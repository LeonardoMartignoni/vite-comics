<script></script>

<template>
  <footer>
    <div class="upper_footer">
      <div class="container">
        <ul class="shop_list">
          <li>
            <img
              src="../assets/img/buy-comics-digital-comics.png"
              alt=""
            />
            <span class="buy_text">Digital Comics</span>
          </li>
          <li>
            <img
              src="../assets/img/buy-comics-merchandise.png"
              alt=""
            />
            <span class="buy_text">DC Merchandise</span>
          </li>
          <li>
            <img
              src="../assets/img/buy-comics-subscriptions.png"
              alt=""
            />
            <span class="buy_text">Subscription</span>
          </li>
          <li>
            <img
              src="../assets/img/buy-comics-shop-locator.png"
              alt=""
            />
            <span class="buy_text">Comic Shop Locator</span>
          </li>
          <li>
            <img
              src="../assets/img/buy-dc-power-visa.svg"
              alt=""
              id="dc_power_visa_icon"
            />
            <span class="buy_text">DC Power Visa</span>
          </li>
        </ul>
      </div>
    </div>

    <div class="middle_footer">
      <div class="container">
        <div class="links">
          <div class="link">
            <h2>DC Comics</h2>
            <ul>
              <li>Characters</li>
              <li>Comics</li>
              <li>Movies</li>
              <li>TV</li>
              <li>Games</li>
              <li>Videos</li>
              <li>News</li>
            </ul>
            <div class="link">
              <h2>Shop</h2>
              <ul>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>
              </ul>
            </div>
          </div>
          <div class="link">
            <h2>DC</h2>
            <ul>
              <li>Terms Of Use</li>
              <li>Privacy policy (New)</li>
              <li>Ad Choices</li>
              <li>Advertising</li>
              <li>Jobs</li>
              <li>Subscriptions</li>
              <li>Talent Workshops</li>
              <li>CPSC Certificates</li>
              <li>Ratings</li>
              <li>Shop Help</li>
              <li>Contact Us</li>
            </ul>
          </div>
          <div class="link">
            <h2>SITES</h2>
            <ul>
              <li>DC</li>
              <li>MAD Magazine</li>
              <li>DC Kids</li>
              <li>DC Universe</li>
              <li>DC Power Visa</li>
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

<style scoped>
ul {
  list-style-type: none;
}
.upper_footer {
  background-color: #0082f9;
}

.shop_list {
  color: white;
  padding: 2rem 0;
  display: flex;
  justify-content: space-around;
}

.shop_list li {
  display: flex;
  align-items: center;
  gap: 10px;
  text-transform: uppercase;
  font-size: 0.9rem;
}

.shop_list img {
  height: 50px;
}

.shop_list #dc_power_visa_icon {
  height: 35px;
}

.middle_footer {
  background-image: url("../assets/img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  color: #8f8f8f;
  padding: 2.5rem 0;
}

.links {
  display: flex;
  gap: 30px;
}

.middle_footer h2 {
  font-family: "Oswald", sans-serif;
  color: white;
  text-transform: uppercase;
}

.middle_footer ul {
  margin: 10px 0;
}

.middle_footer li {
  font-size: 0.9rem;
  margin-bottom: 3px;
}

.bottom_footer {
  padding: 1.8rem 0;
  background-color: #303030;
}

.bottom_footer_content {
  display: flex;
  justify-content: space-between;
}

.bottom_footer button {
  padding: 0.7rem;
  color: white;
  border: 2px solid #0082f9;
}

.bottom_footer .social_follow_us {
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
</style>
