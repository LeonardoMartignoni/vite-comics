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
          <li class="nav_active"><a href="#">Comics</a></li>
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
#logo {
  width: 70px;
}

.container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

ul li {
  font-family: "Oswald", sans-serif;
  display: inline-block;
  margin-left: 2rem;
  text-transform: uppercase;
  font-weight: 600;
}

ul .nav_active {
  color: #0082f9;
  box-shadow: inset 0 -5px #0082f9;
}

ul a {
  display: inline-block;
  height: 100px;
  line-height: 100px;
}
</style>
