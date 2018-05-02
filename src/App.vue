<template>
    <div id="app">
        <LeftSider></LeftSider>
        <div class="main">
            <router-view></router-view>
        </div>
    </div>
</template>

<script>
import LeftSider from '@/components/common/LeftSider'

export default {
  name: 'App',
  components: {
    LeftSider
  }
}
</script>

<style lang="scss">
@import 'static/styles/base';
@import 'static/styles/common';

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  padding-left: 50px;
  position: relative;
  width: 100%;
  height: 100%;
}
.main {
    width: 100%;
    height: 100%;
    background: #eff2f7;
}
</style>
