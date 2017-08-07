<template>
  <div id="app">
    <Header></Header>
    <Tab></Tab>
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
    <Player></Player>
  </div>
</template>

<script>
  import Header from 'components/header/Header'
  import Tab from 'components/tab/Tab'
  import Player from 'components/player/Player'

  export default {
    components: {
      Header,
      Tab,
      Player
    }
  }
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
</style>
