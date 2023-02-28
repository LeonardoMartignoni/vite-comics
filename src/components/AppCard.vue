<script>
export default {
  props: {
    image: Image,
    text: String,
  },
};
</script>

<template>
  <div>
    <div class="card">
      <img
        :src="image"
        alt=""
      />
      <span class="smallCardText">{{ text }}</span>
    </div>
  </div>
</template>

<style scoped>
img {
  width: 200px;
  height: 200px;
}
.smallCardText {
  display: block;
  text-transform: uppercase;
  font-size: 0.9rem;
  margin-top: 5px;
}
</style>
