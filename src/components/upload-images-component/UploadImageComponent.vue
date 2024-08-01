<template>
    <div>
     <p>Upload image component</p>
    </div>
  </template>
  
  <script>
  export default {
    name: 'UploadImageComponent',
    data() {
      return {
        isOpen: false,  // Definicja zmiennej isOpen w data
      };
    },
    methods: {
      toggleMenu() {
        this.isOpen = !this.isOpen;  // Przełączanie stanu isOpen
      },
    },
  };
  </script>