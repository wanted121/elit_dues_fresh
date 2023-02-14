<template>
    
    <section id="title">
    <div class="container-fluid">
    <nav class="navbar navbar-expand-lg navbar-dark">
      <a class="navbar-brand" href="#">Elit Deus</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <!--
          <li class="nav-item active">
            <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
          </li>
          -->
          <li class="nav-item">
            <a class="nav-link" @click="scroll('footer')">Contect</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" @click="scroll('pricing')" >Pricing</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" @click="scroll('cta')">Download</a>
          </li>
          <!--
          <li class="nav-item">
            <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
          </li>-->
        </ul>
      </div>
    </nav>
    <!-- Title -->

    <div class="row">
      <div class="col-lg-6 col-sm-12">
        <h1>We are Professional Developer.</h1>
        <h2>We can build websites & mobile application for you.</h2>
        <!--<button type="button" class="btn btn-dark btn-lg download_botton"><i class="fab fa-apple"></i>  Download</button>
        <button type="button" class="btn btn-outline-light btn-lg download_botton"><i class="fab fa-google-play"></i>  Download</button>-->
      </div>

      <div class="col-lg-6 col-m-12">
        <img class="iphone6" src="images/i1.png" alt="iphone-mockup">
      </div>
    </div>
    </div>
  </section>

  <!-- Features -->

  <section id="features">
    <div class="row">
      <div class="col-lg-4 features1">
        <i class="icon fas fa-check-circle fa-4x"></i>
        <h3>Easy Service.</h3>
        <p>We provide fast & easy service.</p>
      </div>
      <div class="col-lg-4 features1">
        <i class="icon fas fa-bullseye fa-4x"></i>
        <h3>Core work</h3>
        <p>We provide core functionality.</p>
      </div>
      <div class="col-lg-4 features1">
        <i class="icon fas fa-heart fa-4x"></i>
        <h3>Good Service.</h3>
        <p>We provide good service within time.</p>
      </div>
    </div>
  </section>

  <!-- Testimonials -->

  <section id="testimonials">
  
    <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img class="testimonioimmg" src="images/res1.png" alt="dog-profile">
          <em>Latest Templates</em>
        </div>
        <div class="carousel-item">
          <img class="testimonioimmg" src="images/res2.png" alt="lady-profile">
          <em>Latest Templates</em>           
        </div>
        <div class="carousel-item">
          <img class="testimonioimmg" src="images/res3.png" alt="lady-profile">
          <em>Latest Templates</em>           
        </div>
        <div class="carousel-item">
          <img class="testimonioimmg" src="images/res4.png" alt="lady-profile">
          <em>Latest Templates</em>           
        </div>
        <div class="carousel-item">
          <img class="testimonioimmg" src="images/res5.png" alt="lady-profile">
          <em>Latest Templates</em>           
        </div>

      </div>
      <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>

  </section>

  <!-- Press -->

  <section id="press">
    <img class="pres-logo" src="images/tnw.png" alt="tnw-logo">
    <img class="pres-logo" src="images/TechCrunch.png" alt="tc-logo">
    <img class="pres-logo" src="images/bizinsider.png" alt="biz-insider-logo">
    <img class="pres-logo" src="images/mashable.png" alt="mashable-logo">
  </section>

  <!-- Pricing -->

  <section id="pricing">

    <h2>A Plan for Every Developing website and mobile web view</h2>
    <p>Simple and affordable price plans for you and your dog.</p>

<div class="row">
  <div class=" pricing-col col-lg-4 col-md-6">
    <div class="card">
      <div class="card-header">
        <h3>Chihuahua</h3>
      </div>
      <div class="card-body">
        <h2>Free</h2>
        <p>5 Matches Per Day</p>
        <p>10 Messages Per Day</p>
        <p>Unlimited App Usage</p>
        <button class="btn btn-lg btn-block btn-outline-dark" type="button">Sign Up</button>
      </div>
  </div>
</div>
  <div class="pricing-col col-lg-4 col-md-6">
    <div class="card">
      <div class="card-header">
        <h3>Labrador</h3>
      </div>  
      <div class="card-body">
        <h2>$49 / mo</h2>
        <p>Unlimited Matches</p>
        <p>Unlimited Messages</p>
        <p>Unlimited App Usage</p>
        <button class="btn btn-lg btn-block btn-dark" type="button">Sign Up</button>
      </div>
    </div>  
  </div>
  <div class="pricing-col col-lg-4">
    <div class="card">
      <div class="card-header">
        <h3>Mastiff</h3>
      </div>
      <div class="card-body">
        <h2>$99 / mo</h2>
        <p>Pirority Listing</p>
        <p>Unlimited Matches</p>
        <p>Unlimited Messages</p>
        <p>Unlimited App Usage</p>
        <button class="btn btn-lg btn-block btn-dark" type="button">Sign Up</button>
      </div>
    </div>
  </div>
</div>
  
  </section>
  <!-- Call to Action -->
  <section id="cta">
    <h2 class="cat_text">Find the True Love of Your Dog's Life Today.</h2>
    <button type="button" class="btn btn-dark btn-lg download_botton"><i class="fab fa-apple"></i>  Download</button>
    <button type="button" class="btn btn-outline-light btn-lg download_botton"><i class="fab fa-google-play"></i>  Download</button>

  </section>


  <!-- Footer */-->

  <footer id="footer">
    <i class=" fot_icon fab fa-facebook-f fa-2x"></i>
    <i class="fot_icon fab fa-twitter fa-2x"></i>
    <a href="https://www.instagram.com/elitdeus/"> <i class="fot_icon fab fa-instagram fa-2x"></i></a>
    <i class="fot_icon fas fa-envelope-square fa-2x"></i>
    <p>@copyright elit_deus, 2023</p>

  </footer>


  </template>
  
  <script>
  
  export default {
    name: 'Header',
  
    data: () => {
  },
  methods: {
    scroll(refName) {
        const element = document.getElementById(refName);
        element.scrollIntoView({ behavior: "smooth" });
  },
},
}

  </script>

  <style scoped>

/* Style the header with a grey background and some padding */
.header {
  overflow: hidden;
  background-color: black;
  padding: 20px 10px;
}

/* Style the header links */
.header a {
  float: left;
  color: white;
  text-align: center;
  padding: 12px;
  text-decoration: none;
  font-size: 18px;
  line-height: 25px;
  border-radius: 4px;
}

/* Style the logo link (notice that we set the same value of line-height and font-size to prevent the header to increase when the font gets bigger */
.header a.logo {
  font-size: 25px;
  font-weight: bold;
}

/* Change the background color on mouse-over */
.header a:hover {
  background-color: #ddd;
  color: black;
}

/* Style the active/current link*/
.header a.active {
  background-color: dodgerblue;
  color: white;
}

/* Float the link section to the right */
.header-right {
  float: right;
}

/* Add media queries for responsiveness - when the screen is 500px wide or less, stack the links on top of each other */
@media screen and (max-width: 500px) {
  .header a {
    float: none;
    display: block;
    text-align: left;
  }
  .header-right {
    float: none;
  }
}

</style>
  