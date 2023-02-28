<script></script>

<template>
  <main>
    <div class="container">
      <span class="series">Current Series</span>
    </div>

    <div class="cards">
      <div class="container">
        <div class="cards_content">
          <div class="card">
            <img
              src="https://picsum.photos/200/200"
              alt=""
            />
            <span class="smallCardText">Action Comics</span>
          </div>
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
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  gap: 10px;
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
