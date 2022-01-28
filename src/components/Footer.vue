<template>
  <footer>
    <div class="submenu">
      <div class="container">
        <div class="link">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          <div>
            Digital comics
          </div>
        </div>
        <div class="link">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          <div>
            Digital comics
          </div>
        </div>
        <div class="link">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          <div>
            Digital comics
          </div>
        </div>
        <div class="link">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          <div>
            Digital comics
          </div>
        </div>
        <div class="link">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
          <div>
            Digital comics
          </div>
        </div>
      </div>
    </div>



    <div class="main-footer">
      <div class="container">
        <div class="link-footer">
          <div class="link-title">
            Dc comics
          </div>
          <ul>
            <li> 
              <a href="#">
                Characters
              </a>
            </li>
            <li> 
              <a href="#">
                Comics
              </a>
            </li>
            <li> 
              <a href="#">
                Movies
              </a>
            </li>
            <li> 
              <a href="#">
                TV
              </a>
            </li>
            <li> 
              <a href="#">
                Games
              </a>
            </li>
            <li> 
              <a href="#">
                Videos
              </a>
            </li>
            <li> 
              <a href="#">
                news
              </a>
            </li>
          </ul>
          <div class="link-title">
            Shop
          </div>
          <ul>
            <li> 
              <a href="#">
                Shop DC
              </a>
            </li>
            <li> 
              <a href="#">
                Shop DC Collectibles
              </a>
            </li>
          </ul>
        </div>

        <div class="link-footer">
          <div class="link-title">
            Dc
          </div>
          <ul>
            <li> 
              <a href="#">
                Term Of Use
              </a>
            </li>
            <li> 
              <a href="#">
                Privacy policy (NEW)
              </a>
            </li>
            <li> 
              <a href="#">
                Ad Choices
              </a>
            </li>
            <li> 
              <a href="#">
                Advertising
              </a>
            </li>
            <li> 
              <a href="#">
                Jobs
              </a>
            </li>
            <li> 
              <a href="#">
                Subscriptions
              </a>
            </li>
            <li> 
              <a href="#">
                Talent Workshops
              </a>
            </li>
            <li> 
              <a href="#">
                CPSC Certificates
              </a>
            </li>
            <li> 
              <a href="#">
                Ratings
              </a>
            </li>
            <li> 
              <a href="#">
                Shop Help
              </a>
            </li>
            <li> 
              <a href="#">
                Contact Us
              </a>
                
            </li>
          </ul>
        </div>

        <div class="link-footer">
          <div class="link-title">
            Sites
          </div>
          <ul>
            <li> 
              <a href="#">
                DC
              </a>
            </li>
            <li> 
              <a href="#">
                MAD Magazine
              </a>
            </li>
            <li> 
              <a href="#">
                DC Kids
              </a>
            </li>
            <li> 
              <a href="#">
                DC Universe
              </a>
            </li>
            <li> 
              <a href="#">
                DC Power Visa
              </a>
            </li>
          </ul>
        </div>




        <div class="logo-footer">
          <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
      </div>
    </div>


    <div class="contact">
      <div class="container">
        <div class="btn">
          Sign-up now!
        </div>
        <div class="social">
          <a href="#">Follow us</a>
          <div class="social-icon">
            <a href="#">
              <img src="../assets/img/footer-facebook.png" alt="">
            </a>
            <a href="#">
              <img src="../assets/img/footer-twitter.png" alt="">
            </a>
            <a href="#">
              <img src="../assets/img/footer-youtube.png" alt="">
            </a>
            <a href="#">
              <img src="../assets/img/footer-pinterest.png" alt="">
            </a>
            <a href="#">
              <img src="../assets/img/footer-periscope.png" alt="">
            </a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../assets/style/partials/variables.scss';
footer{
  color: white;

  .submenu{
    background-color: $primarycolor;
    position: relative;

    .container{
      display: flex;
      justify-content: space-around;

      .link{
        display: flex;
        align-items: center;

        img{
          height: 70px;
        }
      }
    }
  }
}


.main-footer{
  background-image: url("../assets/img/footer-bg.jpg");
  background-size: cover;
  height: 370px;
  
  .container{
    display: flex;
    justify-content: space-between;

    .link-title{
      font-size: 20px;
      font-weight: bold;
      text-transform: uppercase;
      margin: 20px 0;
    }
    li{
      margin: 5px 0;

      a{
        color: gray;
      }
    }
  



    .logo-footer{
      margin-top: -100px;
    }
  }
}


.contact{
  background-color: $secondarycolor;
  position: relative;
  .container{
    display: flex;
    align-items: center;
    justify-content: space-between;

    .btn{
    border: 1px solid $primarycolor;
    padding: 10px;
    text-transform: uppercase;
    }

    .social{
      display: flex;
      align-items: center;
      text-transform: uppercase;
      font-weight: bold;


      a{
        margin: 0 10px;
        color: $primarycolor;
      }
    }
  }
  
}


</style>
