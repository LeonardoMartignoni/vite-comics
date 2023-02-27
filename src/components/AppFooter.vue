<script>
export default {
  data() {
    return {
      comicsLinks: [
        {
          linkName: "Characters",
          linkHref: "#",
        },
        {
          linkName: "Comics",
          linkHref: "#",
        },
        {
          linkName: "Movies",
          linkHref: "#",
        },
        {
          linkName: "TV",
          linkHref: "#",
        },
        {
          linkName: "Games",
          linkHref: "#",
        },
        {
          linkName: "Videos",
          linkHref: "#",
        },
        {
          linkName: "News",
          linkHref: "#",
        },
      ],

      shopLinks: [
        {
          linkName: "Shop DC",
          linkHref: "#",
        },
        {
          linkName: "Shop DC Collectibles",
          linkHref: "#",
        },
      ],

      dcLinks: [
        {
          linkName: "Terms Of Use",
          linkHref: "#",
        },
        {
          linkName: "Privacy policy (New)",
          linkHref: "#",
        },
        {
          linkName: "Ad Choices",
          linkHref: "#",
        },
        {
          linkName: "Advertising",
          linkHref: "#",
        },
        {
          linkName: "Jobs",
          linkHref: "#",
        },
        {
          linkName: "Subscriptions",
          linkHref: "#",
        },
        {
          linkName: "Talent Workshops",
          linkHref: "#",
        },
        {
          linkName: "CPSC Certificates",
          linkHref: "#",
        },
        {
          linkName: "Ratings",
          linkHref: "#",
        },
        {
          linkName: "Shop Help",
          linkHref: "#",
        },
        {
          linkName: "Contact Us",
          linkHref: "#",
        },
      ],

      sitesLinks: [
        {
          linkName: "DC",
          linkHref: "#",
        },
        {
          linkName: "MAD Magazine",
          linkHref: "#",
        },
        {
          linkName: "DC Kids",
          linkHref: "#",
        },
        {
          linkName: "DC Universe",
          linkHref: "#",
        },
        {
          linkName: "DC Power Visa",
          linkHref: "#",
        },
      ],
    };
  },
};
</script>

<template>
  <footer>
    <div class="upper_footer">
      <div class="container">
        <div class="links">
          <div class="link">
            <h2>DC Comics</h2>
            <ul>
              <li v-for="link in comicsLinks">
                <a :href="link.linkHref">{{ link.linkName }}</a>
              </li>
            </ul>
            <div class="link">
              <h2>Shop</h2>
              <ul>
                <li v-for="link in shopLinks">
                  <a :href="link.linkHref">{{ link.linkName }}</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="link">
            <h2>DC</h2>
            <ul>
              <li v-for="link in dcLinks">
                <a :href="link.linkHref">{{ link.linkName }}</a>
              </li>
            </ul>
          </div>
          <div class="link">
            <h2>SITES</h2>
            <ul>
              <li v-for="link in sitesLinks">
                <a :href="link.linkHref">{{ link.linkName }}</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <div class="bottom_footer">
      <div class="container">
        <div class="bottom_footer_content">
          <button>SIGN-UP NOW!</button>
          <div class="socials">
            <span class="social_follow_us">FOLLOW US</span>
            <span class="social_links">
              <a href="#">
                <img
                  src="../assets/img/footer-facebook.png"
                  alt=""
                />
              </a>
              <a href="#">
                <img
                  src="../assets/img/footer-twitter.png"
                  alt=""
                />
              </a>
              <a href="#">
                <img
                  src="../assets/img/footer-youtube.png"
                  alt=""
                />
              </a>
              <a href="#">
                <img
                  src="../assets/img/footer-pinterest.png"
                  alt=""
                />
              </a>
              <a href="#">
                <img
                  src="../assets/img/footer-periscope.png"
                  alt=""
                />
              </a>
            </span>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
.upper_footer {
  background-image: url("../assets/img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  color: #8f8f8f;
  padding: 2.5rem 0;

  h2 {
    font-family: "Oswald", sans-serif;
    color: white;
    text-transform: uppercase;
  }

  ul {
    margin: 10px 0;
  }

  li {
    font-size: 0.9rem;
    margin-bottom: 3px;
  }

  .links {
    display: flex;
    gap: 30px;
  }
}

.bottom_footer {
  padding: 1.8rem 0;
  background-color: #303030;

  .bottom_footer_content {
    display: flex;
    justify-content: space-between;
  }

  button {
    padding: 0.7rem;
    color: white;
    border: 2px solid #0082f9;
  }

  .social_follow_us {
    font-family: "Oswald", sans-serif;
    font-size: 1.3rem;
    color: #0082f9;
    font-weight: bold;
  }

  .socials {
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .social_links a {
    margin-left: 1rem;
  }
}
</style>
