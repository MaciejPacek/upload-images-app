<style lang="less" scoped>
  @import "./components/main.less";
</style>

<template>
  <div id="app" style="background: #fffbf8;">
    <div class="page-background">
      <div class="main-page">
        <div class="header-background">
          <div class="header">
            <div class="left-links">
              <ul class="links">
                <li class="default-link">
                  <a href="/pl">
                    <p class="default-text-main-page text">Home</p>
                  </a>
                </li>
                <li class="default-link">
                  <a href="/pl">
                    <p class="default-text-main-page text">Galeria</p>
                  </a>
                </li>
                <li class="default-link">
                  <a href="/pl">
                    <p class="default-text-main-page text">O nas</p>
                  </a>
                </li>
              </ul>
            </div>
            <div class="logo">
              <img class="img-logo" src="./assets/img/slonecznik-log.png" />
            </div>
            <div class="right-links">
              <!-- Możliwe linki po prawej stronie -->
            </div>
          </div>
        </div>

        <div class="main-background">
          <div class="main">
            <div class="main-text">
              <h1 class="big-h2 default-h2">
                <b>Witajcie Szanowni Goście!</b>
              </h1>
              <div class="text">
                <p>Jeśli macie ochotę podzielić się z nami swoimi zdjęciami, które zrobiliście podczas wesela to możecie użyć tej strony.</p>
                <p>Później pośmiejemy się razem :)</p>
                <p>Jeśli wolicie wysłać zdjęcia w tradycyjny sposób to udostępniliśmy dla Was adres email: <b>maciej.i.kornelia@gmail.com</b></p>
              </div>
            </div>
          </div>
        </div>

        <div class="slogan-background">
          <div class="slogan-border">
            <div class="slogan">
              <p>Do poniższego formularza możecie dodać wybrane zdjęcia, którymi chcecie się podzielić. Ale uwaga, zdjęcia te później będzie można przeglądać w galeri na stronie.</p>
              <div class="logo">
                <img src="./assets/img/slonecznik-log.png" />
              </div>
            </div>
          </div>
        </div>
        
        <UploadImageComponent />
        
        <div class="background-footer">
          <footer>
            <div class="left">
              <a href="/pl" class="router-link-active router-link-exact-active">
                <img class="img-logo" src="./assets/img/slonecznik-log.png" />
              </a>
            </div>
            <div class="copyright">
              <p>&copy; 2024 Misiek&Kotecek - International Company. Spółka z Z.O.O. Wszelkie prawa zastrzeżone.</p>
            </div>
          </footer>
        </div>
      </div>
    </div>
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
