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
              src="../assets/img/buy-comics-digital-comics.png"
              alt=""
            />
            <span class="buy_text">Digital Comics</span>
          </li>
          <li>
            <img
              src="../assets/img/buy-comics-digital-comics.png"
              alt=""
            />
            <span class="buy_text">Digital Comics</span>
          </li>
          <li>
            <img
              src="../assets/img/buy-comics-digital-comics.png"
              alt=""
            />
            <span class="buy_text">Digital Comics</span>
          </li>
          <li>
            <img
              src="../assets/img/buy-comics-digital-comics.png"
              alt=""
            />
            <span class="buy_text">Digital Comics</span>
          </li>
        </ul>
      </div>

      <div class="middle_footer">
        <div class="container">
          <div class="links">
            <div class="link">
              <h3>DC Comics</h3>
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
                <h3>Shop</h3>
                <ul>
                  <li>Shop DC</li>
                  <li>Shop DC Collectibles</li>
                </ul>
              </div>
            </div>
            <div class="link">
              <h3>DC</h3>
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
              <h3>SITES</h3>
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

      <div class="bottom_footer"></div>
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
  height: 60px;
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

.middle_footer h3 {
  color: white;
  text-transform: uppercase;
  padding: 10px 0;
}

.middle_footer li {
  font-size: 0.9rem;
  margin-bottom: 3px;
}
</style>
