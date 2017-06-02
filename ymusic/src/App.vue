<template>
  <div id="app">
    <Header></Header>
    <Tab></Tab>
    <router-view></router-view>
  </div>
</template>

<script>
  import Header from 'components/header/Header'
  import Tab from 'components/tab/Tab'

  export default {
    components: {
      Header,
      Tab
    }
  }
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
</style>
