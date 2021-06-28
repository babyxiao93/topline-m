<template>
  <div id="app">
    <h1>hello 大宝 </h1>
    <div>
      <i class="toutiao toutiao-dianzan"></i>
    </div>
    <router-view />
  </div>
</template>
<script>

export default {
  name: 'App'
}
</script>

<style lang="less">
#app .toutiao{
  font-size: 48px;
}

</style>
