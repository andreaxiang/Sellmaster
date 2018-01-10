<template>
  <div id="app">

    <v-header></v-header>

    <div class="tab">
      <div class="tab-items">
        <a v-link="{path: '/goods'}">商品</a>
      </div>
      <div class="tab-items">
        <a v-link="{path: '/ratings'}">评论</a>
      </div>
      <div class="tab-items">
        <a v-link="{path: '/seller'}">商家</a>
      </div>
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

<style lang="scss">
  #app
    .tab {
      display: flex;
      width: 100%;
      height: 40px;
      line-height: 40px;
    }
    .tab-items {
      flex: 1;
      text-align: center;
    }





</style>
