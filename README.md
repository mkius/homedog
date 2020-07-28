# homedog
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <!-- controls -->
  <title>TinDog</title>
  <script src="https://kit.fontawesome.com/c4471abc45.js" crossorigin="anonymous"></script>
  <link href="https://fonts.googleapis.com/css2?family=Alex+Brush&family=Allura&family=Faustina:wght@500&family=Meie+Script&family=Montserrat:ital,wght@1,600&family=Sacramento&family=Ubuntu:ital@1&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/styles.css">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
</head>

<body>

  <section id="title">
    <div class="container-fluid" style="padding-bottom:14%" ;font-family:>


      <!-- Nav Bar -->
      <nav class="navbar navbar-expand-lg navbar-dark ">
        <a style="font-family: 'Montserrat-black', sans-serif;  font-size: 3rem;line-height:1.5;" class="navbar-brand" href="">tintog</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
          <ul class="navbar-nav ml-auto">
            <li class"nav-item">
              <a class="nav-link" href="#footer">contact</a>
            </li>
            <li class"nav-item">
              <a class="nav-link" href="#pricing">pricing</a>
            </li>
            <li class"nav-item">
              <a class="nav-link" href="#cta">download</a>
            </li>

          </ul>

        </div>
      </nav>




      <!-- Title -->

      <div class="row">
        <div class=" download-btn col-lg-6 ">
          <h1 style="font-family: 'Montserrat-black', sans-serif;  font-size: 3rem;line-height:1.5;">Meet new and interesting dogs nearby.</h1>
          <button class="btn btn-dark btn-lg download-button" type="button"><i class="fab fa-apple"></i> Download</button>
          <button class="btn btn-outline-dark btn-lg download-button" type="button"><i class="fab fa-google-play"></i>Download</button>
        </div>

        <div class="col-lg-6">
          <img class="img-item" src="images/iphone6.png" alt="iphone-mockup">
        </div>
      </div>
    </div>
  </section>


  <!-- Features -->

  <section id="features">
    <div class="row">


      <div class="features-box col-lg-4">
        <i class="icon fas fa-check-circle fa-4x"></i>
        <h3> Easy to use.</h3>
        <p>So easy to use, even your dog could do it.</p>

      </div>
      <div class="features-box col-lg-4">
        <i class="icon fas fa-bullseye fa-4x"></i>
        <h3>Elite Clientele</h3>
        <p>We have all the dogs, the greatest dogs.</p>

      </div>
      <div class="features-box col-lg-4">
        <i class="icon fas fa-heart fa-4x"></i>
        <h3>Guaranteed to work.</h3>
        <p>Find the love of your dog's life or your money back.</p>

      </div>
    </div>
  </section>


  <!-- Testimonials -->

  <section id="testimonials">
    <div id="carouselExampleControls" class="carousel slide" data-ride="carousel" data-interval="2000">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <h2 class="h2-test">I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
          <img class="testimonials-image" src="images/dog-img.jpg" alt="dog-profile">
          <em>Pebbles, New York</em>
        </div>
        <div class="carousel-item">

          <h2 class="h2-test">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
          <img class="testimonials-image" src="images/lady-img.jpg" alt="lady-profile">
          <em>Beverly, Illinois</em>
        </div>

      </div>
      <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>

      </a>
      <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>

      </a>
    </div>



  </section>


  <!-- Press -->

  <section id="press">
    <img class="press-id" src="images/techcrunch.png" alt="tc-logo">
    <img class="press-id" src="images/tnw.png" alt="tnw-logo">
    <img class="press-id" src="images/bizinsider.png" alt="biz-insider-logo">
    <img class="press-id" src="images/mashable.png" alt="mashable-logo">

  </section>


  <!-- Pricing -->

  <section id="pricing">



    <h2>A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>
    <div class=" row">
      <div class="pricing-col col-lg-4 col-md-6">
        <div class="card">
          <div class="card-header ">
            <h3>Chihuahua</h3>
          </div>
          <div class="card-body">
            <h2>Free</h2>
            <p>5 Matches Per Day</p>
            <p>10 Messages Per Day</p>
            <p>Unlimited App Usage</p>
            <button class="btn btn-lg btn-outline-secondary btn-block " type="button">Sign Up</button>

          </div>
        </div>
      </div>

      <div class="pricing-col col-lg-4 col-md-6">
        <div class="card">
          <div class="card-header ">
            <h3>Labrador</h3>
          </div>
          <div class="card-body">

            <h2>$49 / mo</h2>
            <p>Unlimited Matches</p>
            <p>Unlimited Messages</p>
            <p>Unlimited App Usage</p>
            <button class="btn btn-lg btn-primary btn-block" type="button">Sign Up</button>

          </div>
        </div>

      </div>
      <div class="pricing-col col-lg-4 ">
        <div class="card">
          <div class="card-header ">
            <h3>Mastiff</h3>
          </div>
          <div class="card-body">

            <h2>$99 / mo</h2>
            <p>Unlimited Matches</p>
            <p>Unlimited Messages</p>
            <p>Unlimited App Usage</p>
            <button class="btn btn-lg btn-primary btn-block" type="button">Sign Up</button>
          </div>
        </div>
      </div>

    </div>
  </section>


  <!-- Call to Action -->

  <section id="cta">

    <h3 class="cta-heading">Find the True Love of Your Dog's Life Today.</h3>
    <button class="btn btn-dark btn-lg download-button" type="button"><i class="fab fa-google-play"></i>Download</button>
    <button class="btn btn-light btn-lg download-button" type="button"><i class="fab fa-google-play"></i>Download</button>


  </section>


  <!-- Footer -->

  <footer id="footer">
    <i class="social-icon fab fa-instagram"></i>
    <i class="social-icon fab fa-twitter"></i>
    <i class="social-icon far fa-envelope"></i>
    <i class="social-icon fab fa-whatsapp"></i>
    <p style="  font-family: 'Montserrat-black', sans-serif;">© Copyright 2020 syed usman</p>

  </footer>


</body>

</html>
#title{
  background-color: #ff4c68;
  color: #fff;
}
.container-fluid{
  padding:3% 6%;
  padding-bottom:100;
}
h1 {
font-family: 'Montserrat-black', sans-serif;
  font-size: 3rem;
  line-height:1.5;
}
h3{
  font-family: 'Montserrat-black', sans-serif;
}
.h2-test{
  font-family: "Montserrat-Bold";
    font-size: 3rem;
    line-height:1.5;
}
p{
  color: #8f8f8f;
}
body{
  font-family: 'Montserrat', sans-serif;
}
/* navbar brand */
.navbar{
  padding: 0 0 4.5rem;
}
.navbar-brand{
  font-family: unbuntu;
  font-weight: bold;
  font-size: 4.5rem;
}
.nav-item{
  padding: 0 18px;
}
/* download button */
.download-button{
  padding: 5% 3% 5% 0;
}
/* image transform */
.img-item{
  width:40%;
  transform: rotate(20deg);
height: 470px;
position: absolute;
}
#features{
  padding:10%;
  background-color: #fff;
  position: relative;


}
.features-box{
  text-align: center;

}
.icon{
  color: #ef8172;
  margin-bottom: 1rem;
}
.icon:hover{
  color: #ff4c68;
}
#testimonials{

text-align: center;
background-color: #ef8172;
color: #fff;
}
.carousel-item{
  padding: 5% 15%;
}
.testimonials-image{
  width: 20%;
  border-radius: 100%;
  margin: 5%
}
#press{
  background-color: #ef8172;
  text-align: center;
  padding-bottom: 5%
}
.press-id{
  width: 12%;
margin: 5% 3% 5%;
}
#pricing{
  padding: 100px;
  text-align: center;
}
.pricing-col{
  padding: 3% 2%;
}
#cta{
 background-color: #ef8172;
 color: #fff;
 padding: 10% 15%;
 text-align: center;
}
.cta-heading{
  font-family: 'Montserrat-black', sans-serif;
    font-size: 3rem;
    line-height:1.5;
}
#footer{
  padding: 2% 10%;
  text-align: center;
}
.social-icon{
  margin: 20px 10px;
}
@media(max-width:1028px){
  #title{
    text-align: center;
  }
.img-item{
  position: static;
  transform: rotate(0);
  width: 60%;
  height: auto;
}
.download-btn{
  margin: 40px 30px;
}
}
