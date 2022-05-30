<template>
  <div id="app">
    <AppHeader />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";

export default {
  name: "App",
  components: {
    AppHeader,
  },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Mukta:wght@200;300;400;700&display=swap");

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

html {
  font-family: "Mukta", sans-serif;
}

body {
  height: 100vh;
  background-color: black;
}
</style>
