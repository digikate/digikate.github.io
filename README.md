<!DOCTYPE html>
<html lang='en'>
<head>
    <meta charset='UTF-8'/>
    <title>Queenstown - Home</title>
    
<style>
    
    @import url('https://fonts.googleapis.com/css2?family=DynaPuff&display=swap');
    


/* Slideshow container */
.slideshow-container {
  max-width: 900px;
  position: relative;
  margin: auto;
  border: 10px solid rgb(229, 248, 250);
  border-radius: 15px;
  display: block;
  box-sizing: border-box;
  margin-top: 1em;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: rgb(255,255,255);
  font-weight: bold;
  font-size: 30px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(255,255,255);
}


/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 25px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}


/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 20px}
}
    *{
        margin:0;
    }
    
    
    body{
        background-color: rgb(203, 248, 250);
        font-family: 'DynaPuff', cursive;
        font-size: 100%;
    }
    
    h1{
        font-size: 3em;
        background-color: rgb(242, 242, 242);
        color: rgb(0, 37, 82);
        text-align: center;
    }
   
    h2{
        font-size: 2em;
        background-color: rgb(242, 242, 242);
        color: rgb(0, 37, 82);
        text-align: center;
    }
    
    h3{
        font-size: 1.5em;
        background-color: rgb(242, 242, 242);
        color: rgb(0, 37, 82);
        text-align: center;
    }
    
    h4{
        font-size: 2em;
        color: rgb(255, 255, 255);
        text-align: center;
        padding: 2em;
    }
    
    p{
        font-size: 1em;
        line-height: 1.2em;
        letter-spacing: 0.1em;
        text-align: left;
        margin: 1em 2em;
        
    }
    
    .little-towns{
        max-width: 1200px;
        margin: 1em 8.5em;
        border: 5px solid rgb(0, 37, 82);
    }
    
    .activities{
        max-width: 1200px;
        border: 5px solid rgb(0, 37, 82);
        margin: 1em 8.5em;
    }
    
    .foodentertainment{
        max-width: 1200px;
        border: 5px solid rgb(0, 37, 82);
        margin: 1em 8.5em;
    }
    
    .photogallery{
        max-width: 1200px;
        border: 5px solid rgb(0, 37, 82);
        margin: 1em 8.5em;
    }
    
    .sub-header{
        text-align:center;
        max-width: 1200px;
        margin: 0.5em 8.5em;
        font-style:inherit;
        border: 3px dashed rgb(0, 37, 82);
        border-radius: 10px;
    }
    
    .row{
        display: table;
        clear: both;
    }
    
    .column1{
        float: left;
        width: 50%;
        box-sizing: border-box;
    }
    
    .column2{
        float: left;
        width: 50%;
        box-sizing: border-box;
    }
    
    .img-responsive{
        max-width: 90%;
        border: 10px solid rgb(229, 248, 250);
        border-radius: 15px;
        display: block;
        box-sizing: border-box;
        margin:auto;
        margin-top: 1.2em
    }
    
    .roundimage{
        border-radius: 50%;
        border: 6px solid rgb(0, 37, 82);
        display:block;
        margin: auto;
        margin-top: 1em;
    }
    
    .overtop{
        position:absolute;
        top:40%;
        width:100%;
        box-sizing: border-box;
        background-color: rgba(0,0,0,0.4);
    }

    
    .nav-bar{
        background-color: rgb(0, 37, 82);
        position: sticky;
        top: 0;
        width: 100%;
        z-index: 1;
    }
    
    .nav{
        list-style: none;
        padding:0;
        margin:0;
        text-align: center;
 
    }
    
    .nav li{
        display: inline;
        
    }
    
    .nav li a{
        padding:1.5em;
        display:inline-block;
        border: 1px dashed rgb(203, 248, 250);
        border-radius: 10px;
        font-size: 1em;
        text-align: center;
    }
    
    a:link{
        text-decoration: none;
        color: rgb(242, 242, 242);
    }
    
    a:visited{
        color: rgb(242, 242, 242);
    }
    
    a:hover{
        background-color: rgb(203, 248, 250);
        color: rgb(0, 37, 82);
    }
    
    
    .dropdown {
     position: relative;
     display: inline-block;

    }

    .dropdown-content {
     display: none;
     position: absolute;
     min-width: 160px;
     box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
     padding: 12px 16px;
     background-color: rgb(0, 37, 82);
    }

   .dropdown:hover .dropdown-content {
    display: block;
    }
    

</style>
</head>
<body>
    <div class="nav-bar">
    <ul class="nav">
    <li><a href="#LT"> Little Towns </a></li>
    <li><a href="#A"> Activities </a></li>
    <div class="dropdown">
        <li><a href="#FE"> Food and entertainment </a></li>
    <div class="dropdown-content">
        <li><a href="#F"> Ferg </a></li>
        <li><a href="#CT"> CookieTime CookieBar</a></li>
        <li><a href="#S"> Shopping</a></li>
    </div>
    </div>
    <li><a href="#PG"> Photo Gallery</a></li>
    </ul>
    </div>
<h1>Queenstown</h1> 
    <hr>
        <h2>Introduction</h2>
    <div class="sub-header">
        <p>Queenstown is located in the South Island of New Zealand. Nicknamed ???the adventure capital of the world???, Queenstown is home to lots of outdoor activities for all to enjoy such as: The Luge, superb bike trails and exploring the beautiful landscapes of Glenorchy. </p>
            
        <p>As well as a range of outdoor activities, Queenstown also offers many famous food destinations such as: Ferg???s Burger and the Cookie Time Cookiebar. You can also go to the Queenstown city centre and enjoy some shopping, everything is within walking distance!</p>
   </div>
    
<div class="little-towns">    
<h2 id="LT">Little Towns</h2>
    <hr>
<div class="row">
    <div class="column2">
<h3>Glenorchy</h3>
<img class="img-responsive" src="images/glenorchyscenery_littletowns.jpg" alt="Glenorchy - Trees in water">
        <p>Glenorchy is a small little town 45 minutes away from Queenstown via a stunning lakeside drive. There, snow capped mountains, pristine lakes, rivers and national parks around Glenorchy featured prominently in the Lord of the Rings trilogy.</p>
<p>If you???re a movie-buff then you can go on the fun and highly educational movie tours run by small companies from Queenstown.
</p>
    </div>
    <div class="column2">
<h3>Arrowtown</h3>
<img class="img-responsive" src="images/arrowtowngoldmine_littletowns.jpg" alt="Chinese goldmining museum - picnic tables">
        <p>Arrowtown is a small village 20 minutes drive from Queenstown. There, you can experience bike trails and picturesque former gold mining village, explore old miners??? cottages, the restored Chinese village and visit the Lakes District museum. </p>
<p>Arrowtown also has a range of cafes, restaurants and bars, boutiques selling homeware, souvenirs and designer clothing.</p>
    </div>
</div>
    </div>
<div class="activities">
<h2 id="A">Activities</h2>

<p>If you enjoy adventure, participating in the following activities will enhance your Queenstown experience: The luge, iFly and scenic trail walks. </p>

<h3>The Luge, Jelly Belly and iFly</h3>
<img class="img-responsive" src="images/luge_activities.jpg" alt="The Luge track">
<p>The Skyline Luge: Take on 900m of banked corners, tight turns, tunnels and stomach dropping dips on the Skyline Luge course. Once you reach the bottom, ride the chairlifts and do it all again! You can even visit the Jelly Belly store and treat yourself to the wide variety of the Pick ???n??? mix jelly beans available.</p>
<hr>
<p>iFly: Experience the feeling of skydiving indoors! You can book a range of packages, fly in virtual reality and fly high.</p>

<h3>Queenstown Trail</h3>
<img class="img-responsive" src="images/queenstowntrail2_activities.jpg" alt="Queenstown Trail">
<p>Queenstown Trail: There are many trails in Queenstown but the basic Queenstown trail is suitable for people of all ages and abilities. Hire a bike or go for a late evening stroll, enjoy the scenery of Lake Wakatipu. </p>
</div>
    
<div class="foodentertainment">    
<h2 id="FE">Food and Entertainment</h2>
    <hr>
<h3 id="F">Ferg</h3>
<img class="roundimage" src="images/newmenu_entertainment.jpg" alt="Fergburger menu" style="width:400px">
<p>Ferg Burger: Operating since 2001, Ferg Burger is famous for its freshly made burgers. Its wide variety of burgers and unique combinations of fillings attracts tourists from all over the world. Ferg also has a range of other branches including: Mrs Ferg (gelato), FergBaker and Ferg???s Bar.</p>
<img class="img-responsive" src="images/ferg_entertainment.jpg" alt="Ferg food shops">
<h3 id="CT">CookieTime CookieBar</h3>
<div class="row">
    <div class="column1">
<img class="img-responsive" src="images/cookietimemilkshake_food.jpg" alt="Cookietime - Freakshake">
    </div>
    <div class="column1">
<img class="img-responsive" src="images/cookietimemonster_entertainment.jpg" alt="Cookie Time shop layout">
    </div>
</div>
<p>CookieTime Cookiebar: Enjoy fresh hot cookies, freak shakes, ice-cream, ice-cream sandwiches and even hot chocolates. </p>
    
<h3 id="S">Shopping</h3>
<img class="img-responsive" src="images/shopping_entertainment.jpg" alt="View of Queenstown's city centre">
<p>Shopping: Queenstown has a compact and easily accessible city centre with all the shopping essentials. From luxury brands, iconic New Zealand design stores, adventure sports equipment to art galleries, book stores and specialty stores there are retail stores for everyone to enjoy and all within walking distance!</p>
    </div>

    <div class="photogallery">
<h3 id="PG">Photo Gallery</h3>
    <div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 6</div>
    <div class="overtop"><h4>The Luge - Track</h4></div>
  <img src="images/theluge_activities.jpg" style="width:100%" alt="The Luge - Track">
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 6</div>
    <div class="overtop"><h4>Bike Track - River</h4></div>
  <img src="images/bikescenery_littletowns.jpg" style="width:100%" alt="River that runs along the bike track">
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 6</div>
    <div class="overtop"><h4>Lake Wakatipu</h4></div>
  <img src="images/queenstowntrail1_activities.jpg" style="width:100%" alt="Lake Wakatipu">
</div>
    
<div class="mySlides fade">
  <div class="numbertext">4 / 6</div>
    <div class="overtop"><h4>Ferg Gelato - Ice-cream Flavours</h4></div>
  <img src="images/ice-cream_food.jpg" style="width:100%" alt="Ferg Gelato - Ice cream">
</div>
    
<div class="mySlides fade">
  <div class="numbertext">5 / 6</div>
  <div class="overtop"><h4>The Luge - Outdoor Cafe</h4></div>
  <img src="images/thelugecafe_activities.jpg" style="width:100%" alt="The Luge - Outdoor cafe">
</div>

        
<div class="mySlides fade">
  <div class="numbertext">6 / 6</div>
    <div class="overtop"><h4>Glenorchy - Part of Lord of the Rings film</h4></div>
  <img src="images/lotrlandscape_littletowns.jpg" style="width:100%" alt="A landscape used in the filming of The Lord of the Rings">
</div>
        
<a class="prev" onclick="plusSlides(-1)">???</a>
<a class="next" onclick="plusSlides(1)">???</a>

</div>
<br>


<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }

  slides[slideIndex-1].style.display = "block";  

}
</script>
    
<footer>Copyright Kate Yu</footer>
</div>
</body>
