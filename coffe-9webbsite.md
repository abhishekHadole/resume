<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <style>
    body{
      color: #fff;
      background-color: #2e1c2a;
      width: 100%;
    }
    .coffe9{
      margin: 3%;
    }
    a:hover{
      cursor: pointer;
    }
    header{
      position: fixed;
      top: 0;
      right: 0;
      width: 100%;
      height: 10%;
      z-index: 1000;
      display: flex;
      align-items: center;
      justify-content: space-between;
      background-color: #34192e;
    }
    .logo{
      color:#ff702a;
      font-weight: 500;
      font-size: 3.24rem;
      padding-left: 9%;
      text-decoration: none;
    }
    .navbar{
      display: flex;
      list-style:none;

    }
    .navbar a{
     text-decoration: none;
     color:#fff;
     font-size: 1.2rem;
     padding: 10px 20px;
     font-weight: 500;
  
    }
    .navbar a:hover{
      color: #ff702a;
      transition: 4s;
    }
    #menu-icon{
      font-size: 2rem;
      cursor: pointer;
      display: none;
    }
    section{
      padding: 70px 17%;
      display: flex;
    }
    .home-img img{
      max-width: 100%;
      width: 500PX;
      height: auto;
    }
    .home-text h1{
      font-size: 4rem;
      color:#ff702a;
      margin-left: 10%;
    }
    .home-text h2{
      font-size:2.25rem;
      margin: 1rem 2rem;
    }
    .btn{
      display: inline-block;
      padding: 10px 30px;
      background-color:#ff702a;
      color: #fff;
      border-radius: 0.5rem;
      margin-left: 10%;
    }
    .btn:hover{
      transform: scale(1.2) transLateY(10px);
      transition: 4s;
    }
    .about{
      display: grid;
      grid-template-columns: repeat(2, 2fr);
      grid-gap: 1.5rem;
      text-align:center;
    }
    .about-img img{
      max-width: 100%;
      width: 480PX;
      height: auto;
    }
    .about-text span{
      color:#ff702a;
      font-weight: 600;
    }
    .about-text h2{
      font-size:2.25rem;
    }
    .about-text p{
      font-size: 0.8rem 0 1.8rem;
      line-height: 1.7rem;
    }
     .heading{
      align-items: center;
    }
    .heading span{
      color: #ff702a;
      font-weight: 600;
    }
    .heading h2{
      color: #ff702a;
      font-size: 2.25rem;
    }
    
.slider-bottom{
   width:1300px;
    float:left;}
.slider-bottom-parts{
  width:350px;
  float:left;
  /* padding:15px px; */
  background:#3a2636;
  border-right:2px #FFF solid;}
.slider-bottom-parts-h3{ color:#FFF; padding:20px 0px 10px; text-align:center; font-size:20px;}
.slider-bottom-parts-p{ color:#FFF; line-height:26px; font-size:14px; text-align:center;}

    .service{
      text-align: center;
    }
    .service-container{
      display: flex;
      justify-content: space-around;
      align-items: center;
    }
    .service-container{
      display: grid;
      grid-template-columns: repeat(auto, fit, (minmax 240px, auto));
      grid-gap: 1.5rem;
      align-items: center;
      display: flex;
      justify-content: space-between;
    }
    .s-box{
      text-align: center;
      padding: 20px 30px;
    }
    .s-box img{
      width: 90px;
    }
    .s-box h3{
      padding: 4px 0 10px;
      color:#ff702a;
      font-size: 1.2rem;
    }
    .s-box p{
      line-height: 1.7rem;
    }
    .cta{
      background-color: #feeee7;
      /* padding: 70px 0; */
      align-items: center;
      justify-content: center;
      display: inline-block;
      width: 66%;
      margin-right: 30px;      
      border-radius: 10px;
    }
    .cta h2{
      text-align: center;
      font-size: 2rem;
      color: #2e1c2a;
      margin-bottom: 30px;
      justify-content: center;
    }
     button{
     margin-right: 50%;
      position: relative;
      margin: 20px 10px;
      padding: 10px 10px;
      background-color: #ff702a;
      color: #feeee7;
      border-radius: 10px;

     }
    .main{
      display: flex;
      flex-wrap: wrap;
    }
    .footer{
      padding: 17px;
    }
    .foot-panel{
            /* background-color:rgb(65, 59, 59); */
            color: white;
            height: 50px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 1rem;
            border-radius: 10px;
         }
         .foot-panel2{
            background-color:rgb(49, 48, 48);
            color: white;
            height: 300px;
            display: flex;
            justify-content: space-evenly;
         }
         ul{
            margin-top: 25px;
         }
         ul a {
            display: block;
            font-size: 1rem;
            margin-top: 15px;
            color: #dddddd;
         }
    @media screen and (width: 480px) {
    /* and (max-device-width: 400px) { */
            body{
                background-color: rgb(22, 208, 34);
                box{
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      background: #8c2f06;
      /* width: 60px; */
            }}}
             
            @media screen and (min-device-width: 500px) and (max-device-width: 768px) {
            body{
              font-size: -50%;
                background-color: rgb(224, 15, 179);
               
            }}

            @media screen and (width: 1024px){ 
            body{
                background-color: rgb(22, 72, 208);
               
            }}
    
   
  </style>
</head>
<body>
  <div class="coffe9">
  <header>
    <a href="#" class="logo">Coffe-9</a>
    <div class="bx bx-menu" id="menu-icon"></div>
    <ul class="navbar">
       <li><a href="#Home">Home</a></li>
       <li><a href="#About us">About us</a></li>
       <li><a href="#Menu">Menu</a></li>
       <li><a href="#Service">Service</a></li>
       <li><a href="#content">Contact</a></li>
    </ul>
  </header>
  <section class="home" id="home">
    <div class="home-text">
      <h1>100% Pure Healthy</h1>
      <h2>Food the<br> most precious things</h2>
      <a href="#" class="btn">Today's menu</a>
    </div>
    <div class="home-img">
      <img src="home.png">
    </div>
  </section>
  <section class="about" id="about">
    <div class="about-img">
      <img src="about.png">
    </div>
    <div class="about-text">
      <span>About us</span>
      <h2>We speak the good <br> food language</h2>
      <p>A café is a type of restaurant which typically serves coffee and tea, in addition to light refreshments such as baked goods or snacks. The term "café" comes ...</p>
      <a href="#" class="btn">Learn more</a>
    </div>
  </section>
  <!-- menu-------- -->
  <section class="menu" id="menu">
    <div class="heading">
<div class="slider-bottom">
	<div class="slider-bottom-parts">
    	<div align="center"><img src="food1.png" width="300" /></div>
        <div class="slider-bottom-parts-h3">Burger</div>
        <div class="slider-bottom-parts-p">
          $ 300.00
        </div>
    </div>
    <div class="slider-bottom-parts">
    	<div align="center"><img src="food2.png" width="300" /></div>
        <div class="slider-bottom-parts-h3">Burger special</div>
        <div class="slider-bottom-parts-p">
          $ 400.00
        </div>
    </div>
    <div class="slider-bottom-parts" style="border-right:none;">
    	<div align="center"><img src="food3.png" width="300" /></div>
        <div class="slider-bottom-parts-h3">Fry Chicken</div>
        <div class="slider-bottom-parts-p">
          $ 500.00
        </div>
    </div>
</div>


  </section>
  <section class="service" id="service">
    <div class="head">
      <span>Service</span>
      <h2>We provide the best quality food</h2>
      <div class="service-container">
        <div class="s-box">
          <img src="s1.png">
          <h3>Order</h3>
          <p>to use your position of authority to tell somebody to do something or to say that something must happen.</p>
        </div>
        <div class="s-box">
          <img src="s2.png">
          <h3>Shipping</h3>
          <p>Retail food delivery is a courier service in which a restaurant, store, or independent food-delivery company delivers food to a customer..</p>
        </div>
        <div class="s-box">
          <img src="s3.png">
          <h3>Delivered</h3>
          <p>Once the order reaches your restaurant, you can directly hand it over to your delivery executive, and save a lot of time. The time is taken for a particular .
        </div>
      </div>
    </div>
  </section>
  <section class="cta">
    <h2>We make quality food<br> Everday <br>
    <button>Let's take</button></h2>
  </section>
  <footer>
        <div class="foot-panel">
          Contact
      </div>
      <div class="foot-panel2">
          <ul>          
            <p>COMPANY</p>
            <a>Careers</a>
            <a>FAQ</a>
            <a>Newsroom</a>
          </ul>
          <ul>          
              <p>CAFES</p>
              <a>Coonoor</a>
              <a>Bengaluru</a>
              <a>Delhi</a>
              <a>Pune</a>
              <a>Mumbai</a>
              <a>Hyderabad</a>
            </ul>
            <ul>          
              <p>POLICIES</p>
              <a>Terms & Conditions</a>
              <a>Privacy Policy</a>
              <a>Shipping</a>
              <a>Returns & Cancellations</a>
            </ul>
            <ul>          
              <p>CONTACT</p>
              <a>Ground & 1st Floor,<br> Nitesh Lexington Avenue,<br>
                # 72 Brigade Road,<br> Bengaluru 560001</a>
              <a> +91 80 47108111 <br>
                orders@thirdwavecoffee.in</a>
              <a>Your Orders</a>
              <a>Help</a>
            </ul>
      </div>
      </div>
    </footer>
    </div>
  </section>
</div>
</body>
</html>
