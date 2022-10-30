# bulding
new project
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css" integrity="sha512-xh6O/CkQoPOWDdYTDqeRdPCVd1SpvCA9XXcUnZS2FmJNp1coAFzvtCN9BmamE+4aHK8yyUHUSCcJHgXloTyT2A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/brands.min.css" integrity="sha512-+oRH6u1nDGSm3hH8poU85YFIVTdSnS2f+texdPGrURaJh8hzmhMiZrQth6l56P4ZQmxeZzd2DqVEMqQoJ8J89A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<link rel="stylesheet" href="css/bootstrap.css">
</head>
<style>
*,
*:after,
*:befor{
box-sizing:border-box;
}
:root{
--background-color-1:#ebe9eb;
--background-color-2:#4F4F4F;
--background-color-3:rgba(36,164,234,0.8);
--font-color-1:#929292;
--font-color-2:#666;
--font-color-3:#6c757d;
--font-color-4:#3F3530;
--font-color-5:#E1E1E1;
}
.z-index-1{
z-index:10;
}
.back-image{
height:70vh;
background-image:url('images/2.jpg');
background-repeat:no-repeat;
background-size:cover;
background-position:center center;
}
.back-img-1{
background-image:url('images/2.jpg');
background-repeat:no-repeat;
background-size:cover;
}
.position-sticky{
position:sticky;
top:0;
background-color:white;
}
.hr-line{
width:30px;
height:6px;
background-color:#C1C0B1;
}
.border-radius{
border-radius:15px 0 15px 0;
}
.background-color-1{
background-color:var(--background-color-1);
}
.background-color-2{
background-color:var(--background-color-2);
}
.padding-top{
padding-top:20vh;
}
.padding-top-2{
padding-top:10vh;
}
.padding-top-3{
padding-top:10vh;
}
.padding-top-4{
padding-top:5vh;
}
.padding-bottom{
padding-bottom:10vh;
}
.padding-bottom-2{
padding-bottom:5vh;
}
.font-size-1{
font-size:5vh;
}
.font-color{
color:var(--font-color-1);
}
.font-color-1{
color:var(--font-color-2);
}
.font-color-5{
color:var(--font-color-5);
}
.text-color{
color:#929292;
transition:all 100ms;
}
.text-color > a:hover{
color:#666;
}
.under-list{
list-style-type:none;
text-align:center;
color:var(--font-color-1);
}
.under-list a{
color:var(--font-color-4);
text-decoration:none;
}
.under-list > a:hover{
color:var(--font-color-1);
transition:all 0.5s;
}
.list-group{
list-style-type:none;
}
.list-group a{
text-decoration:none;
margin:10px;
pading-left:0;
}

[type="text"]{
width:400px;
height:5vh;
border:unset;
padding:1rem;
}
.type-button{
width:100px;
height:5vh;
background-color: #897F6E;
color:var(--font-color-5);
border-radius:0 0 15px 0;
}
.type-button:hover{
background-color:var(--font-color-4);
}
.font-color-6{
color:var(--font-color-1);
transition:all 500ms;
}
.font-color-6:hover{
color:var(--font-color-4);
}
.bottom-link{
text-decoration:none;
color:var(--font-color-5);
transition:all 500ms;
}
.bottom-link:hover{
text-decoration:none;
color:var(--font-color-1);
}
.tran-img{
transition: width 1s, height 1s, transform 2s;
}
.tran-img:hover{
transform:rotate(-5deg) scale(1.1);
}
.carousel-indicators [data-bs-target] {
	box-sizing: content-box;
	width: 30px;
	height: 10px;
	padding: 0;
	margin-right: 3px;
	margin-left: 3px;
	text-indent: -999px;
	cursor: pointer;
	opacity: 0.5;
	transition: opacity 0.6s ease;
	background-color: red;
border:1px solid white;
	border-radius: 50%;
}
.font-color-red{
color:red;
}
</style>
<body>
<div class="container-fluid position-sticky z-index-1">
<div class="container p-5">
<div class="row">
<div class="col-4">
<a href="#"><img src="images/1.jpg"></a>
</div>
<div class="col-6 row d-flex align-self-center px-3">
<ul class="d-flex under-list m-3">
<a href="#" class="col ms-auto fw-bold"><li class=" col ms-auto">Home</li></a>
<a href="#" class="col fw-bold"><li class="col">Shop</li></a>
<a href="#" class="col fw-bold"><li class="col">Listing</li></a>
<a href="#" class="col fw-bold"><li class="col">Blog</li></a>
<a href="#" class="col fw-bold"><li class="col">Sevice</li></a>
<a href="#" class="col me-auto fw-bold"><li class="col me-auto">Contact</li></a>
</ul>
</div>
<div class="col-2 row d-flex align-self-center">
<div class="col"><a href="#"><i class="fa-solid fa-magnifying-glass font-color"></i></a></div>
<div class="col me-auto"><a href="#"><i class="fa-solid fa-magnifying-glass font-color"></i></a></div>
</div>
</div>
</div>
</div>
<div class="container-fluid ms-0">
<div class="row d-flex">
<div class="col-12">
<div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
  <div class="carousel-indicators d-flex flex-row justify-content-center">
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2""></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3""></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="images/88.jpg" class="d-block w-100" alt="..." width="300px" height="600px">
      <div class="carousel-caption d-none d-md-block">
        <h5 class="text-black fs-4 fw-bold">First slide label</h5>
        <p class="text-black fs-3">Some representative placeholder content for the first slide.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="images/3.jpg" class="d-block w-100" alt="..." width="300px" height="600px">
      <div class="carousel-caption d-none d-md-block">
        <h5 class="text-black fs-4 fw-bold">Second slide label</h5>
        <p class="text-black fs-3">Some representative placeholder content for the second slide.</p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="images/77.jpg" class="d-block w-100" alt="..." width="300px" height="600px">
      <div class="carousel-caption d-none d-md-block">
        <h5 class="text-black fs-4 fw-bold">Third slide label</h5>
        <p class="text-black fs-3">Some representative placeholder content for the third slide.</p>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
   <i class='fas fa-angle-double-left font-color-red fs-2 fw-bold'></i>
  </button>
<button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
<i class='fas fa-angle-double-right font-color-red fs-2 fw-bold'></i>
</button>
</div>
</div>
</div>
</div>
<div class="container mt-5">
<div class="d-flex flex-column align-items-center">
<div class="col mt-3 text-muted fs-4">Welcome to</div>
<div class="col mt-3 fw-bolder font-size-1">Housy Real Estate</div>
<div class="col mt-3">
<hr class=" hr-line">
</div>
<div class="col-6 mt-3 text-center"><b>Lorem Ipsum</b> is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</div>
<div class="mt-5"><button type="button" class="btn btn-outline-secondary border-radius">Learn About</button>
</div>
</div>
</div>
<div class="container mt-5">
<div class="row">
<div class="col row g-3">
<div class="col-6">
<div class="card text-bg-dark">
  <img src="" class="card-img back-img-1" width="300px" height="300px">
  <div class="card-img-overlay">
    <h5 class="card-title mt-5 text-dark ms-5">Condo Type </h5>
    <p class="card-text ms-5 mt-3">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
    <p class="card-text mt-2 ms-5"><small>Last updated 3 mins ago</small></p>
<div class="mt-5 ms-5"><button type="button" class="btn btn-outline-secondary border-radius text-white mt-3">Learn About</button>
</div>
  </div>
</div>
</div>
<div class="col-6">
<div class="card text-bg-dark">
  <img src="" class="card-img back-img-1" width="300px" height="300px">
  <div class="card-img-overlay">
    <h5 class="card-title mt-5 text-dark ms-5">Card title</h5>
    <p class="card-text ms-5">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
    <p class="card-text mt-2 ms-5"><small>Last updated 3 mins ago</small></p>
<div class="mt-5 ms-5"><button type="button" class="btn btn-outline-secondary border-radius text-white">Learn About</button>
</div>
  </div>
</div>
</div>
<div class="col-6">
<div class="card text-bg-dark">
  <img src="" class="card-img back-img-1" width="300px" height="300px">
  <div class="card-img-overlay">
    <h5 class="card-title mt-5 ms-5">Card title</h5>
    <p class="card-text ms-5">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
    <p class="card-text mt-2 ms-5"><small>Last updated 3 mins ago</small></p>
<div class="mt-5 ms-5"><button type="button" class="btn btn-outline-secondary border-radius text-white">Learn About</button>
</div>
  </div>
</div>
</div>
<div class="col-6">
<div class="card text-bg-dark">
  <img src="" class="card-img back-img-1" width="300px" height="300px">
  <div class="card-img-overlay">
    <h5 class="card-title mt-5 ms-5">Card title</h5>
    <p class="card-text ms-5">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
    <p class="card-text mt-2 ms-5"><small>Last updated 3 mins ago</small></p>
<div class="mt-5 ms-5"><button type="button" class="btn btn-outline-secondary border-radius text-white">Learn About</button>
</div>
  </div>
</div>
</div>
</div>
</div>
</div>

<div class="container mt-5 pt-5 mb-5">
Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of <b>“de Finibus Bonorum et Malorum”</b> (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. 
</div>

<div class="container-fluid padding-top padding-bottom vh-auto background-color-1">
<div class="d-flex flex-column align-items-center">
<div class="col font-color fs-5">New Listings </div>
<div class="col mt-4 fw-bold font-size-1">The Latest Type </div>
<div class="col mt-4">
<hr class=" hr-line">
</div>
<div class="col mt-4">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</div>
</div>
<div class="container padding-top">
<div class="row row-cols-1 row-cols-md-3 g-4">
  <div class="col">
    <div class="card h-100 rounded-0 overflow-hidden">

      <img src="images/3.jpg" class="card-img-top" alt="..."height="400px">
<span style="background-color:silver; width:80px;position:absolute;top:352px;">Residential</span>
<span style="background-color:green; width:100px;position:absolute;top:376px;">17.175.000,00</span>
<span style="background-color:var(--background-color-3); width:80px;position:absolute;top:0px;left:350px;top:10px;text-align:center; transform:rotate(45deg);overflow: visible;">NEW</span>
      <div class="card-body">
        <h5 class="card-title mt-3 font-color-1">Mangrove Villa</h5>
        <p class="card-text mt-3 font-color">300 E Rio Salado<br>
Tempe, Arizona 85281</p>
      </div>
      <div class="card-footer d-flex flex-row justify-content-center">
        <div class="col text-center font-color">4<br>Beds</div>
<div class="col text-center font-color">2<br>Baths</div>
<div class="col text-center font-color">1.500<br>Square Feet</div>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100 rounded-0">
      <img src="images/3.jpg" class="card-img-top" alt="..." height="400px">
      <div class="card-body">
        <h5 class="card-title mt-3 font-color-1">Card title</h5>
        <p class="card-text mt-3 font-color">This card has supporting text below as a natural lead-in to additional content.</p>
      </div>
      <div class="card-footer d-flex flex-row justify-content-center">
                <div class="col text-center font-color">4<br>Beds</div>
<div class="col text-center font-color">2<br>Baths</div>
<div class="col text-center font-color">1.500<br>Square Feet</div>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100 rounded-0">
      <img src="images/4.jpg" class="card-img-top" alt="..." height="400px">
      <div class="card-body">
        <h5 class="card-title mt-3 font-color-1">Card title</h5>
        <p class="card-text mt-3 font-color">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
      </div>
      <div class="card-footer d-flex flex-row justify-content-center">
<div class="col text-center font-color">4<br>Beds</div>
<div class="col text-center font-color">2<br>Baths</div>
<div class="col text-center font-color">1.500<br>Square Feet</div>
      </div>
    </div>
  </div>
</div>


<div class="row row-cols-1 row-cols-md-3 g-4 mt-1">
  <div class="col">
    <div class="card h-100 rounded-0">
      <img src="images/2.jpg" class="card-img-top" alt="..." height="400px">
      <div class="card-body">
        <h5 class="card-title mt-3 font-color-1">Mangrove Villa</h5>
        <p class="card-text mt-3 font-color">300 E Rio Salado<br>
Tempe, Arizona 85281</p>
      </div>
      <div class="card-footer d-flex flex-row justify-content-center">
        <div class="col text-center font-color">4<br>Beds</div>
<div class="col text-center font-color">2<br>Baths</div>
<div class="col text-center font-color">1.500<br>Square Feet</div>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100 rounded-0">
      <img src="images/3.jpg" class="card-img-top" alt="..." height="400px">
      <div class="card-body">
        <h5 class="card-title mt-3 font-color-1">Card title</h5>
        <p class="card-text mt-3 font-color">This card has supporting text below as a natural lead-in to additional content.</p>
      </div>
      <div class="card-footer d-flex flex-row justify-content-center">
                <div class="col text-center font-color">4<br>Beds</div>
<div class="col text-center font-color">2<br>Baths</div>
<div class="col text-center font-color">1.500<br>Square Feet</div>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100 rounded-0">
      <img src="images/4.jpg" class="card-img-top" alt="..." height="400px">
      <div class="card-body">
        <h5 class="card-title mt-3 font-color-1">Card title</h5>
        <p class="card-text mt-3 font-color">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
      </div>
      <div class="card-footer d-flex flex-row justify-content-center">
<div class="col text-center font-color">4<br>Beds</div>
<div class="col text-center font-color">2<br>Baths</div>
<div class="col text-center font-color">1.500<br>Square Feet</div>
      </div>
    </div>
  </div>
</div>


<div class="row row-cols-1 row-cols-md-3 g-4 mt-1">
  <div class="col">
    <div class="card h-100 rounded-0">
      <img src="images/2.jpg" class="card-img-top" alt="..." height="400px">
      <div class="card-body">
        <h5 class="card-title mt-3 font-color-1">Mangrove Villa</h5>
        <p class="card-text mt-3 font-color">300 E Rio Salado<br>
Tempe, Arizona 85281</p>
      </div>
      <div class="card-footer d-flex flex-row justify-content-center">
        <div class="col text-center font-color">4<br>Beds</div>
<div class="col text-center font-color">2<br>Baths</div>
<div class="col text-center font-color">1.500<br>Square Feet</div>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100 rounded-0">
      <img src="images/3.jpg" class="card-img-top" alt="..." height="400px">
      <div class="card-body">
        <h5 class="card-title mt-3 font-color-1">Card title</h5>
        <p class="card-text mt-3 font-color">This card has supporting text below as a natural lead-in to additional content.</p>
      </div>
      <div class="card-footer d-flex flex-row justify-content-center">
                <div class="col text-center font-color">4<br>Beds</div>
<div class="col text-center font-color">2<br>Baths</div>
<div class="col text-center font-color">1.500<br>Square Feet</div>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100 rounded-0">
      <img src="images/4.jpg" class="card-img-top" alt="..." height="400px">
      <div class="card-body">
        <h5 class="card-title mt-3 font-color-1">Card title</h5>
        <p class="card-text mt-3 font-color">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
      </div>
      <div class="card-footer d-flex flex-row justify-content-center">
<div class="col text-center font-color">4<br>Beds</div>
<div class="col text-center font-color">2<br>Baths</div>
<div class="col text-center font-color">1.500<br>Square Feet</div>
      </div>
    </div>
  </div>
</div>
</div>
</div>

<div class="container padding-top">
<div class="d-flex flex-column align-items-center">
<div class="col text-muted fs-4">From The Blog</div>
<div class="col mt-3 fw-bolder font-size-1">The Latest News</div>
<div class="col mt-3">
<hr class="hr-line">
</div>
<div class="col mt-3">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</div>
<div class="container">
<div class="row row-cols-1 row-cols-md-3 g-4 mt-5">
  <div class="col">
    <div class="card rounded-0">
      <img src="images/5.jpg" class="card-img-top tran-img" alt="..." height="200px">
<div class="d-flex flex-row justify-content-between font-color ps-3 text-color mt-2">
<a href="#" class="font-color"><div class="col"><i class="fa-solid fa-magnifying-glass font-color m-2"></i></div></a>
<a href="#" class="font-color me-auto text-decoration-none"><div class="col">September 5, 2021 </div></a>
<a href="#" class="font-color"><div class="col"><i class="fa-solid fa-magnifying-glass font-color m-2"></i></div></a>
<a href="#" class="font-color me-auto text-decoration-none"><div class="col">Idea</div></a>
</div>
      <div class="card-body">
        <h5 class="card-title font-color-1">A unique way to make your<br> kitchen look… </h5>
        <p class="card-text mt-3">Lorem ipsum dolor sit amet,<br> consectetur adipiscing elit.<br> Proin convallis lectus odio, nec ultricies<br> odio…</p>
<div class="mt-3"><button type="button" class="btn btn-outline-secondary border-radius">Learn About</button>
</div>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card rounded-0">
      <img src="images/3.jpg" class="card-img-top tran-img" alt="..." height="200px">
<div class="d-flex flex-row justify-content-between font-color ps-3 text-color mt-2">
<a href="#" class="font-color"><div class="col"><i class="fa-solid fa-magnifying-glass font-color m-2"></i></div></a>
<a href="#" class="font-color me-auto text-decoration-none"><div class="col">September 5, 2021</div></a>
<a href="#" class="font-color"><div class="col"><i class="fa-solid fa-magnifying-glass font-color m-2"></i></div></a>
<a href="#" class="font-color me-auto text-decoration-none"><div class="col">	Inspiration</div></a>
</div>
      <div class="card-body">
        <h5 class="card-title font-color-1">Dream house is everyone’s<br> dream </h5>
        <p class="card-text mt-3">Lorem ipsum dolor sit amet,<br> consectetur adipiscing elit. Proin<br> convallis lectus odio, nec ultricies<br> odio…</p>
<div class="mt-3"><button type="button" class="btn btn-outline-secondary border-radius">Learn About</button>
</div>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card rounded-0 bs-sm">
      <img src="images/4.jpg" class="card-img-top tran-img" alt="..." height="200px">
<div class="d-flex flex-row justify-content-between font-color ps-3 text-color mt-2">
<a href="#" class="font-color"><div class="col"><i class="fa-solid fa-magnifying-glass font-color m-2"></i></div></a>
<a href="#" class="font-color me-auto text-decoration-none"><div class="col">September 5, 2021</div></a>
<a href="#" class="font-color"><div class="col ms-auto"><i class="fa-solid fa-magnifying-glass font-color m-2"></i></div></a>
<a href="#" class="font-color me-auto text-decoration-none"><div class="col">News</div></a>
</div>
      <div class="card-body">
        <h5 class="card-title font-color-1">The property developer has just launched a new… </h5>
        <p class="card-text mt-3">Lorem ipsum dolor sit amet,<br> consectetur adipiscing elit. Proin<br> convallis lectus odio, nec ultricies<br> odio…</p>
<div class="mt-3"><button type="button" class="btn btn-outline-secondary border-radius">Learn About</button>
</div>
      </div>
    </div>
  </div>
</div>
</div>
</div>
</div>
<div class="container-fluid background-color-2 mt-5 padding-top-3 padding-bottom">
<div class="container">
<div class="row d-flex flex-row">
<div class="col-6 text-white fs-4 fw-bold">
<div>Enter your email to subscribe<br> our newsletter</div>
<div class="font-color-5 fs-6 mt-3">A small river named Duden flows by their<br> place and supplies.</div>
</div>
<div class="col-6 align-items-center d-flex">
<input type="text" placeholder="Enter Email" class="input-text" >
<input type="submit" value="Subscribe" class="type-button">
</div>
</div>
</div>
</div>

</div>
<div class="container-fluid bg-dark text-white-1">
<div class="container">
<div class="row d-flex">
<div class="col-3 padding-top-2">
<img src="images/logo.png">
<div class="col font-color-5 mt-3">
<span>In publishing and graphic design, Lorem<br> ipsum is a placeholder text. </span>
</div>
</div>
<div class="col-3 text-white padding-top-2 padding-bottom">Information
<ul class="font-color-5 list-group">
<a href="#"><li class="font-color-6">About</li></a>
<a href="#"><li class="font-color-6">Listing</li></a>
<a href="#"><li class="font-color-6">Blog</li></a>
<a href="#"><li class="font-color-6">Shop</li></a>
<a href="#"><li class="font-color-6">Contact</li></a>
</ul>
</div>
<div class="col-3 text-white padding-top-2">Contact
<div class="font-color-6 mt-3">+1 517-224-3344</div>
<div class="font-color-6 mt-3">ali.zarchini@gmail.com</div>
<div class="font-color-6 mt-3">Address</div>
</div>
<div class="col-3 font-color-5 padding-top-2">Social
<ul class="font-color-5 list-group">
<a href="#"><li class="font-color-6">WhatsApp</li></a>
<a href="#"><li class="font-color-6">Instagram</li></a>
<a href="#"><li class="font-color-6">Telegram</li></a>
<a href="#"><li class="font-color-6">Linkedin</li></a>
<a href="#"><li class="font-color-6">Twitter</li></a>
</ul>
</div>
</div>
</div>
</div>
</div>
<div class="container-fluid padding-top-4 padding-bottom-2 background-color-2 font-color-5">
<div class="container">
<div class="row align-self-center">
<div class="col d-flex flex-row">
<div class="col-6"><b>Housy Real Estate</b> estabilished on 2021, created by Housy Company .Inc, all right reserved. </div>
<div class="col-1 ms-auto"><a href="#" class="bottom-link">Terms of Use</a></div>
<div class="col-1"><a href="#" class="bottom-link">Privacy Policy</a></div>
</div>
</div>
</div>
</div>
<!-- JavaScript Bundle with Popper -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-OERcA2EqjJCMA+/3y+gxIOqMEjwtxJY7qPCqsdltbNJuaOe923+mo//f6V8Qbsw3" crossorigin="anonymous"></script>

</body>
</html>
