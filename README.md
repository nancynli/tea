<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Graviola Tea Company</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://fonts.googleapis.com/css?family=Roboto+Condensed" rel="stylesheet">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <link rel="stylesheet" type="text/css" href="styles.css"/>

</head>


<body id="Home" data-spy="scroll" data-target=".navbar" data-offset="50">

<nav class="navbar navbar-default navbar-fixed-top">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="#Home">GRAVIOLA TEA COMPANY</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#Home">Home</a></li>
                  <li class="dropdown">
            <a class="dropdown-toggle" data-toggle="dropdown" href="#">About
            <span class="caret"></span></a>
            <ul class="dropdown-menu">
              <li><a href="#">History</a></li>
              <li><a href="#">Press</a></li>
              <li><a href="#">Team</a></li>
              <li><a href="#">Careers</a></li>
            </ul>
        <li><a href="#Tea">Tea</a></li>
        <li><a href="#Menu">Menu</a></li>
        <li><a href="#Events">Events</a></li>
         <li><a href="#Visit">Visit</a></li>
      </ul>
    </div>
  </div>
</nav>


<!-- Container (Carousel Section) -->

<div id="myCarousel" class="carousel slide" data-ride="carousel">

    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
      <div class="item active">
        <img src="img/carousel1.jpg" alt="New York" width="1200" height="800">
      </div>

      <div class="item">
        <img src="img/carousel2.jpg" alt="Chicago" width="1200" height="800">
      </div>
    
      <div class="item">
        <img src="img/carousel3.jpg" alt="Los Angeles" width="1200" height="800">
      </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
</div>


<!-- Container (Tea Section) -->
<div id="Tea" class="container text-center">
  <img src="img/logo-round.png" width="100" height="100" alt="logo-round" title="logo-round">
    <h3><strong>We Know Quality</strong></h3>
  <p>We are second generation tea merchants. Tea is not only a business to us, it is what we drink day in and out, and what we obsess over. It is this obsession that drives us to seek out the best tea and teaware we can. Give Graviola Tea Company a try and taste the difference.</p>
  <br>
  <div class="row">

    <div class="col-sm-3">
      <p class="text-center"><strong>Variety</strong></p>
      <img src="img/tea1.jpg" width="150" height="100" alt="tea1" title="tea1">
      <p>Cultivar variations affect the flavor and aroma of a tea; it is one of the factors that determine a tea’s character.</p>
      </div>

   <div class="col-sm-3">
      <p class="text-center"><strong>Provenance</strong></p>
      <img src="img/tea2.jpg" width="150" height="100" alt="tea2" title="tea2">
      <p>Soil type, climate, surrounding vegetation, and elevation can all produce different nuances in tea.</p>
      </div>


    <div class="col-sm-3">
      <p class="text-center"><strong>Harvest Date</strong></p>
      <img src="img/tea3.jpg" width="150" height="100" alt="tea3" title="tea3">
      <p>Time of harvest distinguishes a great tea from a mediocre one. Teas have only 1-2 peak harvesting times.</p>
      </div>

    <div class="col-sm-3">
      <p class="text-center"><strong>Craftsmanship</strong></p>
      <img src="img/tea4.jpg" width="150" height="100" alt="tea4" title="tea4">
      <p>The tea maker creates the different tea types we are familiar with by controlling the oxidation of the tea leaf with heat.</p>
      </div>

  </div>
</div>


<!-- Container (Menu Section) -->
<div id="Menu" class="bg-1">
  <div class="container text-center">
    <h3>Food &amp; Tea Pairings</h3>

<ul class="list-group">
  <li><strong>Japanese service.</strong> Steamed organic brown rice, seaweed salad, seasonal veggies. Paired with Ryokucha Green Tea. 16</li>
  <li><strong>English service.</strong> 3-tiered platter: fritatta, cherry oat scone with cream and jam, market fruit. Paired with English Breakfast Black Tea. 24</li>
  <li><strong>Moorish service.</strong> Grilled halloumi veggie kebabs over large Lacinato kale salad. Paired with Moorish Mint Green Tea. 23</li>
  <li><strong>Russian service.</strong> Borscht vegetarian beet soup and tea-smoked chicken salad sandwich. Paired with Tolstoy’s Sip Black Tea. 24</li>
  <li><strong>Chinese service.</strong> Seasonal veggie stir-fry, organic brown rice, squash dumplings. Paired with Blood Orange Pu-erh Tea. 19</li>
  </ul>

  <h3>Tea Selections</h3>

    <div id="tea-selections">

          <div class="col-sm-3">
          <p><strong>Black Tea</strong></p>
                <p>Masala Chai. Cardamom, black pepper, cinnamon, cloves, ginger, black tea, whole milk, raw cane sugar 6</p>
                <p>Tolstoy's Sip. Traditional Russian-style smokey black tea with dried blackberry, strawberry, currants 10</p>
            </div>


          <div class="col-sm-3">
          <p><strong>Green Tea</strong></p>
                <p>Moorish Mint. Green tea, peppermint, fennel, black pepper, ginger, licorice, cardamom 10</p>
                <p>Ryokucha. Japanese medium steamed green tea, matcha powder, toasted brown rice 10</p>
            </div>

          <div class="col-sm-3">
          <p><strong>Oolong Tea</strong></p>
                <p>Iron Goddess of Mercy. Taiwanese hand-rolled oolong. Notes of caramel, shiitake mushroom, roasted chicory 10</p>
                <p>Golden Phoenix. From Phoenix Mountain, China. Notes of ripe plum, caramelized sugar, honey 17</p>
            </div>

          <div class="col-sm-3">
          <p><strong>Specialty Tea</strong></p>
                <p>Spearmint Sage. Yakima Valley spearmint and peppermint, sage, lemongrass, lavender, orange peel 10</p>
                <p>Ocean of Wisdom. South African rooibos, ginger, cinnamon, clove, licorice root, black pepper 10</p>
            </div>
    </div>
  </div>
</div>

<br>
<br>
<br>
<br>
<br>
<br>
<br>



<!-- Container (Calendar of Events Section) -->

<div id="Events" class="bg-2">
  <div class="container">
    <h3 class="text-center"><strong>Calendar of Events</strong></h3>


<div class="month">
  <ul>
    <li class="prev">❮</li>
    <li class="next">❯</li>
    <li style="text-align:center">
      <span style="font-size:16px">November 2016</span>
    </li>
  </ul>
</div>

<ul class="weekdays">
  <li>Mo</li>
  <li>Tu</li>
  <li>We</li>
  <li>Th</li>
  <li>Fr</li>
  <li>Sa</li>
  <li>Su</li>
</ul>

<ul class="days">
  <li>1</li>
  <li>2</li>
  <li>3</li>
  <li>4</li>
  <li>5</li>
  <li>6</li>
  <li>7</li>
  <li>8</li>
  <li>9</li>
  <li>10</li>
  <li>11</li>
  <li>12</li>
  <li>13</li>
  <li>14</li>
  <li>15</li>
  <li>16</li>
  <li>17</li>
  <li>18</li>
  <li>19</li>
  <li>20</li>
  <li>21</li>
  <li>22</li>
  <li>23</li>
  <li>24</li>
  <li>25</li>
  <li>26</li>
  <li>27</li>
  <li>28</li>
  <li>29</li>
  <li>30</li>
</ul>
</div>
<br>
<br>


<!-- Container (Visit Section) -->
<div id="Visit" class="bg-3">
  <div class="container">
  <h3><strong>Visit Us</strong></h3>
  
  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3152.946839874297!2d-122.39588938439407!3d37.79128557975635!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80858064ee150287%3A0x9e4dd36ae6936dc7!2s155+Main+St%2C+San+Francisco%2C+CA+94105!5e0!3m2!1sen!2sus!4v1477446941031" width="800" height="600" frameborder="0" style="border:0" allowfullscreen></iframe>
</div>

<!-- Footer -->

<footer>
  <a class="up-arrow" href="#Home" data-toggle="tooltip" title="TO TOP">
    <span class="glyphicon glyphicon-chevron-up"></span></a>
      <h5><strong>Stay Connected</strong></h5>
    <p>
      <a href="http://www.facebook.com/nancynli/" target=“_blank”><img src="img/fb.png" alt="Facebook" title="Facebook" width="30" height="30"></a>
      <a href="http://www.twitter.com/cityborngirl/" target=“_blank”><img src="img/twitter.png" alt="Twitter" title="Twitter" width="30" height="30"></a>
      <a href="http://www.instagram.com/nancyinsf/" target=“_blank”><img src="img/instagram.png" alt="Instagram" title="Instagram" width="30" height="30"></a>
        </p>
        </footer>

<div id="copyright"><span><small>&#169; 2016 Graviola Tea Company</small></span></div>





<!--Smooth scroll-->


<script>
$(document).ready(function(){
  // Initialize Tooltip
  $('[data-toggle="tooltip"]').tooltip();
  
  // Add smooth scrolling to all links in navbar + footer link
  $(".navbar a, footer a[href='#Home']").on('click', function(event) {

    // Make sure this.hash has a value before overriding default behavior
    if (this.hash !== "") {

      // Prevent default anchor click behavior
      event.preventDefault();

      // Store hash
      var hash = this.hash;

      // Using jQuery's animate() method to add smooth page scroll
      // The optional number (900) specifies the number of milliseconds it takes to scroll to the specified area
      $('html, body').animate({
        scrollTop: $(hash).offset().top
      }, 900, function(){
   
        // Add hash (#) to URL when done scrolling (default click behavior)
        window.location.hash = hash;
      });
    } // End if
  });
})
</script>


</div>
</body>
</html>

