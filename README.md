<!DOCTYPE html>
<html>
  <head>
    <title>Ugadi Festival Poster</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
      body {
        background-color: #f2f2f2;
        margin: 0;
        padding: 0;
        font-family: Arial, sans-serif;
        
      background-image: url("https://i.pinimg.com/originals/fc/24/8f/fc248fdcee78408185d622d84b46b498.jpg");
     
    }
    

      .container {
        max-width: 600px;
        margin: 0 auto;
        padding: 30px;
        background-color:rgb(205, 192, 255);
        border-radius: 20px;
        box-shadow: 0 0 10px rgba(0,0,0,0.3);
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: center;
        text-align: center;
        background-size: cover;
      }
      .btn {
			display: inline-block;
			padding: 10px 20px;
			background-color:rgb(133, 105, 255);
			color: #ffffff;
			border-radius: 5px;
			text-decoration: none;
			font-size: 15px;
			transition: background-color 0.3s ease;
      text-align: center;
      align-items: center;
		}
        .btn:hover {
			background-color:darkblue;
		}

      .title {
        font-size: 36px;
        color: #8400ff;
        margin: 0;
        width: 100%;
      }

      .subtitle {
        font-size: 24px;
        color: #333;
        margin: 20px 0;
        width: 100%;
        color: mediumblue;
      }

      .date {
        font-size: 18px;
        color: #333;
        margin: 10px 0;
        width: 100%;
        color:rgb(98, 21, 199);
      }

      .venue {
        font-size: 18px;
        color: #333;
        margin: 10px 0;
        width: 100%;
        color: red;
      }

      .image {
         max-width: 90%;
      padding :2px;
        margin:30px; 
        border: 5px solid red;
        
       
        
      }

      @media screen and (max-width: 600px) {
        .container {
          flex-direction: column;
        }
        .image {
          max-width: 70%;
        }
        .btn {
			display: inline-block;
			padding: 10px 20px;
			background-color: #ff9900;
			color: #fff;
			border-radius: 5px;
			text-decoration: none;
			font-size: 18px;
			transition: background-color 0.3s ease;
		}
        .btn:hover {
			background-color: hotpink;
		}
        
      }
    </style>
  </head>
  <body>
    <div class="container">
      <h1 class="title">Celebrate Ugadi Festival with Us</h1>
      <img class="image" src="https://static.toiimg.com/photo/msid-90595553/90595553.jpg" alt="Ugadi Festival Poster">
     
      <p class="subtitle">Join us in welcoming the New Year with traditional fervour and joy</p>
     
        <p class="events"><h3>EVENTS:</h3><h2>1:Poster making 2:Techqiuz 3:Photography 4:Mehandi 5:Rampwalk</h2></p>
      <p class="date">Date: 21 Mar, 2023 9:30am to 4:30pm</p>
      <p class="venue">Venue: Qis college ,Vengamukkapalem,Andhra Pradesh</p>
      <a href="#" class="btn">Register Now</a>
    </div>
  </body>
</html>
