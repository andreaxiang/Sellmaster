<template>
  <div id="app">

    <v-header></v-header>

    <v-tab></v-tab>

    <!--路由外链-->
    <router-view></router-view>

  </div>
</template>

<script>

  import header from './components/header/header.vue'
  import tab from './components/tab/tab.vue'

  export default {
    name: 'app',
    components: { 'v-header': header, 'v-tab': tab},
    data: function() {
      return {
        seller: {}
      }
    }
  }


</script>

<style rel="stylesheet/scss" lang="scss">
  html, body {
    font-size: 16px;
  }
  #app {

  }

</style>
