<template>
  <h1>
    Componentes en VUE

     
  </h1>
  <hr>
  <card url="https://cdn.svgporn.com/logos/vue.svg" nombre="Vue.js" pagina="https://vuejs.org/"/>
  <card url="https://cdn.svgporn.com/logos/vuetifyjs.svg" nombre="Vuetify"/>
  <card url="https://cdn.svgporn.com/logos/angular-icon.svg" nombre="Angular"/>
  <card url="https://cdn.svgporn.com/logos/angular.svg" nombre="Angular 2"/>
  <card url="https://cdn.svgporn.com/logos/create-react-app.svg" nombre="React"/>
  </template>


<script>
  import Card from "./components/Card.vue"
  export default {
    components:{
      Card
    },
  };

</script>
  