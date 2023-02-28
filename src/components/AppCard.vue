<script>
export default {
  props: {
    image: Image,
    text: String,
  },
};
</script>

<template>
  <div class="card">
    <img
      :src="image"
      alt=""
    />
    <span class="smallCardText">{{ text }}</span>
  </div>
</template>

<style scoped>
img {
  width: 200px;
  height: 200px;
  object-position: top;
}

.card {
  flex: 0 0 auto;
  width: calc(16.66666667% - 10px);
}
.smallCardText {
  display: block;
  text-transform: uppercase;
  font-size: 0.9rem;
  margin-top: 5px;
}
</style>
