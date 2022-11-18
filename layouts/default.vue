<template>
  <v-app dark>
    <v-app-bar :clipped-left="clipped" fixed app>
      <NuxtLink style="text-decoration: none; color: inherit;"
 to="/">
        <v-toolbar-title>
          {{ title }}
        </v-toolbar-title>
      </NuxtLink>

      <v-spacer />
      <v-btn icon @click.stop="rightDrawer = !rightDrawer">
        <v-icon>mdi-menu</v-icon>
      </v-btn>
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>

    <v-footer :absolute="!fixed" app>
      <Footer />
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: "DefaultLayout",
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: "mdi-apps",
          title: "hhh",
          to: "/",
        },
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: "soowcode-rec",
      togo: "/",
    };
  },
};
</script>
