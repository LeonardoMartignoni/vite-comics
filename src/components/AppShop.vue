<script></script>

<template>
  <div class="shop">
    <div class="container">
      <ul class="shop_list">
        <li>
          <a href="#">
            <img
              src="../assets/img/buy-comics-digital-comics.png"
              alt=""
            />
            <span class="buy_text">Digital Comics</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img
              src="../assets/img/buy-comics-merchandise.png"
              alt=""
            />
            <span class="buy_text">DC Merchandise</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img
              src="../assets/img/buy-comics-subscriptions.png"
              alt=""
            />
            <span class="buy_text">Subscription</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img
              src="../assets/img/buy-comics-shop-locator.png"
              alt=""
            />
            <span class="buy_text">Comic Shop Locator</span>
          </a>
        </li>
        <li>
          <a href="#">
            <img
              src="../assets/img/buy-dc-power-visa.svg"
              alt=""
              id="dc_power_visa_icon"
            />
            <span class="buy_text">DC Power Visa</span>
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.shop {
  background-color: #0082f9;

  .shop_list {
    color: white;
    padding: 2rem 0;
    display: flex;
    justify-content: space-around;

    li {
      text-transform: uppercase;
      font-size: 0.9rem;
      display: flex;
      align-items: center;

      a {
        display: flex;
        align-items: center;
        gap: 10px;
      }
    }

    img {
      height: 50px;
    }

    #dc_power_visa_icon {
      height: 35px;
    }
  }
}
</style>
