<?php include "config.php"; ?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>sweet</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
   <header>
    <nav class="navbar">
            <a href="#"class="nav-logo">
        <h2 class="logo-text">🧇The Sweet Corner</h2>
    
    
           </a>
           <ul class="nav-menu">

        <li class="nav-item">
            <a href="index.php"class="nav-link">Home</a>

        </li>
        <li class="nav-item">
            <a href="aboutus.php"class="nav-link">About Us</a>

        </li>
        <li class="nav-item">
            <a href="menu.php"class="nav-link">Menu</a>

        </li>
        <li class="nav-item">
            <a href="Reviews.php"class="nav-link">Reviews</a>

        </li>
        <li class="nav-item">
            <a href="contactus.php"class="nav-link">contact us
</a>

  

         </ul>   
        
 

    </nav>
   </header> 



  

 

<section class="reviews-container">

    <!-- Review 1 -->
    <div class="review-card">
        <div class="review-header">
            <img src="images/photo_2025-12-26_13-03-38.jpg" alt="user">
            <div>
                <h3>Teima B.</h3>
                <div class="stars">★★★★★</div>
            </div>
        </div>
        <p>Amazing coffee and very tasty desserts. Highly recommended!</p>
    </div>

    <!-- Review 2 -->
    <div class="review-card">
        <div class="review-header">
            <img src="images/photo_2025-12-26_13-07-32.jpg" alt="user">
            <div>
                <h3>Hemza Z.</h3>
                <div class="stars">★★★★☆</div>
            </div>
        </div>
        <p>Nice place, good prices and friendly staff.</p>
    </div>

    <!-- Review 3 -->
    <div class="review-card">
        <div class="review-header">
            <img src="images/photo_2025-12-26_13-07-27.jpg" alt="user">
            <div>
                <h3>Rouia R.</h3>
                <div class="stars">★★★★★</div>
            </div>
        </div>
        <p>The best sweet shop in town! Everything is fresh.</p>
    </div>

    <!-- Review 4 -->
    <div class="review-card">
        <div class="review-header">
            <img src="images/photo_2025-12-26_13-07-30.jpg" alt="user">
            <div>
                <h3>Saber B.</h3>
                <div class="stars">★★★★☆</div>
            </div>
        </div>
        <p>Perfect place to chill with friends.</p>
    </div>

    <!-- Review 5 -->
    <div class="review-card">
        <div class="review-header">
            <img src="images/photo_2025-12-26_13-07-30 (2).jpg" alt="user">
            <div>
                <h3>Hana B.</h3>
                <div class="stars">★★★★★</div>
            </div>
        </div>
        <p>Love the crepes and iced coffee 😍</p>
    </div>

    <!-- Review 6 -->
    <div class="review-card">
        <div class="review-header">
            <img src="images/photo_2025-12-26_13-07-31.jpg" alt="user">
            <div>
                <h3>Walid B.</h3>
                <div class="stars">★★★★☆</div>
            </div>
        </div>
        <p>Clean place and fast service.</p>
    </div>

  

  

</section>


   
<footer class="footer">
  <div class="footer-box">
    <h3>The Sweet Corner</h3>
    <ul>
      <li>Home</li>
      <li>About Us</li>
      <li>Menu</li>
      <li>Reviews</li>
      <li>Contact Us</li>
    </ul>
  </div>

  <div class="footer-box">
    <h3>Contact</h3>
    <p>Email: thesweetcorner21@gmail.com</p>
    <p>Phone: 05 xx xx xx xx</p>
    <p>Address: Rue 21 xxx, Skikda</p>
  </div>

  <div class="footer-box">
    <h3>Suivez-nous</h3>
    <ul>
      <li>Facebook</li>
      <li>Instagram</li>
    </ul>
  </div>
  
</footer>
 <div class="footer-bottom">
    <p><b>© 2026 My Shop. The Sweet Corner.</b></p> </div>

 

 
.reviews-container {
    max-width: 1100px;
    margin: 60px auto;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    padding: 0 20px;
}


.reviews-container {
    max-width: 1100px;
    margin: 60px auto;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 30px;
    padding: 0 20px;
}


.review-card {
    background: white;
    padding: 20px;
    border-radius: 15px;
    transition: transform 0.3s;
}

.review-card:hover {
    transform: translateY(-5px);
}


.review-header {
    display: flex;
    align-items: center;
    gap: 15px;
    margin-bottom: 15px;
}

.review-header img {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    object-fit: cover;
    border: 2px solid  rgb(116, 39, 39);
}

.review-header h3 {
    color:  rgb(116, 39, 39);
    margin-bottom: 5px;
}

.stars {
    color:  rgb(237, 173, 25);
    font-size: 16px;
}


.review-card p {
    font-size: 14px;
    line-height: 1.6;
    color:black;
}  

</body>
</html>
