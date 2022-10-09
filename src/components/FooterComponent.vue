<template>
  <footer>
  <div class="top-footer">
    <div class="footer-link">
      <img src="../assets/img/buy-comics-digital-comics.png" alt="">
      <p class="text-white">DIGITAL COMICS</p>
    </div>
    <div class="footer-link">
      <img src="../assets/img/buy-comics-merchandise.png" alt="">
      <p class="text-white">DC MERCHANDISE</p>
    </div>
    <div class="footer-link">
      <img src="../assets/img/buy-comics-subscriptions.png" alt="">
      <p class="text-white">SUBSCRIPTION</p>
    </div>
    <div class="footer-link">
      <img src="../assets/img/buy-comics-shop-locator.png" alt="">
      <p class="text-white">POSITION</p>
    </div>    
  </div>


  <div class="mid-footer">
    <div class="mid-footer-container">
      <div class="left-footer">
     
       <div>
        <h3 class="text-white" >DC COMICS</h3>
        <ul>
          <li>
                <a class="text-white" href="#">CARACTERS</a>
            </li>
            <li>
                <a class="text-white" href="#">COMICS</a>
            </li>
            <li>
                <a class="text-white" href="#">MOVIES</a>
            </li>
            <li>
                <a class="text-white" href="#">TV</a>
            </li>
            <li>
                <a class="text-white" href="#">GAMES</a>
            </li>
            <li>
                <a class="text-white" href="#">COLLECTIBLES</a>
            </li>
            <li>
                <a class="text-white" href="#">VIDEOS</a>
            </li><li>
                <a class="text-white" href="#">FANS</a>
            </li>
            <li>
                <a class="text-white" href="#">NEWS</a>
            </li>
            <li>
                <a class="text-white" href="#">SHOP</a>
            </li>
        </ul>

       </div>
        <div>
          <H3 class="text-white">SHOP</H3>
          <ul>
            <li>
                  <a class="text-white" href="#">Shop DC</a>
              </li>
              <li>
                  <a class="text-white" href="#">Shop DC Collectibles</a>
              </li>
          </ul>
        </div>
      
      </div>
      <div class="right-footer">
        <div>
          <H3 class="text-white">DC</H3>
          <ul>
            <li>
                  <a class="text-white" href="#">Terms of Usse</a>
              </li>
              <li>
                  <a class="text-white" href="#">Privacy policy (New)</a>
              </li>
              <li>
                  <a class="text-white" href="#">Add Choices</a>
              </li>
              <li>
                  <a class="text-white" href="#">Advertising</a>
              </li>
              <li>
                  <a class="text-white" href="#">Jobs</a>
              </li>
              <li>
                  <a class="text-white" href="#">Subscription</a>
              </li>
              <li>
                  <a class="text-white" href="#">Talent Workshops</a>
              </li>
              <li>
                  <a class="text-white" href="#">CPSC Certificates</a>
              </li>
              <li>
                  <a class="text-white" href="#">Ratings</a>
              </li>
              <li>
                  <a class="text-white" href="#">Shop Help</a>
              </li>
              <li>
                  <a class="text-white" href="#">Contact Us</a>
              </li>
          </ul>
        </div>
        <div>

          <H3 class="text-white">SITES</H3>
          <ul>
            <li>
                  <a class="text-white" href="#">DC</a>
              </li>
              <li>
                  <a class="text-white" href="#">MAD Magazine</a>
              </li>
              <li>
                  <a class="text-white" href="#">DC Kids</a>
              </li>
              <li>
                  <a class="text-white" href="#">DC Universe</a>
              </li>
              <li>
                  <a class="text-white" href="#">DC Power Visa</a>
              </li>
          </ul>
        </div>


      </div>
    </div>
    
    <div></div>

  </div>





  <div class="bottom-footer">bottom</div>
</footer>
</template>

<script>
export default {
    name:'FooterComponent'

}
</script>

<style
lang="scss" scoped>

footer{
  background-color: hsl(209deg 98% 49%);  
}
.top-footer {
  margin: 50px auto;
  max-width: 1200px;
  background-color: hsl(209deg 98% 49%);
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  
}
.footer-link{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
img {
  width: 50%;
  height: 100%;
  padding-right: 10%;
}
p {
  text-align: center;
  padding-top: 40px;
}
.text-white{
  color: white;
}

/*MID FOOTER*/
.mid-footer{  
  background-image: url(../assets/img/footer-bg.jpg) ;
  
}
.mid-footer-container{
  margin: 50px auto;
  max-width: 300px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;  
  
}
a {
  text-decoration-line: none; 
}
h3 {
  margin-top: 10px;
  margin-bottom: 10px;
}
li {
  list-style: none;
}

</style>