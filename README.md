# WEB-DEV
Web development group work

<!DOCTYPE html>
<html lang="en">
<head>
	<title>FB Store</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
	<script src="https://use.fontawesome.com/releases/v5.6.1/js/all.js"></script>
	
	<link rel="stylesheet" href="webstyle.css">
</head>

<body>

<div id="home">     <!--- class="container-fluid" --->
<nav class="navbar navbar-expand-md navbar-dark bg-dark fixed-top">
	<a class="navbar-brand" href="#home"><img src="img/Logo.png"></a>
	<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#mynavbarmenu">
		<span class="navbar-toggler-icon"></span>
	</button>

<!-- Navbar links/content -->
	<div class="collapse navbar-collapse" id="mynavbarmenu">
	  <ul class="navbar-nav mx-auto"> <!--add/ ml-auto /to put contant right-->
		<li class="nav-item">
		  <a class="nav-link" href="#home">Home</a>
	    </li>
		<li class="nav-item">
		  <a class="nav-link" href="#newReleases">New Releases</a>
		</li>
		<li class="nav-item">
		  <a class="nav-link" href="#men">Men</a>
		</li>
		<li class="nav-item">
		  <a class="nav-link" href="#women">Women</a>
		</li>
		<li class="nav-item">
		  <a class="nav-link" href="#kids">Kids</a>
		</li>
		<li class="nav-item">
		  <a class="nav-link" href="#about">About</a>
		</li>
		<li class="nav-item">
		  <a class="nav-link" href="#contact">Contact</a>
		</li>
	  </ul>
	</div>
</nav>
</div>

<!--- Image Slider indicators--->
<div id="mySlides" class="carousel slide" data-ride="carousel">  <!-- add--  data-interval="7000" --for time image spend on the screen  -->
	<ul class="carousel-indicators">
	  <li data-target="#mySlides" data-slide-to="0" class="active"></li>
	  <li data-target="#mySlides" data-slide-to="1"></li>
	  <li data-target="#mySlides" data-slide-to="3"></li>
	</ul>
	
<!--- Slideshow --->
	<div class="carousel-inner">
	<!--- Slide 1 --->
		<div class="carousel-item active">
			<img src="img/NIKE_GLOBAL_Shoot_Mercurial_Groupshot.jpg">
			<div class="carousel-caption">
			  <h1 class="disply-1">Get Kicking and running while looking stunning</h1>
				<a href="#explore" class="btn btn-outline-light btn-sm">Explore</a>
			</div>
		</div>
	<!--- Slide 2 --->
		<div class="carousel-item">
			<img src="img/a-mercurialSuperfly360.jpg">
			<div class="carousel-caption">
			  <h1 class="display-1">Some dream about goals – we make them</h1>
			  <h5><strong>with the new MercurialSuperfly360</strong></h5>
				<a href="#cleats" class="btn btn-outline-light btn-sm">Shop Now</a>
			</div>
		</div>
	<!--- Slide 3 --->
		<div class="carousel-item">
		  <div class="row">
			<div class="col">
			  <img src="img/fcb.jpg" alt="FC Barcelona Home Kit">
			  <div class="carousel-caption">
			    <h6>We created it so play it<br/>FC Barcelona 2019 Home Kit</h6>
			    <a href="#barcalink" class="btn btn-warning btn-sm">Shop now</a>
			  </div>
			</div>
			<div class="col">
			  <img src="img/man U home.jpg" alt="Man United Home Kit">
			  <div class="carousel-caption">
				<h6>Taking you closer to the pitch<br/>with this Manchester United 2019 Home Kit</h6>
				<a href="#unitedlink" class="btn btn-warning btn-sm">Shop now</a>
			  </div>
			</div>
		  </div>
		</div>
		
	<!-- Left and right controls -->
		<a class="carousel-control-prev" href="#mySlides" data-slide="prev">
		  <span class="carousel-control-prev-icon"></span>
		</a>
		<a class="carousel-control-next" href="#mySlides" data-slide="next">
		  <span class="carousel-control-next-icon"></span>
		</a>
	</div>
	
	<!-- About Section -->
<div id="about">

<div class="jumbotron container-fluid">
  <div class="col-12 text-center">
	<h3 class="heading">About Us</h3>
	<div class="heading-underline"></div>
	  <p class="lead">Welcome<br> To Football World At football world, <q>we take you closer to the pitch.</q> By<br/>
		using our products while making you experience<br/>the game like your favourite 
		soccer stars.
	  </p>
	  <a href="#joinlink" class="btn btn-outline-light btn-md">More Info</a>
	</div>
  </div>
</div>
</div>

<!-- New Releases Section -->
<div id="newReleases">
  <div class="col-12 text-center">
	<h3 class="heading">New Releases & Top Trends</h3>
	<div class="heading-underline"></div>
  </div>
	
<div class="row padding">

	<div class="col-md-6">
		<div class="card text-center">
			<img class="card-img-top" src="img/newR/Chelsea-home-kit-main-2019-2020.jpg">
			<div class="card-body">
				<h4>Chelsea</h4>
				<p>The 2019/2020 Home kit<br/>Photo shoot with the first team.</p>
				<a href="#anotherpage1" class="btn btn-primary btn-lg">Pre-Order</a>
			</div>
		</div>
	</div>
	<div class="col-md-6">
		<div class="card text-center">
			<img class="card-img-top" src="img/newR/Liverpool-fc-2019-20-home-kit-red-stripes-new-balance.jpg">
			<div class="card-body">
				<h4>Liverpool</h4>
				<p>The 2019/2020 Home kit<br/>Photo shoot with the first team.</p>
				<a href="#anotherpage2" class="btn btn-primary btn-lg">Pre-Order</a>
			</div>
		</div>
	</div>
	<div class="col-md-6">
		<div class="card text-center">
			<img class="card-img-top" src="img/women/Nike 'Victory' 2019 Women's World Cup Boots Pack Launched.jpg">
			<div class="card-body">
				<h4>Nike Women</h4>
				<p>All New<br/>Nike 'Victory' 2019 Women's World Cup Boots Pack Launched</p>
				<a href="#anotherpage3" class="btn btn-primary btn-lg">Pre-Order</a>
			</div>
		</div>
	</div>
	<div class="col-md-6">
		<div class="card text-center">
			<img class="card-img-top" src="img/newR/addidas Predator 19+SG-Active Red_Solor Red-Core Black.jpg" height="258px";>
			<div class="card-body">
				<h4>Addidas</h4>
				<p>All new<br/>Addidas Predator 19+SG-Active Red_Solor Red-Core Black</p>
				<a href="#anotherpage4" class="btn btn-primary btn-lg">Order Now</a>
			</div>
		</div>
	</div>
</div>
</div>


<!--- Men Section --->
<div id="men">
  <div class="col-12 text-center">
	<h3 class="heading">Men</h3>
	<div class="heading-underline"></div>
  </div>

<div class="row padding">

	<div class="col-md-3">
		<div class="card text-center">
			<a href="#1"><img class="card-img-top" src="img/men/adidas-predator-18-fg-core-blackwhitered.jpg"></a>
			<div class="card-body">
				<h3>Adidas Predator 18 FG</h3>
				<p>Ksh 15,000</p>
			</div>
		 </div>
	</div>
		
	<div class="col-md-3">
		<div class="card text-center">
			<a href="#2"><img class="card-img-top" src="img/men/Nike Hypervenom Phade FG.jpg"></a>
			<div class="card-body">
				<h3>Nike Hypervenom Phade FG</h3>
				<p>Ksh 10,000</p>
			</div>
		</div>
	</div>
	<div class="col-md-3">
		<div class="card text-center">
			<a href="#3"><img class="card-img-top" src="img/men/nike_mercurial_superfly_360_elite_se_fg_lvl_up__pure_platinum_white_black_3.jpg" height="150px"></a>
			<div class="card-body">
				<h3>Nike Mercurial Superfly 360 Elite Se FG</h3>
				<p>Ksh 10,000</p>
			</div>
		</div>
	</div>
	<div class="col-md-3">
		<div class="card text-center">
			<a href="#4"><img class="card-img-top" src="img/men/addidas Predator.jpg" height="150px"></a>
			<div class="card-body">
				<h3>Addidas Predator</h3>
				<p>Ksh 10,000</p>
			</div>
		</div>
	</div>
</div>

<!--- Women section --->
<div class="container-fluid justify-content-center">
<div id="women">
  <div class="col-12 text-center">
	<h3 class="heading">Women</h3>
	<div class="heading-underline"></div>
  </div>
  <img src="img/women/Barca Womens.jpg">
	<a href="#womenpage" class="btn btn-primary btn-lg">Explore</a>
</div>
</div>

<!--- Kids Section --->
<div class="container-fluid justify-content-center">
<div id="kids">
  <div class="col-12 text-center">
	<h3 class="heading">Kids</h3>
	<div class="heading-underline"></div>
  </div>
  <img src="img/kids/Kidsimage.jpg">
	<a href="#kidspage" class="btn btn-primary btn-lg">Explore</a>
</div>
</div>

<!-- Contact Section -->
<div id="contact">
  <footer>
<div class="row justify-content-center">

	<div class="col-md-5 text-center">
		<img src="img/Logo.png">
		<p>We have a collection of different new jerseys and cleats of sizes to satisfy our customers. Checkout our Facebook, Twitter and Instagram pages.</p>
		<strong>Contact Info</strong>
		<p>(+254)4041-6423<br>email@gmail.com</p>
		<a href="https://twitter.com/home" target="-blank"><i class="fab fa-twitter-square"></i></a>
		<a href="https://facebook.com/home" target="-blank"><i class="fab fa-facebook-square"></i></a>
		<a href="https://instagram.com/home" target="-blank"><i class="fab fa-instagram"></i></a>
	</div>
	
	<hr class="socket">
	&copy; Football World.
	</div>
</footer>
</div>
</body>
</html>


/*--- CSS FILE BELOW ---*/

body{
	overflow-x: hidden;
	font-family: 'Lato', sans-serif;
	color: #000000;
	}

/*--- Navbar ---*/
.navbar{
	text-transform: uppercase;
	font-weight: 700;
	font-size: .8rem;  /*--- (1rem = 16px) ---*/
	letter-spacing: .1rem;  
	background: rgba(0, 0, 0, .6)!important;
	}
.navbar-brand img{
	height: 3rem;
	}
.navbar-nav li{
	padding: .5rem;  /*--- Give spaces between the navbar list items ---*/
	}
.navbar-dark .navbar-nav .nav-link{
	color: white;
	padding-top: .9rem;
	}
.navbar-dark .navbar-nav .nav-link.active,
.navbar-dark .navbar-nav .nav-link:hover{
	color: #ffa500;
	}
	
/*--- For Slideshow ---*/
.carousel-item{
	height: 100vh;
	}
.carousel-inner img{
	width: 100%;
	height: 100%;
	}
.carousel-caption{
	position: absolute;
	top: 44%;
	text-transform: uppercase;
	}
.carousel-caption h1{
	font-size: 2.5rem;
	text-shadow: .1rem .1rem .5rem black;
	padding-bottom: 1rem;
	}
.row img{
	padding-top: 4rem;
	height: 35rem;
	}
.btn-warning{
	background-color: #FF9900;
	border: 0;
	
	}
.btn-warning:hover{
	background-color: #b4b4b4;
	}
h6{
	top: 20%;
	font-weight: 800;
	font-family: shadow;
	font-size: 1.6rem;
	color: #00000;
	padding: 4rem;	
	text-shadow: .1rem .1rem .5rem black;
	}
	
/*--- ABOUT SECTION ---*/
.jumbotron {
	border-radius: 0;
	padding: .01rem 0 13rem; /*-- Top and Bottom padding *--/
	}
/*--- NEW RELEASE SECTION ---*/
h3.heading{
	font-size: 1.8rem;
	font-weight: 700;
	text-transform: uppercase;
	padding: 5.2rem;
	padding-bottom: 1.9rem;
	}
.heading-underline{
	width: 3rem;
	height: .2rem;
	background-color: #DAA520;
	margin: 0 auto 1rem;
	}
.card{
	margin: 2rem;
	}
	
/*-- MEN SECTION --*/
.card.col-md-3{
	margin: .01rem;
	}
	
/*-- WOMEN & KIDS SECTION --*/
.container-fluid{
	width: 80%;
	height: 80%;
	padding-bottom: 12rem;
	}

/*-- CONTACT --*/
footer{
	background-color: #40474e;
	color: white;
	padding: 5rem 0 3rem;
	margin-top: 1rem;
	}
footer img{
	height: 6rem;
	margin: 1.5rem 0;
	}
footer a{
	color: white;
	}
footer a{
	color: white;
	}
footer svg.svg-inline--fa{
	font-size: 1.6rem;
	margin: 1.2rem .5rem 0 0;
	}
footer svg.svg-inline--fa:hover{
	color: #ff8000;
	}
hr.socket{
	border-top: .2rem solid #ff8000;
	width: 100%;
	}
