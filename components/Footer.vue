<template>
    <footer class="footer">
      <div class="footer-notes">
        <div class="col" style="float:left;width:60%;">
          <div style="margin-bottom:20px;">About us<br/><a href="https://github.com/nuxt/nuxt.js" target="_blank">Nuxt.js</a></div>
          <div style="margin-bottom:20px;">Our partenairs <br/><a href="http://spaceipsum.com" target="_blank">http://spaceipsum.com</a></div>
          <div style="margin-bottom:20px;"> To join us<br/><a href="http://uigradients.com" target="_blank">http://uigradients.com</a></div>
        </div>
        <div class="col" style="float:left;width:40%;">
          <div style="margin-bottom:20px;">
            <a style="margin-right:20px;" href="https://github.com/cosmicjs" target="_blank">
              <i class="fa fa-github social-icon"></i>
            </a>
            <a href="https://twitter.com/cosmic_js" target="_blank">
              <i class="fa fa-twitter social-icon"></i>
            </a>
          </div>
          <div style="margin-bottom:20px;">&copy; {{ new Date().getFullYear() }} SoowCode</div>
          <div style="margin-bottom:20px;">
            <a href="https://soowcode.github.io" target="_blank">
              <img style="float:left;margin-right:15px;position:relative; border-radius: 55%;" src="https://i.imgur.com/47klUK0.png" width="28" height="28"/>
              <span class="powered-by">Proudly powered by SoowCode</span>
            </a>
          </div>
        </div>
        <div class="clearfix"></div>
      </div>
    </footer>
  </div>
</template>
<script>
    export default{
        name: "footer"
    }
</script>
<style>
.footer {
  background-color: #333;
  color: #fff;
  font-size: 18px;
  width: 100%;
}
.footer-notes {
  margin: 0 auto;
  max-width: 960px;
  padding: 15px;
  padding-bottom: 60px;
  padding-top: 40px;
}
</style>