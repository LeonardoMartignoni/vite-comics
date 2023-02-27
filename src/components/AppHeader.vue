<script></script>

<template>
  <header>
    <div class="container">
      <a href="#">
        <img
          src="../assets/img/dc-logo.png"
          alt="DC Logo"
          id="logo"
        />
      </a>

      <nav>
        <ul>
          <li><a href="#">Characters</a></li>
          <li><a href="#">Comics</a></li>
          <li><a href="#">Movies</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">Games</a></li>
          <li><a href="#">Collectibles</a></li>
          <li><a href="#">Videos</a></li>
          <li><a href="#">Fans</a></li>
          <li><a href="#">News</a></li>
          <li><a href="#">Shop</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style scoped>
header {
  padding: 15px 0;
}

#logo {
  width: 70px;
}

.container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

ul li {
  display: inline-block;
  margin-left: 2rem;
  text-transform: uppercase;
  font-weight: 600;
  height: 100%;
}
</style>
