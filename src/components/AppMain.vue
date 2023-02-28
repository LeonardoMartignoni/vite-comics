<script>
import AppCard from "./AppCard.vue";
import comicsList from "../assets/comics.js";

export default {
  components: { AppCard },

  data() {
    return {
      comics: comicsList,
    };
  },

  props: {
    image: Image,
    text: String,
  },
};
</script>

<template>
  <main>
    <div class="container">
      <span class="series">Current Series</span>
    </div>

    <div class="cards">
      <div class="container">
        <div class="cards_content">
          <AppCard
            v-for="comic in comics"
            :text="comic.series"
            :image="comic.thumb"
          />
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
main {
  color: white;
  background-color: #1c1c1c;
}

.series {
  font-size: 1.7rem;
  font-family: "Oswald", sans-serif;
  padding: 8px 16px;
  text-transform: uppercase;
  font-weight: bold;
  background-color: #0082f9;
  position: relative;
  top: -20px;
}

.cards_content {
  padding: 1rem;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  gap: 10px;
}

.card {
  flex: 0 0 auto;
  width: calc(16.66666667% - 10px);
}
</style>
