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
</body>
</html>

/*--- CSS file below ---*/

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
