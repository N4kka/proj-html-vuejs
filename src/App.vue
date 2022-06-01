<template>
  <div id="app">
    <AppHeader />
    <AppJumbotron />
    <AppFirstSection />
    <AppStats />
    <AppSecondSection />
    <AppCoreValues />
    <AppThirdSection />
    <AppFourthSection />
    <AppFifthSection />
    <AppCta />
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppJumbotron from "./components/AppJumbotron.vue";
import AppFirstSection from "./components/AppFirstSection.vue";
import AppStats from "./components/AppStats.vue";
import AppSecondSection from "./components/AppSecondSection.vue";
import AppCoreValues from "./components/AppCoreValues.vue";
import AppThirdSection from "./components/AppThirdSection.vue";
import AppFourthSection from "./components/AppFourthSection.vue";
import AppFifthSection from "./components/AppFifthSection.vue";
import AppCta from "./components/AppCta.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AppJumbotron,
    AppFirstSection,
    AppStats,
    AppSecondSection,
    AppCoreValues,
    AppThirdSection,
    AppFourthSection,
    AppFifthSection,
    AppCta,
    AppFooter,
  },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Mukta:wght@200;300;400;700&display=swap");
@import "~@fortawesome/fontawesome-free/css/all.min.css";
@import "~bootstrap/scss/bootstrap.scss";

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
}
</style>
