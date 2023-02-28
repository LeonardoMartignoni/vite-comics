<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppShop from "./components/AppShop.vue";
import AppFooter from "./components/AppFooter.vue";
import AppJumbotron from "./components/AppJumbotron.vue";

export default {
  components: {
    AppHeader,
    AppMain,
    AppShop,
    AppFooter,
    AppJumbotron,
  },
};
</script>

<template>
  <AppHeader />
  <AppJumbotron />
  <main>
    <AppMain />
  </main>
  <AppShop />
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
  max-height: 100%;
  object-fit: cover;
}

a {
  text-decoration: none;
  color: inherit;
}

button {
  background: none;
  border: 0;
  color: inherit;
}

ul {
  list-style-type: none;
}

.container {
  margin: 0 auto;
  max-width: 1200px;
}
</style>
