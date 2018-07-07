# photoX
Photography website made with jquery and bootstrap.
html files and css
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="icon" href="images/title-img.png">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css" integrity="sha384-9gVQ4dYFwwWSjIDZnLEWnxCjeSWFphJiwGPXr1jddIhOegiu1FwO5qRGvFXOdJZ4" crossorigin="anonymous">
  <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
  <title>PhotoX</title>
</head>
<body>

  <!--header-->
  <header>

<!--Navbar-->
<nav class="navbar navbar-expand-lg fixed-top nav-menu">
  <a href="#" class="navbar-brand text-light text-uppercase"><span class="h2 font-weight-bold">photo</span><span class="h1">X</span></a>
<button class="navbar-toggler nav-button" type="button" data-toggle="collapse" data-target="#myNavbar">
  <div class="bg-light line1"></div>
  <div class="bg-light line2"></div>
  <div class="bg-light line3"></div>
</button>
<div class="collapse navbar-collapse justify-content-end text-uppercase font-weight-bold" id="myNavbar">
  <ul class="navbar-nav">
    <li class="nav-item">
      <a href="#" class="nav-link m-2 menu-item nav-active">Home</a>
    </li>
    <li class="nav-item">
        <a href="#" class="nav-link m-2 menu-item">Mission</a>
      </li>
      <li class="nav-item">
          <a href="#" class="nav-link m-2 menu-item">Collection</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link m-2 menu-item">Gallery</a>
          </li>
          <li class="nav-item">
              <a href="#" class="nav-link m-2 menu-item">Customers</a>
            </li>
            <li class="nav-item">
                <a href="#" class="nav-link m-2 menu-item">Pricing</a>
              </li>
              <li class="nav-item">
                  <a href="#" class="nav-link m-2 menu-item">Contact</a>
                </li>
  </ul>
</div>
</nav>

<!--End of Navbar-->

<!--Banner-->
<div class="banner text-light text-md-right text-center">
  <h1 class="display-4 banner-heading">Welcome to <span>photo</span><span class="display-3">X</span></h1>
  <p class="lead banner-par">Lorem ipsum dolor sit amet consectetur adipisicing.</p>
</div>

<!--End of banner-->
    <!--End of header-->

  </header>

  <!--Mission-->

  <section class="p-5 mission">
   <div class="container-fluid">
     <!--title-->
    <div class="row text-white text-center">
      <div class="col m-4">
        <h1 class="display-4 mb-4">
          Our Mission
        </h1>
        <div class="underline mb-4"></div>
          <p class="lead">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis 
            corrupti delectus suscipit, perspiciatis molestias maiores?
          </p>
        
      </div>
    </div>
     <!--end of title-->
     <div class="row my-5">
       <div class="col-md-4 text-center">
        <i class="fa fa-cogs fa-5x text-danger mb-4"></i>
        <h1 class="text-white mb-3">
          Creativity
        </h1>
        <p class="text-muted">
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Inventore, accusantium? Dolore
           neque quam aut illum aliquam molestiae recusandae labore! Unde.
        </p>
       </div>
       <div class="col-md-4 text-center">
          <i class="fa fa-thumbs-up fa-5x text-danger mb-4"></i>
          <h1 class="text-white mb-3">
            Quallity
          </h1>
          <p class="text-muted">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Inventore, accusantium? Dolore
             neque quam aut illum aliquam molestiae recusandae labore! Unde.
          </p>
        </div>
        <div class="col-md-4 text-center">
            <i class="fa fa-handshake-o fa-5x text-danger mb-4"></i>
            <h1 class="text-white mb-3">
              Experience
            </h1>
            <p class="text-muted">
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Inventore, accusantium? Dolore
               neque quam aut illum aliquam molestiae recusandae labore! Unde.
            </p>
          </div>
      </div>
   </div>
   <div class="container">
     <div class="row align-items-center">
       <div class="col-lg-5 text-center">
        <img src="images/camera.png" width="350" class="img-fluid camera-img">
       </div>
       <div class="col-lg-7 text-white text-lg-right text-center mission-text">
        <h1>We know what we do</h1>
        <p class="lead">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ea eos quis, facere neque voluptatem non commodi odio
           totam vero quia recusandae nemo earum ducimus officiis laudantium alias iste unde adipisci.</p>
       </div>
     </div>
   </div>
  </section>

  <!--End of Mission-->

  <!--Collection-->
<section class="bg-secondary py-5">
  <div class="container-fluid">
    <!--title-->
    <div class="row text-white text-center">
      <div class="col m-4">
        <h1 class="display-4 mb-4">
          Collection
        </h1>
        <div class="underline mb-4"></div>
          <p class="lead">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis 
            corrupti delectus suscipit, perspiciatis molestias maiores?
          </p>
        
      </div>
    </div>
     <!--end of title-->
  </div>
  <div class="row">
    <div class="col-lg-4 col-sm-5 my-5">
      <div class="card border-0 card-shadow">
        <img src="images/wedding.jpeg" class="card-img">
        <div class="card-img-overlay">
          <h5 class="text-white text-uppercase font-weight-bold p-2 heading">
            Wedding Photography
          </h5>
        </div>
      </div>
    </div>
    <div class="col-lg-4 col-sm-5 my-5">
      <div class="card border-0 card-shadow">
        <img src="images/party.jpeg" class="card-img">
        <div class="card-img-overlay">
          <h5 class="text-white text-uppercase font-weight-bold p-2 heading">
            Party Photography
          </h5>
        </div>
      </div>
    </div>
    <div class="col-lg-4 col-sm-5 my-5">
      <div class="card border-0 card-shadow">
        <img src="images/business.jpeg" class="card-img">
        <div class="card-img-overlay">
          <h5 class="text-white text-uppercase font-weight-bold p-2 heading">
            Business Photography
          </h5>
        </div>
      </div>
    </div>
    <div class="col-lg-4 col-sm-5 my-5">
      <div class="card border-0 card-shadow">
        <img src="images/fashion.jpeg" class="card-img">
        <div class="card-img-overlay">
          <h5 class="text-white text-uppercase font-weight-bold p-2 heading">
            Fashion Photography
          </h5>
        </div>
      </div>
    </div>
    <div class="col-lg-4 col-sm-5 my-5">
      <div class="card border-0 card-shadow">
        <img src="images/family.jpeg" class="card-img">
        <div class="card-img-overlay">
          <h5 class="text-white text-uppercase font-weight-bold p-2 heading">
            Family Photography
          </h5>
        </div>
      </div>
    </div>
    <div class="col-lg-4 col-sm-5 my-5">
      <div class="card border-0 card-shadow">
        <img src="images/nature.jpeg" class="card-img">
        <div class="card-img-overlay">
          <h5 class="text-white text-uppercase font-weight-bold p-2 heading">
            Nature Photography
          </h5>
        </div>
      </div>
    </div>
  </div>
</section>
  <!--End of collection-->

  <!--Gallery-->
<section class="py-5">
  <div class="container-fluid">
    <!--title-->
    <div class="row text-muted text-center">
      <div class="col m-4">
        <h1 class="display-4 mb-4">
          Gallery
        </h1>
        <div class="underline-dark mb-4"></div>
          <p class="lead">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis 
            corrupti delectus suscipit, perspiciatis molestias maiores?
          </p>        
      </div>
    </div>
     <!--end of title-->
     <ul class="list-inline text-center text-uppercase font-weight-bold my-4">
       <li class="list-inline-item gallery-list-item active-item" data-filter="all">
        All<span class="mx-md-5 mx-3 text-muted">/</span>
       </li>
       <li class="list-inline-item gallery-list-item active-item" data-filter="new">
        New<span class="text-muted mx-md-5 mx-3">/</span>
       </li>
       <li class="list-inline-item gallery-list-item" data-filter="free">
        Free<span class="text-muted mx-md-5 mx-3">/</span>
       </li>
       <li class="list-inline-item gallery-list-item" data-filter="pro">
        Pro<span class="text-muted mx-md-5 mx-3">/</span>
       </li>
     </ul>
     <div class="container-fluid">
       <div class="d-flex flex-wrap justify-content-center">
         <div class="filter new">
           <img src="images/img1.jpeg" width="300">
         </div>
         <div class="filter free">
          <img src="images/img2.jpeg" width="300">
        </div>
        <div class="filter pro">
          <img src="images/img3.jpeg" width="300">
        </div>
        <div class="filter new">
          <img src="images/img4.jpeg" width="300">
        </div>
        <div class="filter free">
          <img src="images/img5.jpeg" width="300">
        </div>
        <div class="filter pro">
          <img src="images/img6.jpeg" width="300">
        </div>
        <div class="filter new">
          <img src="images/img7.jpeg" width="300">
        </div>
        <div class="filter free">
          <img src="images/img8.jpeg" width="300">
        </div>
        <div class="filter pro">
          <img src="images/img9.jpeg" width="300">
        </div>
        <div class="filter new">
          <img src="images/img10.jpeg" width="300">
        </div>
        <div class="filter free">
          <img src="images/img11.jpeg" width="300">
        </div>
        <div class="filter pro">
          <img src="images/img12.jpeg" width="300">
        </div>
        <div class="filter new">
          <img src="images/img13.jpeg" width="300">
        </div>
        <div class="filter">
          <img src="images/img14.jpeg" width="300">
        </div>
        <div class="filter">
          <img src="images/img15.jpeg" width="300">
        </div>
        <div class="filter">
          <img src="images/img16.jpeg" width="300">
        </div>
       </div>
     </div>
  </div>
</section>

  <!--End of gallery-->

  <!--Customer-->
<section class="p-5 customers">
  <div class="container-fluid">
    <!--title-->
    <div class="row text-white text-center">
      <div class="col m-4">
        <h1 class="display-4 mb-4">
          Happy Customer
        </h1>
        <div class="underline mb-4"></div>
          <p class="lead">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis 
            corrupti delectus suscipit, perspiciatis molestias maiores?
          </p>
        
      </div>
    </div>
     <!--end of title-->
     <div class="row">
       <div class="col-md-6 mx-auto">
        <div class="carousel slide" data-ride="carousel" id="customer-carousel">
          <ol class="carousel-indicators">
            <li data-target="customer-carousel" data-slide-to="0" class="active"></li>
            <li data-target="customer-carousel" data-slide-to="1"></li>
            <li data-target="customer-carousel" data-slide-to="2"></li>
          </ol>
          <div class="carousel-inner">
            <div class="carousel-item active text-center">
              <img src="images/customer1.jpeg" class="img-fluid rounded-circle m-5" width="150">
<blockquote class="blockquote text-white">
  <p class="mb-5">
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat 
    itaque magnam reprehenderit labore, corrupti facilis!
  </p>
</blockquote>
<h5 class="text-light text-uppercase font-weight-bold mb-3">Monica</h5>
<ul class="list-inline mb-5">
  <li class="list-inline-item">
    <i class="fa fa-star text-warning"></i>
  </li>
  <li class="list-inline-item">
      <i class="fa fa-star text-warning"></i>
    </li>
    <li class="list-inline-item">
        <i class="fa fa-star text-warning"></i>
      </li>
      <li class="list-inline-item">
          <i class="fa fa-star text-warning"></i>
        </li>
        <li class="list-inline-item">
            <i class="fa fa-star text-warning"></i>
          </li>
      </ul>
    </div>
    <div class="carousel-item text-center">
        <img src="images/customer2.jpeg" class="img-fluid rounded-circle m-5" width="150">
<blockquote class="blockquote text-white">
<p class="mb-5">
Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat 
itaque magnam reprehenderit labore, corrupti facilis!
</p>
</blockquote>
<h5 class="text-light text-uppercase font-weight-bold mb-3">Jonathan</h5>
<ul class="list-inline mb-5">
<li class="list-inline-item">
<i class="fa fa-star text-warning"></i>
</li>
<li class="list-inline-item">
<i class="fa fa-star text-warning"></i>
</li>
<li class="list-inline-item">
  <i class="fa fa-star text-warning"></i>
</li>
<li class="list-inline-item">
    <i class="fa fa-star text-warning"></i>
  </li>
  <li class="list-inline-item">
      <i class="fa fa-star text-warning"></i>
    </li>
</ul>
      </div>
      <div class="carousel-item text-center">
          <img src="images/customer3.jpeg" class="img-fluid rounded-circle m-5" width="150">
<blockquote class="blockquote text-white">
<p class="mb-5">
Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat 
itaque magnam reprehenderit labore, corrupti facilis!
</p>
</blockquote>
<h5 class="text-light text-uppercase font-weight-bold mb-3">Helen</h5>
<ul class="list-inline mb-5">
<li class="list-inline-item">
<i class="fa fa-star text-warning"></i>
</li>
<li class="list-inline-item">
  <i class="fa fa-star text-warning"></i>
</li>
<li class="list-inline-item">
    <i class="fa fa-star text-warning"></i>
  </li>
  <li class="list-inline-item">
      <i class="fa fa-star text-warning"></i>
    </li>
    <li class="list-inline-item">
        <i class="fa fa-star text-warning"></i>
      </li>
</ul>
        </div>
          </div>
        </div>
       </div>
     </div>
  </div>
</section>

  <!--End customer-->

  <!--Pricing-->
<section class="bg-light text-center p-5">
  <!--title-->
  <div class="row text-muted text-center">
      <div class="col m-4">
        <h1 class="display-4 mb-4">
          Join Us
        </h1>
        <div class="underline-dark mb-4"></div>
          <p class="lead">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis 
            corrupti delectus suscipit, perspiciatis molestias maiores?
          </p>        
      </div>
    </div>
     <!--end of title-->
     <div class="row align-items-center">
       <div class="col-lg-4">
         <div class="card card-1 text-light py-4 my-4 mx-auto">
           <div class="card-body">
             <h5 class="text-uppercase font-weight-bold mb-5">Monthly Membership</h5>
             <h1 class="display-4"><i class="fa fa-dollar-sign"></i>19</h1>
             <ul class="list-unstyled">
               <li class="font-weight-bold py-3 card-list-item">Photoshop</li>
               <li class="font-weight-bold py-3 card-list-item">After Effects</li>
               <li class="font-weight-bold py-3 card-list-item">Graphic</li>
               <li class="font-weight-bold py-3 card-list-item border-0">Video Montage</li>
             </ul>
             <a href="#" class="btn p-2 text-uppercase font-weight-bold price-card-button text-light">sign-up</a>
           </div>
         </div>
       </div>
       <div class="col-lg-4">
          <div class="card card-2 text-light py-4 my-4 mx-auto">
            <div class="card-body">
              <h5 class="text-uppercase font-weight-bold mb-5">Unlimited Access</h5>
              <h1 class="display-4"><i class="fa fa-dollar-sign"></i>499</h1>
              <ul class="list-unstyled">
                <li class="font-weight-bold py-3 card-list-item">Photoshop</li>
                <li class="font-weight-bold py-3 card-list-item">After Effects</li>
                <li class="font-weight-bold py-3 card-list-item">Graphic</li>
                <li class="font-weight-bold py-3 card-list-item border-0">Video Montage</li>
                <li class="font-weight-bold py-3 card-list-item border-0">Clip making</li>
              </ul>
              <a href="#" class="btn p-2 text-uppercase font-weight-bold price-card-button text-light">sign-up</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4">
            <div class="card card-3 text-light py-4 my-4 mx-auto">
              <div class="card-body">
                <h5 class="text-uppercase font-weight-bold mb-5">Annual Membership</h5>
                <h1 class="display-4"><i class="fa fa-dollar-sign"></i>199</h1>
                <ul class="list-unstyled">
                  <li class="font-weight-bold py-3 card-list-item">Photoshop</li>
                  <li class="font-weight-bold py-3 card-list-item">After Effects</li>
                  <li class="font-weight-bold py-3 card-list-item">Graphic</li>
                  <li class="font-weight-bold py-3 card-list-item border-0">Video Montage</li>
                </ul>
                <a href="#" class="btn p-2 text-uppercase font-weight-bold price-card-button text-light">sign-up</a>
              </div>
            </div>
          </div>
     </div>
     <div class="my-5">
      <h2 class="text-muted mb-4">
        Thanks for being with Us!
      </h2>
      <i class="fa fa-coffee fa-3x"></i>
     </div>
     
</section>

  <!--End Pricing-->

  <!--Contact us-->
<section class="contact -5">
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-5 pb-4">
        <h3 class="display-4 mb-5 text-white">
          Get in Touch
        </h3>
        <form action="" class="contact-form">
          <div class="form-group py-4">
            <input type="text" class="form-control my-2 p-2 input" placeholder="Name">
            <label for="name" class="label">Name</label>
          </div>
          <div class="form-group py-4">
              <input type="email" class="form-control my-2 p-2 input" placeholder="Email Address">
              <label for="name" class="label">Name</label>
            </div>
            <div class="form-group py-4 my-4">
              <input type="checkbox" checked>
              <label for="check" class="text-white">Send Announcements</label>
            </div>
            <button type="submit" class="btn btn-block p-2 font-weight-bold text-uppercase submit-button">Subscribe</button>
        </form>
      </div>
    </div>
  </div>
</section>

  <!--End contact-->

  <!--Footer-->
<section class="bg-dark px-5">
  <div class="container-fluid">
    <div class="row text-light py-4">
      <div class="col-lg-4 col-sm-6">
        <h5 class="pb-3">
          About Us
        </h5>
        <p class="small">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis, autem? 
          Vitae, fugit libero aut doloribus non veritatis itaque incidunt voluptatum?</p>
      </div>
      <div class="col-lg-2 col-sm-6">
        <h5 class="pb-3">Visit Us</h5>
        <ul class="list-unstyled">
          <li>
            <a href="#" class="footer-link">Home</a>
          </li>
          <li>
            <a href="#" class="footer-link">Mission</a>
          </li>
          <li>
            <a href="#" class="footer-link">Collection</a>
          </li>
          <li>
            <a href="#" class="footer-link">Gallery</a>
          </li>
          <li>
            <a href="#" class="footer-link">Customers</a>
          </li>
          <li>
            <a href="#" class="footer-link">Pricing</a>
          </li>
          <li>
            <a href="#" class="footer-link">Contact</a>
          </li>
        </ul>
        </div>
        <div class="col-lg-2 col-sm-6">
          <h5 class="pb-3">Need Help?</h5>
          <ul class="list-unstyled">
            <li>
              <a href="#" class="footer-link text-uppercase">
                Customer Service
              </a>
            </li>
            <li>
              <a href="#" class="footer-link text-uppercase">
                Online Chat
              </a>
              <li>
                <a href="#" class="footer-link text-uppercase">
                  Support
                </a>
                <li>
                  <a href="#" class="text-info">
                    photox@email.com
                  </a>
          </ul>
          </div>
          <div class="col-lg-4 col-sm-6">
            <h5 class="pb-3">Stay Connected</h5>
            <p class="small">Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae minus beatae
               similique sapiente quos consequuntur quo temporibus fuga sed consectetur!</p>
            <form>
              <div class="input-group">
                <input type="text" class="form-control" placeholder="Email address">
                <div class="input-group-append">
                  <button class="btn bg-danger text-white text-uppercase font-weight-bold" type="button">Sign Up</button>
                </div>
              </div>
            </form class="mb-3">
            <ul class="list-inline pt-4">
              <li class="list-inline-item">
                <i class="fa fa-facebook-square fa-2x text-primary"></i>
              </li>
              <li class="list-inline-item">
                  <i class="fa fa-google-plus fa-2x text-danger"></i>
                </li>
                <li class="list-inline-item">
                    <i class="fa fa-instagram fa-2x text-danger"></i>
                  </li>
                  <li class="list-inline-item">
                      <i class="fa fa-twitter fa-2x text-primary"></i>
                    </li>
                    <li class="list-inline-item">
                        <i class="fa fa-youtube fa-2x text-primary"></i>
                      </li>
                  </ul>
              </div>
          </div>
          <div class="row">
            <div class="col text-center text-light border-top pt-3">
              <p>&copy; 2018 Copyright, All rights reserved</p>
            </div>
          </div>
  </div>
</section>
  <!--End of footer-->

  
  <script
  src="https://code.jquery.com/jquery-3.3.1.js"
  integrity="sha256-2Kok7MbOyxpgUVvAk/HJ2jigOSYS2auK4Pfzbm7uH60="
  crossorigin="anonymous"></script>
  <script src="http://code.jquery.com/jquery-3.3.1.js" integrity="sha256-2Kok7MbOyxpgUVvAk/HJ2jigOSYS2auK4Pfzbm7uH60="
  crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.0/umd/popper.min.js" integrity="sha384-cs/chFZiN24E4KMATLdqdvsezGxaGsi4hLGOzlXwp5UZB1LY//20VyM2taTB4QvJ" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/js/bootstrap.min.js" integrity="sha384-uefMccjFJAIv6A+rW+L4AHf99KvxDjWSu1z9VI8SKNVmz4sk7buKt/6v9KI65qnm" crossorigin="anonymous"></script>
  <script src="script.js"></script>
</body>
</html>















































