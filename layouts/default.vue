<template>
  <div id="app">
    <AppTopBar />
    <div class="app">
      <Nuxt />
    </div>
  </div>
</template>
<script>
import AppTopBar from "~/components/AppTopBar";
export default {
  components: {
    AppTopBar,
  },
};
</script>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
#app .app {
  padding: 10px;
}
</style>
