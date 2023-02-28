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
  <div class="main_content">
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

    <div class="load_more_btn">
      <button>Load More</button>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.main_content {
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

.cards {
  padding: 20px 0;
}

.cards_content {
  padding: 1rem;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  gap: 40px 10px;
  justify-content: space-between;
}

.load_more_btn {
  padding: 20px 0;
  display: flex;
  justify-content: center;
  button {
    cursor: pointer;
    font-family: "Oswald", sans-serif;
    text-transform: uppercase;
    font-size: 1rem;
    background-color: #0082f9;
    padding: 12px 72px;
  }
}
</style>
