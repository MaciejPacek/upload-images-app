<style lang="less" scoped>
  @import "./components/main.less";
</style>  
<template>
  <div id="app" style="background: #fffbf8;">
    <div class="page-background">
      <div class="main-page">
        <div class="header-background">
          <div class="header">
            <ul class="links">
              <li class="default-link">
                <a href="/pl" >
                  <p class="default-text-main-page text">Home</p>
                </a>
              </li>
              <li class="default-link">
                <a href="/pl" >
                  <p class="default-text-main-page text">Galeria</p>
                </a>
              </li>
            </ul>
            <div class="logo">
              <img class="img-logo" src="./assets/img/slonecznik.png" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="main-background"></div>
    <UploadImageComponent />
  </div>
</template>

<script>
import UploadImageComponent from './components/upload-images-component/UploadImageComponent.vue';

export default {
  name: 'App',
  components: {
    UploadImageComponent
  }
}
</script>