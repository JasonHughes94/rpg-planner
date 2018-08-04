<template>
  <div id="app">
    <Header />
  </div>
</template>

<script>
import Header from './components/Header.vue';

export default {

  name: 'app',
  components: {
    Header,
  },
};
</script>

<style lang="scss">
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-kerning: auto;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  margin: 0;
}
</style>
