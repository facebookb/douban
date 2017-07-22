<template>
  <div id="app">
    <router-view class="view"></router-view>
    <router-view class="view" name="subject"></router-view>
  </div>
</template>

<script>
export default {
  name: 'app',
}
</script>

<style lang="scss">
  #app {
    max-width: 568px;
    margin: 0 auto;
  }
  .has-header {
    margin-top: 48px;
  }
  ul, li, a {
    margin: 0;
    padding: 0;
  }
  li {
    list-style: none;
  }
  a {
    text-decoration: none;
  }
</style>
