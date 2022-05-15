<template>

  <footer>

    <div class="icon-options">
      <div class="image-container w-70">
        <div class="image-box">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="buy-comics-digital-comics">
          <p>Digital Comics</p>
        </div>
        <div class="image-box">
          <img src="../assets/img/buy-comics-merchandise.png" alt="buy-comics-merchandise">
          <p>Dc Merchandise</p>
        </div>
        <div class="image-box">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="buy-comics-subscriptions">
          <p>Subscription</p>
        </div>
        <div class="image-box special-image-box">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="buy-comics-shop-locator">
          <p>Comic Shop Locator</p>
        </div>
        <div class="image-box">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="buy-dc-power-visa">
          <p>Dc Power Visa</p>
        </div>
      </div>
    </div>

    <div class="footer-container">

        <div class="footer-links">
          <div class="w-70 links-logo-container">

            <div class="links">

              <div class="dc-comics-shop-link">

                <nav>
                  <ul>
                    <h4>DC COMICS</h4>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                  </ul>
                </nav>

                <nav>
                  <ul>
                    <h4>SHOP</h4>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                  </ul>
                </nav>
              </div>

              <div class="dc-link">

                <nav>
                  <ul>
                    <h4>DC</h4>
                    <li><a href="#">Terms Of Use</a></li>
                    <li><a href="#">Privary Policy (New)</a></li>
                    <li><a href="#">Ad Choices</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscriptions</a></li>
                    <li><a href="#">Talent Workshops</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li>
                    <li><a href="#">Contact Us</a></li>
                  </ul>
                </nav>
                
              </div>

              <div class="sites-link">

                <nav>
                  <ul>
                    <h4>SITES</h4>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Visa</a></li>
                  </ul>
                </nav>
                
              </div>

            </div>

            <div class="logo">
              <img src="../assets/img/dc-logo-bg.png" alt="dc-logo-bg">
            </div>

          </div>

        </div>

        <div class="footer-socials-sign-up">
          <div class="w-70 social-login-container">

            <div class="sign-up">
              <p>SIGN-UP NOW!</p>
            </div>

            <div class="socials">
              <p>FOLLOW US</p>
              <img src="../assets/img/footer-facebook.png" alt="social-logo">
              <img src="../assets/img/footer-twitter.png" alt="social-logo">
              <img src="../assets/img/footer-youtube.png" alt="social-logo">
              <img src="../assets/img/footer-pinterest.png" alt="social-logo">
              <img src="../assets/img/footer-periscope.png" alt="social-logo">
            </div>

          </div>
        </div>

    </div>

  </footer>

</template>

<script>
export default {
  name: "myFooter"
}
</script>

<style lang="scss">

.icon-options{
  background-color: #0282F9;
}

.image-container{
  display: flex;
  justify-content: space-between;
  padding: 40px;
}

.image-box{
  display: flex;
  align-items: center;
}

.image-box img{
  width: 2.5rem;
}

.special-image-box img{
  width: 1.5rem;
}

.image-box p{
  font-size: .9rem;
  color: white;
  text-transform: uppercase;
  margin-left: 10px;
}

.footer-links{
  background-image: url("../assets/img/footer-bg.jpg");
  background-size: cover;
  background-repeat: no-repeat;
}

.links-logo-container{
  display: flex;
  justify-content: space-between;
}

.links{
  display: flex;
  padding: 35px 0px;
}

.links h4{
  color: white;
  margin:  20px 50px 10px 0px;
}

.links li{
  margin-bottom: 4px;
  margin-right: 20px;

  &:hover{
    text-decoration: underline;
    color: rgba($color: white, $alpha: 0.5);
  }
}

.links a{
  color: rgba($color: white, $alpha: 0.5);
  font-size: .9rem
}

.logo img{
  width: 25rem;
}

.footer-socials-sign-up{
  background-color: #303030;
}

.social-login-container{
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 30px 0px;
}

.sign-up{
  color: white;
  padding: 10px;
  border: 2px solid #0282F9;
}

.socials{
  display: flex;
  align-items: center;
}

.socials p{
  color: #0282F9;
}

.socials img{
  margin-left: 20px;

  &:hover{
    opacity: 75%;
  }
}

</style>