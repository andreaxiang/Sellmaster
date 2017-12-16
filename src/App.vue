<template>
  <div id="app">

    <v-header></v-header>

    <div class="tab">
      <div class="tab-items">商品</div>
      <div class="tab-items">评论</div>
      <div class="tab-items">商家</div>
    </div>

    <div class="content">
      I am content
    </div>

  </div>
</template>

<script>

  import header from './components/header/header.vue'

  export default {
    name: 'app',
    components: { 'v-header': header}
  }


</script>

<style>
  #app {
    
  }
</style>
