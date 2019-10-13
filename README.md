<!DOCTYPE html>
<html ng-app="myModule">
  <head>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <script src="https://code.jquery.com/jquery-3.4.1.js" integrity="sha256-WpOohJOqMqqyKL9FccASB9O0KwACQJpFTUBLTYOVvVU=" crossorigin="anonymous"></script>
  	<script type="text/javascript" src="angular.min.js"></script>
  	<script type="text/javascript" src="FirstAid.js"></script>
  	<link rel="stylesheet" type="text/css" href="FirstAid.css">
  	
  	
  	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
  	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

    <link href="https://fonts.googleapis.com/css?family=M+PLUS+1p&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Source+Code+Pro:700&display=swap" rel="stylesheet">

  </head>
  <body>
  <div id="main">


    <div id="header">
     
      <div class="topnav" id="myTopnav">
        <a href="#home" class="active">Home</a>
        <a href="#aboutus">About Us</a>
        <a href="#contact">Contact</a>
        <a href="javascript:void(0);" class="icon" onclick="myFunction()">
          <i class="fa fa-bars"></i>
        </a>

        <form class="navbar-form navbar-right" method="get" action="http://www.google.com/search" style="color: white; padding-right: 40px" >
          <div class="input-group">
            <input type="text" name="q" size="20" maxlength="255" value="" style="color: black" class="form-control" placeholder="Search Google"/> 
            <div class="input-group-btn">
              <button class="btn btn-default" type="submit">
                <i class="glyphicon glyphicon-search"></i>
              </button>
            </div>
          </div>
        </form>
        
      </div>

    </div>

    <div id="body1" >

      <div style="padding-left: 45.5%">
          <img src="mirage.png" alt="Mirage">
      </div>
      <br>
      <p id="heading" style="font-size: 75px; text-align: center; color: #dd2476">FIRST AID</p>
      <br>
      <p style="font-size: 30px; text-align: left; padding-left: 8px">Steps to Follow:</p>

    </div>

    <div id="body2" >

      <ol>

        <li>If unconscious, give CPR.</li>
        <li>Lay the person on his back on a firm surface.</li>
        <li>Kneel next to the peron's neck and shoulders.</li>
        <li>Place the heel of one hand over the center of the person's chest, between the nipples. Place your other hand on top of the first hand.</li>
        <li>Keep your elbows straight and position your shoulders directly above your hands.</li>
        <li>Use your upper body weight (not just your arms) as you compress the chest at least 2 inches (approximately 5 centimeters) but not greater than 2.4 inches (approximately 6 centimeters).</li>
        <li>Give chest compressions of 100-120 compressions a minute.</li>
        <li>If you haven't been trained in CPR, continue chest compressions until there are signs of movement or until emergency medical personnel take over.</li>

      </ol>

    </div>

    <br>
    <div>
      <form id="button" action="https://www.youtube.com/watch?v=hizBdM1Ob68">
         <button type="submit" class="btn"><span style="font-weight: bold; color: white; font-size: 15px">View Demonstration</span></button>
      </form>
    </div>
    <br><br><br><br>

    <div>

      <div class="navbar navbar-fixed-bottom" id="myNavbar">
        <a href="#home">Hotline Contact Number : 1800 536 678</a>
      <!--
        <a href="#news">News</a>
        <a href="#contact">Contact</a>
        <a href="#about">About</a>
      -->
        <a href="javascript:void(0);" class="icon" onclick="myFunction()">&#9776;</a>
      </div>

    </div>

  </div>
  <script src="https://code.responsivevoice.org/responsivevoice.js?key=zVG12Uxj"></script>
  </body>
</html>
