<template>
  <div id="app">
    <Header></Header>
    <Tab></Tab>
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
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
