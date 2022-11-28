<template>
  <footer>
    <div id="links">
      <div class="categoria">
        <h2>DC COMICS</h2>
        <span>Characters</span>
        <span>Comics</span>
        <span>Movies</span>
        <span>TV</span>
        <span>Games</span>
        <span>Videos</span>
        <span>News</span>
      </div>
      <div class="categoria">
        <h2>SHOP</h2>
        <span>Shop DC</span>
        <span>Shop DC Collectibles</span>
      </div>
      <div class="categoria">
        <h2>DC</h2>
        <span>Terms of use</span>
        <span>Privacy policy (new)</span>
        <span>Ad Choices</span>
        <span>Advertising</span>
        <span>Jobs</span>
        <span>Subscriptions</span>
        <span>Talent Workshops</span>
        <span>CPSC Certificates</span>
        <span>Ratings</span>
        <span>Shop Help</span>
        <span>Contact Us</span>
      </div>
      <div class="categoria">
        <h2>Sites</h2>
        <span>DC</span>
        <span>MAD Magazine</span>
        <span>DC Kids</span>
        <span>DC Universe</span>
        <span>DC Power Visa</span>
      </div>
      <img id="dc" src="../assets/dc-logo-bg.png" alt="errore">
    </div>
    <div id="last">
      <button>SIGN-UP NOW!</button>
      <div id="socials">
        <span>FOLLOW US</span>
        <img src="../assets/footer-facebook.png" alt="errore">
        <img src="../assets/footer-twitter.png" alt="errore">
        <img src="../assets/footer-youtube.png" alt="errore">
        <img src="../assets/footer-pinterest.png" alt="errore">
        <img src="../assets/footer-periscope.png" alt="errore">
        
      </div>

    </div>
  </footer>
</template>

<!-- Script -->
<script>
export default {
  name: 'FooterLinks',
  props: {
    
  }
}
</script>

<!-- CSS -->
<style scoped lang="scss">
footer{
  background-image: url('../assets/footer-bg.jpg');
  height: 400px;
  background-repeat: no-repeat;
  background-size: cover;
  #links{
    display: flex;
    flex-wrap: wrap;
    flex-direction: column;
    width: 600px;
    height: 350px;
    text-align: left;
    padding: 0px 200px 50px 200px;
  }
  #last{
    background-color: #303030;
    height: 100px;
    button{
      color: white;
      background-color: #303030;
      display: inline-block;
      border: 1px solid #0282f9;
      padding: 10px 20px;
      font-weight: bold;
      font-size: 20px;
      float: left;
      margin-top: 28px;
      margin-left: 200px;
    }
    #socials{
      display: flex;
      float: right;
      margin-top: 40px;
      margin-right: 400px;
      gap: 20px;
      span{
        font-weight: bold;
        color: #0282f9;
      }
      img{
        
      }
    }
  }
}

span{
  display: block;
  color: #6e665f;
  margin-bottom: 5px;
}

h2{
  color: white;
}

#dc{
  position: relative;
  bottom: 70px;
  left: 400px;
  width: 500px;
  z-index: 1;
}
</style>