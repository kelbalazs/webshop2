<template>
    <v-app>
      
        <img src="../assets/BuyHive_Logo.png" alt="" width=200px>
        <div>
            Connecting buyers and suppliers using the world’s best <br>
             sourcing experts & technology built by buyers, for buyers.
        </div>
<div class="container"></div>
    <footer>
      <section class="ft-main">
        <div class="ft-main-item">
          <h2 class="ft-title">About Us</h2>
          <ul>
            <li><a href="#">Our Story</a></li>
            <li><a href="#">How to Buy</a></li>
            <li><a href="#">Our Partners</a></li>
            <li><a href="#">Contact Us</a></li>
            <li><a href="#">Careers</a></li>
            <li><a href="#">Terms of Use</a></li>
            <li><a href="#">Privacy Policy</a></li>

          </ul>
        </div>
        <div class="ft-main-item">
          <h2 class="ft-title">Our Services</h2>
          <ul>
            <li><a href="#">Buy</a></li>
            <li><a href="#">Expect Sourcing</a></li>
            <li><a href="#">Turnkey Sourcing Solution</a></li>
           
          </ul>
        </div>
        <div class="ft-main-item">
          <h2 class="ft-title">Account</h2>
          <ul>
            <li><a href="#">Sign In</a></li>
            <li><a href="#">Register to Buy</a></li>
            <li><a href="#">My Profile</a></li>
            <li><a href="#">My Orders</a></li>
            <li><a href="#">Register to Sell</a></li>
            <li><a href="#">Become a Sourcing Expert</a></li>



          </ul>
        </div>
        <div class="ft-main-item">
          <h2 class="ft-title">Our Locations</h2>
          <p>Subscribe to our newsletter to get our latest news.</p>
          <form>
            <input type="email" name="email" placeholder="Enter email address">
            <input type="submit" value="Subscribe">
          </form>
        </div>
      </section>
     
      <section class="ft-social">
        <ul class="ft-social-list">
          <li><a href="#"><i class="fab fa-facebook"></i></a></li>
          <li><a href="#"><i class="fab fa-twitter"></i></a></li>
          <li><a href="#"><i class="fab fa-instagram"></i></a></li>
          <li><a href="#"><i class="fab fa-github"></i></a></li>
          <li><a href="#"><i class="fab fa-linkedin"></i></a></li>
          <li><a href="#"><i class="fab fa-youtube"></i></a></li>
        </ul>
      </section>
     
      <section class="ft-legal">
        <ul class="ft-legal-list">
          <li><a href="#">Terms &amp; Conditions</a></li>
          <li><a href="#">Privacy Policy</a></li>
          <li>© 2022 BuyHive Limited All Rights Reserved</li>
        </ul>
      </section>
    </footer>
    </v-app>
</template>

<style>

* {
    box-sizing: border-box;
    color: black;
    margin: 0; 
    padding: 0;
    text-decoration: none;
}
ul {
    list-style: none;
    padding-left: 0;
}
footer {
    background-color: lightgray;
    line-height: 1.5;
}
footer a {
    text-decoration: none;
}


.ft-title {
    font-size: 1.375rem;
    padding-bottom: 0.625rem;
}

body {
    display: flex;
    min-height: 100vh;
    flex-direction: column;
}
.container {
    flex: 1;    
}

.ft-main {
    padding: 1.25rem 1.875rem;
    display: flex;
    flex-wrap: wrap;
}
.ft-main-item {
    padding: 1.25rem;
    min-width: 12.5rem ;
}

.ft-social {
    padding: 0 1.875rem 1.25rem;
}
.ft-social-list {
    display: flex;
    justify-content: center;
    border-top: 1px #777 solid; 
    padding-top: 1.25rem;
}
.ft-social-list li {
    margin: 0.5rem;
    font-size: 1.25rem;
}
    
</style>