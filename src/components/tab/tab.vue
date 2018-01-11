<template>
  <div class="tab">
    <div class="tab-items">
      <router-link to="/goods">商品</router-link>
    </div>
    <div class="tab-items">
      <router-link to="/ratings">评论</router-link>
    </div>
    <div class="tab-items">
      <router-link to="/seller">商家</router-link>
    </div>
  </div>
</template>

<script type="text/ecmascript-6">

  export default {
    data: function () {
      return {}
    }
  }
</script>

<style>
  .tab {
    display: flex;
    width: 100%;
    height: 40px;
    line-height: 40px;
    border-bottom: 1px solid rgba(7,17,27,.1);
  }
  .tab-items {
    flex: 1;
    text-align: center;
  }
  .tab-items .router-link {
    display: block;
    color: rgb(77,85,93);
    font-size: .3rem;
  }
  .tab-items .router-link-active {
    color: rgb(240,20,20);
  }

</style>