<style lang="less" scoped>
  @import "/src/components/upload-images-component/upload-main.less";
</style>
<template>
    <div class="sender">
     <div class="files">
        <div class="pictures"></div>
        <div class="file-input-wrapper file-input-wrapper-empty">
          <input data-v-79477918="" id="file-input-empty" type="file" name="file-input" class="file-input" accept=".jpg, image/*, video/*, .heic" multiple="">
          <label for="file-input-empty" class="file-input-label">
            <span data-v-79477918="" class="plus">+</span>
            <span data-v-79477918="" class="text">Dodaj zdjęcia</span>
          </label>
        </div>
     </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'UploadImageComponent',
    data() {
      return {
        isOpen: false,  
      };
    },
    methods: {
      toggleMenu() {
        this.isOpen = !this.isOpen;  
      },
    },
  };
  </script>