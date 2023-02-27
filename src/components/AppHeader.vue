<script>
export default {
  data() {
    return {
      navLinks: [
        {
          linkName: "Characters",
          linkHref: "#characters",
        },
        {
          linkName: "Comics",
          linkHref: "#comics",
        },
        {
          linkName: "Movies",
          linkHref: "#movies",
        },
        {
          linkName: "TV",
          linkHref: "#tv",
        },
        {
          linkName: "Games",
          linkHref: "#games",
        },
        {
          linkName: "Collectibles",
          linkHref: "#collectibles",
        },
        {
          linkName: "Videos",
          linkHref: "#videos",
        },
        {
          linkName: "Fans",
          linkHref: "#fans",
        },
        {
          linkName: "News",
          linkHref: "#news",
        },
        {
          linkName: "Shop",
          linkHref: "#shop",
        },
      ],

      navActiveLink: 0,
    };
  },
};
</script>

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
          <li
            v-for="(link, index) in navLinks"
            :class="navActiveLink == index ? 'nav_active' : ''"
            @click="navActiveLink = index"
          >
            <a :href="link.linkHref">{{ link.linkName }}</a>
          </li>
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
