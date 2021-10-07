<template>
  <img alt="logo" id="logo" src="./assets/logo.png">
  <ViajaPass msg="Descubra o ViajaPASS"/>
</template>

<script>
import ViajaPass from './components/ViajaPass.vue';

export default {
  name: 'App',
  components: {
    ViajaPass,
  },
};
</script>

<style lang="scss">
#app {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #003C52;
  margin-top: 60px;
}

#logo {
  width: 230px;
}
</style>
