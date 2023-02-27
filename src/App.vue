<script>
import AppHeader from "./components/AppHeader.vue";

export default {
  components: {
    AppHeader,
  },
};
</script>

<template>
  <AppHeader />
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

a {
  text-decoration: none;
  color: inherit;
}

.container {
  margin: 0 auto;
  max-width: 1200px;
}
</style>
