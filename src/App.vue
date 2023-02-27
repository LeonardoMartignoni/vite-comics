<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  },
};
</script>

<template>
  <AppHeader />
  <main>
    <AppMain />
  </main>
  <AppFooter />
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Open Sans", sans-serif;
  color: #606060;
}

img {
  max-width: 100%;
  min-height: 100%;
  object-fit: cover;
}

a {
  text-decoration: none;
  color: inherit;
}

.container {
  margin: 0 auto;
  max-width: 1200px;
}
</style>
