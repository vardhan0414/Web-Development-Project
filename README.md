# Web-Development-Project
In this project I designed my own website using HTML, CSS, JavaScript
In this article, we Create A Restaurant Website Using HTML And CSS With complete code. We use Html, Css, And Javascript for this amazing Restaurant Website project.
We start with our html code for the Restaurant Website then we write css and javascript code for this Restaurant Website
we add javascript for smooth scrolling in our website otherwise javascript is optional for this project.

Code Begins!

HTML CODE
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <title>Chinese Restaurant</title>
   <!-- font awesome cdn link  -->
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
   <link rel="stylesheet" href="https://unpkg.com/swiper@7/swiper-bundle.min.css" />
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightgallery-js/1.4.0/css/lightgallery.min.css">
   <!-- custom css file link  -->
   <link rel="stylesheet" href="css/style.css">


</head>
<body>
<!-- header section starts     -->
<section class="header">
   <a href="#" class="logo"> <i class="fas fa-utensils"></i> food. </a>
   <nav class="navbar">
      <a href="#home">home</a>
      <a href="#about">about</a>
      <a href="#food">food</a>
      <a href="#gallery">gallery</a>
      <a href="#menu">menu</a>
      <a href="#order">order</a>
      <a href="#blogs">blogs</a>
   </nav>
   <div id="menu-btn" class="fas fa-bars"></div>
</section>
<!-- header section ends    -->



<!-- home section starts  -->
<marquee><p style="font-size:20px">*YOU MUST CONNECT TO INTERNET TO VIEW THIS WEB PAGE *</p></marquee>
<section class="home" id="home">
   <div class="swiper home-slider">
      <div class="swiper-wrapper">
         <div class="swiper-slide slide" style="background: url(images/home-slide-1.jpg) no-repeat;">
            <div class="content">
               <span>outstanding food</span>
               <h3>delicious cooking</h3>
               <a href="#" class="btn">get started</a>
            </div>
         </div>
         <div class="swiper-slide slide" style="background: url(images/home-slide-2.jpg) no-repeat;">
            <div class="content">
               <span>outstanding food</span>
               <h3>morning moment</h3>
               <a href="#" class="btn">get started</a>
            </div>
         </div>
         <div class="swiper-slide slide" style="background: url(images/home-slide-3.jpg) no-repeat;">
            <div class="content">
               <span>outstanding food</span>
               <h3>authentic kitchen</h3>
               <a href="#" class="btn">get started</a>
            </div>
         </div>
      </div>
      <div class="swiper-button-next"></div>
      <div class="swiper-button-prev"></div>
   </div>
</section>
<!-- home section ends -->




<!-- about section starts  -->
<section class="about" id="about">
   <div class="image">
      <img src="images/about-img.png" alt="">
   </div>
   <div class="content">
      <h3 class="title">welcome to our Chinese Restaurant</h3>
      <p>A well-run Restaurant is like a winning baseball team.It makes the most of every crew member's talent and
         takes advantage of every split-second oppurtunity to speed up service.</p>
      <a  class="btn">read more</a>
      <div class="icons-container">
         <div class="icons">
            <img src="images/about-icon-1.png" alt="">
            <h3>quality food</h3>
         </div>
         <div class="icons">
            <img src="images/about-icon-2.png" alt="">
            <h3>food & drinks</h3>
         </div>
         <div class="icons">
            <img src="images/about-icon-3.png" alt="">
            <h3>expert chefs</h3>
         </div>
      </div>
   </div>
</section>
<!-- about section ends -->




<!-- food section starts  -->
<section class="food" id="food">
   <div class="heading">  
      <span>popular dishes</span>
      <h3>our delicious food</h3>
   </div>
   <div class="swiper food-slider">
      <div class="swiper-wrapper">
         <div class="swiper-slide slide" data-name="food-1">
            <img src="images/food-img-1.png" alt="">
            <h3>Tortilla Española</h3>
            <div class="price">$49.99</div>
         </div>
         <div class="swiper-slide slide" data-name="food-2">
            <img src="images/food-img-2.png" alt="">
            <h3>Gambas al ajillo</h3>
            <div class="price">$59.99</div>
         </div>
         <div class="swiper-slide slide" data-name="food-3">
            <img src="images/food-img-3.png" alt="">
            <h3>Pollo al ajillo</h3>
            <div class="price">$69.99</div>
         </div>
         <div class="swiper-slide slide" data-name="food-4">
            <img src="images/food-img-4.png" alt="">
            <h3>Paella</h3>
            <div class="price">$79.99</div>
         </div>
         <div class="swiper-slide slide" data-name="food-5">
            <img src="images/food-img-5.png" alt="">
            <h3>Gazpacho</h3>
            <div class="price">$89.99</div>
         </div>
      </div>
      <div class="swiper-pagination"></div>
   </div>
</section>
<!-- food section ends -->



<!-- food preview section starts  -->
<section class="food-preview-container">
   <div id="close-preview" class="fas fa-times"></div>
   <div class="food-preview" data-target="food-1">
      <img src="images/food-img-1.png" alt="">
      <h3>Tortilla Española</h3>
      <div class="stars">
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
      </div>
      <p>Eggs, potatoes, onions… that’s it – and some purists even consider that adding onion is a gastronomic crime of
         the highest order. The Spanish omelette is so much more than the sum of its parts. The potatoes and onions are
         slow fried in olive oil then mixed with the beaten eggs for the flavours to mix before cooking. Add chorizo,
         ham, spinach, courgettes or whatever you have to hand to make a tasty meal out of next to nothing.</p>
      <div class="price">$49.99</div>
      <a  class="btn">buy now</a>
   </div>
   <div class="food-preview" data-target="food-2">
      <img src="images/food-img-2.png" alt="">
      <h3>Gambas al ajillo</h3>
      <div class="stars">
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
      </div>
      <p>You walk into a tapas bar, the barman is handing a customer an earthenware dish of sizzling prawns,
         the tantalising aroma hits your nostrils and you just have to order some too. To recreate it at home,
         just fry some sliced garlic and green chilli in olive oil, throw in the prawns for a couple of minutes
         and add some parsley. Couldn’t be simpler, couldn’t be tastier.</p>
      <div class="price">$59.99</div>
      <a  class="btn">buy now</a>
   </div>
   <div class="food-preview" data-target="food-3">
      <img src="images/food-img-3.png" alt="">
      <h3>Pollo al ajillo</h3>
      <div class="stars">
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
      </div>
      <p>Any Spaniard will tell you that the best garlic chicken ever is the one their grandmother makes.
         And of course they are right. Unpeeled cloves of garlic are fried in olive oil to flavour it, then taken out
         before adding pieces of chicken. When that's cooked, the garlic goes back in with some rosemary, thyme and some
         dry sherry or white wine. But there is no definitive recipe for this much-loved dish.</p>
      <div class="price">$69.99</div>
      <a  class="btn">buy now</a>
   </div>
   <div class="food-preview" data-target="food-4">
      <img src="images/food-img-4.png" alt="">
      <h3>Paella</h3>
      <div class="stars">
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
      </div>
      <p>In the Valencia region, they claim you can eat a different rice dish every day of the year, but let’s stick
         with the most traditional version for now. Ingredients for paella Valenciana include chicken or rabbit,
         saffron, runner beans and butter beans. But the all-important element is the rice, ideally the bomba or
         Calasparra varieties grown on Spain’s east coast, which are particularly good for absorbing all the flavours.</p>
      <div class="price">$79.99</div>
      <a  class="btn">buy now</a>
   </div>
   <div class="food-preview" data-target="food-5">
      <img src="images/food-img-5.png" alt="">
      <h3>Gazpacho</h3>
      <div class="stars">
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
         <i class="fas fa-star"></i>
      </div>
      <p>The reddest, ripest tomatoes, olive oil, garlic, bread, peppers and cucumber are blended until silky smooth,
         then chilled and poured into bowls or glasses. So delicious, so refreshing. In Andalucía in southern Spain,
         people have it every day in summer and there is always a jug on the counter in tapas bars. Also try salmorejo
         from Córdoba, a thicker version that is often served with pieces of Ibérico ham on the top.</p>
      <div class="price">$89.99</div>
      <a  class="btn">buy now</a>
   </div>
</section>
<!-- food preview section ends -->



<!-- gallery section starts  -->
<section class="gallery" id="gallery">
   <div class="heading">
      <span>our gallery</span>
      <h3>our untold stories</h3>
   </div>
   <div class="gallery-container">
      <a href="images/food-galler-img-1.jpg" class="box">
         <img src="images/food-galler-img-1.jpg" alt="">
         <div class="icon"> <i class="fas fa-plus"></i> </div>
      </a>
      <a href="images/food-galler-img-2.jpg" class="box">
         <img src="images/food-galler-img-2.jpg" alt="">
         <div class="icon"> <i class="fas fa-plus"></i> </div>
      </a>
      <a href="images/food-galler-img-3.jpg" class="box">
         <img src="images/food-galler-img-3.jpg" alt="">
         <div class="icon"> <i class="fas fa-plus"></i> </div>
      </a>
      <a href="images/food-galler-img-4.jpg" class="box">
         <img src="images/food-galler-img-4.jpg" alt="">
         <div class="icon"> <i class="fas fa-plus"></i> </div>
      </a>
      <a href="images/food-galler-img-5.jpg" class="box">
         <img src="images/food-galler-img-5.jpg" alt="">
         <div class="icon"> <i class="fas fa-plus"></i> </div>
      </a>
      <a href="images/food-galler-img-6.jpg" class="box">
         <img src="images/food-galler-img-6.jpg" alt="">
         <div class="icon"> <i class="fas fa-plus"></i> </div>
      </a>
   </div>
</section>
<!-- gallery section ends -->



<!-- menu section starts  -->
<section class="menu" id="menu">
   <div class="heading">
      <span>our menu</span>
      <h3>our popular dishes</h3>
   </div>
   <div class="swiper menu-slider">
      <div class="swiper-wrapper">
         <div class="swiper-slide slide">
            <h3 class="title">breakfast</h3>
            <div class="box-container">
               <div class="box">
                  <div class="info">
                     <h3>Pincho de tortilla.</h3>
                     <p>Morning Beast</p>
                  </div>
                  <div class="price">$5.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Huevos rotos con chorizo.</h3>
                     <p>Breakfast</p>
                  </div>
                  <div class="price">$34.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Freshly squeezed orange juice.</h3>
                     <p>Prevents Energy</p>
                  </div>
                  <div class="price">$6.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Tostada con tomate</h3>
                     <p>Includes Onion</p>
                  </div>
                  <div class="price">$6.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Café con leche.</h3>
                     <p>Cappuccino </p>
                  </div>
                  <div class="price">$9.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>aceite</h3>
                     <p>Juicy</p>
                  </div>
                  <div class="price">$9.99</div>
               </div>
            </div>
         </div>
         <div class="swiper-slide slide">
            <h3 class="title">lunch</h3>
            <div class="box-container">
               <div class="box">
                  <div class="info">
                     <h3>Patatas bravas</h3>
                     <p>Specially from China</p>
                  </div>
                  <div class="price">$22.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Pisto</h3>
                     <p>Delicious!</p>
                  </div>
                  <div class="price">$69.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Turrón</h3>
                     <p>Sweet</p>
                  </div>
                  <div class="price">$39.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Urricas</h3>
                     <p>Appricot</p>
                  </div>
                  <div class="price">$49.99</div>
               </div>
            </div>
         </div>
         <div class="swiper-slide slide">
            <h3 class="title">dinner</h3>
            <div class="box-container">
               <div class="box">
                  <div class="info">
                     <h3>Okonomiyaki</h3>
                     <p>Specially from Japan</p>
                  </div>
                  <div class="price">$99.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Shabu Shabu and Sukiyaki.</h3>
                     <p>Special for Dinner</p>
                  </div>
                  <div class="price">$59.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Yakiniku.</h3>
                     <p>Lorem ipsum</p>
                  </div>
                  <div class="price">$19.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Teppanyaki.</h3>
                     <p> dolor sit amet </p>
                  </div>
                  <div class="price">$79.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Fugu</h3>
                     <p>Energetic</p>
                  </div>
                  <div class="price">$49.99</div>
               </div>
            </div>
         </div>
         <div class="swiper-slide slide">
            <h3 class="title">drinks</h3>
            <div class="box-container">
               <div class="box">
                  <div class="info">
                     <h3>Fanta Lemon Soda.</h3>
                     <p>Cold drink</p>
                  </div>
                  <div class="price">$9.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Lychee Fanta.</h3>
                     <p>Cold drink</p>
                  </div>
                  <div class="price">$6.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Tropical Yogurt Fanta</h3>
                     <p>Cold drink</p>
                  </div>
                  <div class="price">$4.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Sake (Nihonshu)</h3>
                     <p>Cold drink</p>
                  </div>
                  <div class="price">$2.99</div>
               </div>
            </div>
         </div>
         <div class="swiper-slide slide">
            <h3 class="title">dessert</h3>
            <div class="box-container">
               <div class="box">
                  <div class="info">
                     <h3>Marbled tres leches cake</h3>
                     <p>Cake</p>
                  </div>
                  <div class="price">$9.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>Flan</h3>
                     <p>Best of Menu</p>
                  </div>
                  <div class="price">$9.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>macaroons</h3>
                     <p>sliced cheese</p>
                  </div>
                  <div class="price">$49.99</div>
               </div>
               <div class="box">
                  <div class="info">
                     <h3>CHURROS</h3>
                     <p>Chips</p>
                  </div>
                  <div class="price">$29.99</div>
               </div>
            </div>
         </div>
      </div>
      <div class="swiper-pagination"></div>
   </div>
</section>
<!-- menu section ends -->



<!-- order section starts  -->
<section class="order" id="order">
   <div class="heading">
      <span>order now</span>
      <h3>fast home delivery</h3>
   </div>
   <form action="">
      <div class="box-container">
         <div class="box">
            <div class="inputBox">
               <span>full name</span>
               <input type="text" placeholder="enter your name">
            </div>
            <div class="inputBox">
               <span>food name</span>
               <input type="text" placeholder="food you want">
            </div>
            <div class="inputBox">
               <span>order details</span>
               <input type="text" placeholder="specifics with food">
            </div>
            <div class="inputBox">
               <span>your address</span>
               <textarea name="" placeholder="enter your address" id="" cols="30" rows="10"></textarea>
            </div>
         </div>
         <div class="box">
            <div class="inputBox">
               <span>number</span>
               <input type="number" placeholder="enter your number">
            </div>
            <div class="inputBox">
               <span>how much</span>
               <input type="number" placeholder="how many you want">
            </div>
            <div class="inputBox">
               <span>when you want</span>
               <input type="datetime-local">
            </div>
         </div>
      </div>
      <input type="submit" value="order now" class="btn">
   </form>
</section>
<!-- order section ends -->


<!-- blogs section starts  -->
<section class="blogs" id="blogs">
   <div class="heading">
      <span>our blogs</span>
      <h3>our latest posts</h3>
   </div>
   <div class="swiper blogs-slider">
      <div class="swiper-wrapper">
         <div class="swiper-slide slide">
            <div class="image">
               <img src="images/blog-img-1.jpg" alt="">
               <span>burger</span>
            </div>
            <div class="content">
               <div class="icon">
                  <a > <i class="fas fa-calendar"></i> 21st may, 2022 </a>
                  <a > <i class="fas fa-user"></i> by admin </a>
               </div>
               <a  class="title">Burger</a>
               <p>Made from minced beef, pork or a blend of the two mixed with minced onions, egg, breadcrumbs and
                  spices.</p>
            </div>
         </div>
         <div class="swiper-slide slide">
            <div class="image">
               <img src="images/blog-img-2.jpg" alt="">
               <span>sandwich</span>
            </div>
            <div class="content">
               <div class="icon">
                  <a > <i class="fas fa-calendar"></i> 21st may, 2022 </a>
                  <a> <i class="fas fa-user"></i> by admin </a>
               </div>
               <a  class="title">Sandwich</a>
               <p>A sandwich is a food typically consisting of vegetables, sliced cheese or meat, placed on or between
                  slices of bread</p>
            </div>
         </div>
         <div class="swiper-slide slide">
            <div class="image">
               <img src="images/blog-img-3.jpg" alt="">
               <span>chicken</span>
            </div>
            <div class="content">
               <div class="icon">
                  <a> <i class="fas fa-calendar"></i> 21st may, 2022 </a>
                  <a > <i class="fas fa-user"></i> by admin </a>
               </div>
               <a class="title">Chicken</a>
               <p>Chicken is the most common type of poultry in the world. Owing to the relative ease and low cost of
                  raising chickens</p>
            </div>
         </div>
         <div class="swiper-slide slide">
            <div class="image">
               <img src="images/blog-img-4.jpg" alt="">
               <span>ice-cream</span>
            </div>
            <div class="content">
               <div class="icon">
                  <a > <i class="fas fa-calendar"></i> 21st may, 2022 </a>
                  <a> <i class="fas fa-user"></i> by admin </a>
               </div>
               <a  class="title">ice-cream</a>
               <p>Cool!</p>
            </div>
         </div>
         <div class="swiper-slide slide">
            <div class="image">
               <img src="images/blog-img-5.jpg" alt="">
               <span>pizza</span>
            </div>
            <div class="content">
               <div class="icon">
                  <a > <i class="fas fa-calendar"></i> 21st may, 2022 </a>
                  <a> <i class="fas fa-user"></i> by admin </a>
               </div>
               <a class="title">Pizza</a>
               <p>Classic-Hand Tossed</p>
            </div>
         </div>
         <div class="swiper-slide slide">
            <div class="image">
               <img src="images/blog-img-6.jpg" alt="">
               <span>coffee</span>
            </div>
            <div class="content">
               <div class="icon">
                  <a > <i class="fas fa-calendar"></i> 21st may, 2022 </a>
                  <a > <i class="fas fa-user"></i> by admin </a>
               </div>
               <a  class="title">Coffee</a>
               <p>Coffee is a drink prepared from roasted coffee beans. Darkly colored, bitter, and slightly acidic,
               </p>
            </div>
         </div>
      </div>
      <div class="swiper-pagination"></div>
   </div>
</section>
<!-- blogs section ends -->



<!-- footer section starts  -->
<section class="footer">
   <div class="icons-container">
      <div class="icons">
         <i class="fas fa-clock"></i>
         <h3>opening hours</h3>
         <p>07:00am to 10:00pm</p>
      </div>
      <div class="icons">
         <i class="fas fa-phone"></i>
         <h3>phone</h3>
         <p>+91-9347809552</p>
         <p>+91-8309597359</p>
      </div>
      <div class="icons">
         <i class="fas fa-envelope"></i>
         <h3>email</h3>
         <p>ankith22@gmail.com</p>
         <p>vally89@gmail.com</p>
      </div>
      <div class="icons">
         <i class="fas fa-map"></i>
         <h3>address</h3>
         <p>Phagwara ,India-144401</p>
      </div>
   </div>
   <div class="share">
      <a href="https://www.facebook.com/login/" target="_blank" class="fab fa-facebook-f"></a>
      <a href="https://twitter.com/i/flow/login" target="_blank" class="fab fa-twitter"></a>
      <a href="https://www.instagram.com/ankith_ankith_2004/" target="_blank" class="fab fa-instagram"></a>
      <a href="https://www.linkedin.com/in/vardhan0811/" target="_blank" class="fab fa-linkedin"></a>
   </div>
   <div class="credit"> created by <span>Vardhan,Ankith and Vally</span> | all rights reserved! | From K22FR</div>
</section>
<!-- footer section ends  -->




<!-- script -->
<script src="https://unpkg.com/swiper@7/swiper-bundle.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightgallery-js/1.4.0/js/lightgallery.min.js"></script>
<!-- custom js file link  -->
<script src="js/script.js"></script>
<script>
   lightGallery(document.querySelector('.gallery .gallery-container'));
</script>


</body>
</html>



CSS CODE BEGINS !!

:root{
   --peru:#cd9452;
   --black:#222;
   --white:#fff;
   --light-black:#666;
   --light-white:#ccc;
   --light-bg:#f5f5f5;
   --dark-bg:rgba(0,0,0,.7);
   --border:.1rem solid #aaa;
   --box-shadow:0 .5rem 1rem rgba(0,0,0,.1);
}



*{
   font-family: 'Dosis', sans-serif;
   margin:0; padding:0;
   box-sizing: border-box;
   outline: none; border:none;
   text-decoration: none;
   transition: all 0.4s cubic-bezier(.43,1.1,.62,1.08);
   text-transform: capitalize;
}

* > img{
   user-select: none;
   pointer-events: none;
}

html{
   font-size: 62.5%;
   overflow-x: hidden;
   scroll-behavior: smooth;
   scroll-padding-top: 6rem;
}

html::-webkit-scrollbar{
   width: 1rem;
}

html::-webkit-scrollbar-track{
   background-color: var(--white);
}

html::-webkit-scrollbar-thumb{
   background-color: var(--peru);
}

section{
   padding:5rem 10%;
}

.heading{
   text-align: center;
   margin-bottom: 3rem;
}

.heading span{
   font-size: 2.5rem;
   color:var(--peru);
}

.heading h3{
   font-size: 4.5rem;
   color:var(--black);
}

.btn{
   margin-top: 1rem;
   display: inline-block;
   background: var(--peru);
   color:var(--white);
   font-size: 2rem;
   cursor: pointer;
   padding:1rem 3rem;
}

.btn:hover{
   letter-spacing: .2rem;
}

.header{
   padding-top: 2rem;
   padding-bottom: 2rem;
   display: flex;
   align-items: center;
   justify-content: space-between;
   box-shadow: var(--box-shadow);
   position: sticky;
   top:0; left:0; right: 0;
   background: var(--white);
   z-index: 1000;
}

.header .logo{
   font-size: 2.5rem;
   font-weight: bolder;
   color:var(--black);
}

.header .logo i{
   color:var(--peru);
   padding-right: .5rem;
}

.header .navbar a{
   font-size: 2rem;
   margin-left: 2rem;
   color:var(--light-black);
}

.header .navbar a:hover{
   color:var(--peru);
}

#menu-btn{
   font-size: 2.5rem;
   cursor: pointer;
   color:var(--black);
   display: none;
}

@keyframes fadeIn {
   0%{
      transform: translateY(-4rem) scale(0);
      opacity: 0;
   }
}

.home{
   padding:0;
   background: var(--black);
}

.home .slide{
   min-height: 100vh;
   background-size: cover !important;
   background-position: center !important;
   position: relative;
   z-index: 0;
   display: flex;
   align-items: center;
   justify-content: center;
}

.home .slide::before{
   content: '';
   position: absolute;
   top:0; left:0;
   height: 100%;
   width: 100%;
   background: var(--dark-bg);
   z-index: -1;
}

.home .slide .content{
   text-align: center;
   width: 70rem;
   display: none;
}

.home .slide .content span{
   font-size: 3rem;
   display: block;
   padding-bottom: .5rem;
   color:var(--light-white);
   animation:fadeIn 0.4s cubic-bezier(.54,1.3,.63,1.34) .2s backwards;
}

.home .slide .content h3{
   font-size: 8vw;
   text-transform: uppercase;
   color:var(--white);
   text-shadow: 0 .5rem 1rem rgba(0,0,0,.7);
   line-height: 1;
   padding:2rem 0;
   animation:fadeIn 0.4s cubic-bezier(.54,1.3,.63,1.34) .4s backwards;
}

.home .slide .content .btn{
   animation:fadeIn 0.4s cubic-bezier(.54,1.3,.63,1.34) .6s backwards;
}

.home .swiper-slide-active .content{
   display: inline-block;
}

.swiper-button-next,
.swiper-button-prev{
   height: 5rem;
   width: 5rem;
   line-height: 5rem;
   background: var(--white);
   color:var(--black);
}

.swiper-button-next:hover,
.swiper-button-prev:hover{
   background: var(--peru);
   color:var(--white);
}

.swiper-button-next::after,
.swiper-button-prev::after{
   font-size: 2rem;
}

.about{
   display: flex;
   align-items: center;
   flex-wrap: wrap;
   gap:2rem;
}

.about .image{
   flex:1 1 41rem;
}

.about .image img{
   width: 100%;
}

.about .content{
   flex:1 1 41rem;
}

.about .content .title{
   font-size: 4rem;
   color:var(--black);
}

.about .content p{
   font-size: 1.7rem;
   color:var(--light-black);
   padding:1rem 0;
   line-height: 2;
}

.about .content .icons-container{
   display: flex;
   flex-wrap: wrap;
   gap:2rem;
   margin-top: 3rem;
}

.about .content .icons-container .icons{
   flex:1 1 16rem;
   text-align: center;
   background: var(--light-bg);
   padding:3rem 2rem;
}

.about .content .icons-container .icons img{
   height: 5rem;
}

.about .content .icons-container .icons h3{
   padding-top: 1rem;
   font-size: 2rem;
   color:var(--light-black);
   font-weight: normal;
}

.food{
   background: var(--light-bg);
}

.food .slide{
   text-align: center;
   padding:4rem 2rem;
   border-radius: .5rem;
   transform: scale(.9);
   opacity: .5;
   margin-bottom: 4rem;
   cursor: pointer;
}

.swiper-pagination-bullet-active{
   background: var(--peru);
}

.swiper-horizontal>.swiper-pagination-bullets, .swiper-pagination-bullets.swiper-pagination-horizontal{
   bottom:0;
}

.food .swiper-slide-active{
   transform: scale(1);
   opacity: 1;
   background: var(--white);
   box-shadow: var(--box-shadow);
   border:var(--border);
}

.food .slide img{
   height: 25rem;
   margin-bottom: 1rem;
}

.food .slide h3{
   font-size: 2.5rem;
   padding:1rem 0;
   color:var(--black);
}

.food .slide .price{
   font-size: 2.5rem;
   color:var(--peru);
}

.food-preview-container{
   background: var(--dark-bg);
   position: fixed;
   top:0; left:0;
   height: 100%;
   width: 100%;
   z-index: 1100;
   display: none;
   align-items: center;
   justify-content: center;
}

.food-preview-container .food-preview{
   text-align: center;
   background: var(--white);
   padding:3rem 2rem;
   border-radius: .5rem;
   display: none;
   width: 35rem;
}

.food-preview-container .food-preview.active{
   display: inline-block;
   animation:fadeIn 0.4s cubic-bezier(.54,1.3,.63,1.34) backwards;
}

.food-preview-container .food-preview img{
   height: 25rem;
   margin-bottom: 1rem;
}

.food-preview-container .food-preview h3{
   padding:1rem 0;
   font-size: 2.5rem;
   color:var(--black);
}

.food-preview-container .food-preview .stars{
   margin-top: .5rem;
}

.food-preview-container .food-preview .stars i{
   font-size: 1.7rem;
   color:var(--peru);
}

.food-preview-container .food-preview p{
   font-size: 1.6rem;
   color:var(--light-black);
   padding:1rem 0;
   line-height: 2;
}

.food-preview-container .food-preview .price{
   font-size: 2.5rem;
   color:var(--black);
   margin-bottom: .5rem;
}

#close-preview{
   position: absolute;
   top:1.5rem; right:2.5rem;
   font-size: 6rem;
   cursor: pointer;
   color:var(--white);
}

#close-preview:hover{
   transform: rotate(90deg);
}

.gallery .gallery-container{
   display: grid;
   grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
   gap:2rem;
}

.gallery .gallery-container .box{
   height: 40rem;
   position: relative;
   overflow: hidden;
}

.gallery .gallery-container .box img{
   height: 100%;
   width: 100%;
   object-fit: cover;
}

.gallery .gallery-container .box .icon{
   display: none;
   align-items: center;
   justify-content: center;
   position: absolute;
   top:0; left:0;
   z-index: 10;
   height: 100%;
   width: 100%;
   background: var(--dark-bg);
}

.gallery .gallery-container .box .icon i{
   font-size: 6rem;
   color:var(--white);
}

.gallery .gallery-container .box:hover .icon{
   display: flex;
}

.menu{
   background: var(--light-bg);
}

.menu .slide .title{
   padding:1rem;
   font-size: 3rem;
   color:var(--white);
   background: var(--peru);
   margin-bottom: 3rem;
   text-align: center;
}

.menu .slide .box-container{
   display: flex;
   flex-wrap: wrap;
   gap:2rem;
   padding-bottom: 4rem;
}

.menu .slide .box-container .box{
   flex:1 1 41rem;
   background: var(--white);
   padding:2rem;
   box-shadow: var(--box-shadow);
   border:var(--border);
   display: flex;
   align-items: center;
   gap:1rem;
   justify-content: space-between;
}

.menu .slide .box-container .box h3{
   font-size: 2.5rem;
   color:var(--black);
   padding-bottom: .5rem;
}

.menu .slide .box-container .box p{
   font-size: 1.6rem;
   color:var(--light-black);
   line-height: 2;
}

.menu .slide .box-container .box .price{
   font-size: 2.5rem;
   color:var(--peru);
}

.menu .slide .box-container .box:hover{
   transform: scale(.9);
   cursor: pointer;
}

.order{
   background: var(--peru);
}

.order .heading span{
   color:var(--white);
}

.order .heading h3{
   color:var(--white);
}

.order form{
   padding:2rem;
   background: var(--white);
   box-shadow: var(--box-shadow);
}

.order form .box-container{
   display: flex;
   flex-wrap: wrap;
   gap:2rem;
}

.order form .box-container .box{
   flex:1 1 41rem;
}

.order form .box-container .box .inputBox input,
.order form .box-container .box .inputBox textarea{
   width: 100%;
   margin:1rem 0;
   padding:1.2rem 1.4rem;
   font-size: 1.7rem;
   color:var(--light-black);
   border:var(--border);
   text-transform: none;
}

.order form .box-container .box .inputBox input::placeholder,
.order form .box-container .box .inputBox textarea::placeholder{
   text-transform: capitalize;
}

.order form .box-container .box .inputBox input:focus,
.order form .box-container .box .inputBox textarea:focus{
   background: var(--black);
   color:var(--white);
}

.order form .box-container .box .inputBox input:focus::placeholder,
.order form .box-container .box .inputBox textarea:focus::placeholder{
   color:var(--light-white);
}

.order form .box-container .box .inputBox textarea{
   height: 20rem;
   resize: none;
}

.order form .box-container .box .inputBox .map{
   height: 20rem;
   width: 100%;
   margin:1rem 0;
}

.order form .box-container .box .inputBox span{
   color:var(--light-black);
   font-size: 2rem;
}

.blogs{
   background: var(--light-bg);
}

.blogs .slide .image{
   height: 25rem;
   overflow: hidden;
   position: relative;
}

.blogs .slide .image img{
   height: 100%;
   width: 100%;
   object-fit: cover;
}

.blogs .slide .image span{
   position: absolute;
   bottom: -10rem; left:50%;
   transform: translateX(-50%);
   padding:.5rem 1.5rem;
   font-size: 2rem;
   color:var(--white);
   background: var(--black);
   z-index: 10;
}

.blogs .slide:hover .image span{
   bottom: 1rem;
}

.blogs .slide:hover .image img{
   transform: scale(1.1);
}

.blogs .slide .content{
   padding:2rem;
   background: var(--white);
   box-shadow: var(--box-shadow);
   border:var(--border);
   margin-bottom: 4rem;
}

.blogs .slide .content .icon{
   display: flex;
   align-items: center;
   justify-content: space-between;
   margin-bottom: 2rem;
}

.blogs .slide .content .icon a{
   font-size: 1.5rem;
   color:var(--light-black);
}

.blogs .slide .content .icon a i{
   padding-right: .7rem;
   color:var(--peru);
}

.blogs .slide .content .icon a:hover{
   color:var(--peru);
}

.blogs .slide .content .title{
   font-size: 2.5rem;
   color:var(--black);
}

.blogs .slide .content .title:hover{
   text-decoration: underline;
}

.blogs .slide .content p{
   padding:1rem 0;
   line-height: 2;
   font-size: 1.6rem;
   color:var(--light-black);
}

.footer{
   text-align: center;
   /* padding-bottom: 10rem; */
}

.footer .icons-container{
   display: grid;
   grid-template-columns: repeat(auto-fit, minmax(25rem, 1fr));
   gap:2rem;
}

.footer .icons-container .icons{
   text-align: center;
   padding:3rem 2rem;
}

.footer .icons-container .icons i{
   height: 6rem;
   width: 6rem;
   border-radius: 50%;
   background: var(--peru);
   color:var(--white);
   margin-bottom: .5rem;
   line-height: 5.8rem;
   font-size: 2rem;
}

.footer .icons-container .icons h3{
   font-size: 2rem;
   color:var(--black);
   padding:1rem 0;
}

.footer .icons-container .icons p{
   line-height: 1.5;
   font-size: 1.7rem;
   color:var(--light-black);
   text-transform: none;
}

.footer .share{
   margin:2rem 0;
}

.footer .share a{
   height: 6rem;
   width: 6rem;
   line-height: 5.8rem;
   color:var(--white);
   background: var(--black);
   margin:0 .3rem;
   font-size: 2.5rem;
}  

.footer .share a:hover{
   background: var(--peru);
}

.footer .credit{
   padding-top: 2.5rem;
   margin-top: 3rem;
   border-top: var(--border);
   font-size: 2rem;
   color:var(--light-black);
}

.footer .credit span{
   color:var(--peru);
}




/* media queries  */

@media (max-width:1200px){

   section{
      padding:3rem 5%;
   }

}

@media (max-width:991px){

   section{
      padding:3rem 2rem;
   }

   html{
      font-size: 55%;
   }

   .home .slide .content h3{
      font-size: 15vw;
   }

}

@media (max-width:768px){

   #menu-btn{
      display: inline-block;
   }

   .fa-times{
      transform: rotate(180deg);
   }

   .header .navbar{
      position: absolute;
      top:99%; left:0; right:0;
      background-color: var(--white);
      border-top: var(--border);
      clip-path: polygon(0 0, 100% 0, 100% 0, 0 0);
   }

   .header .navbar.active{
      clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
   }

   .header .navbar a{
      display: block;
      margin:2rem;
   }

   .swiper-button-next,
   .swiper-button-prev{
      top:initial;
      bottom:1rem;
   }

   .menu .slide .box-container .box{
      flex-flow: column;
      text-align: center;
   }
}

@media (max-width:450px){

   html{
      font-size: 50%;
   }

   .home .slide .content h3{
      font-size: 7rem;
   }

}




JAVASCRIPT CODE BEGINS !!
let navbar = document.querySelector('.header .navbar');
let menuBtn = document.querySelector('#menu-btn');

menuBtn.onclick = () =>{
   menuBtn.classList.toggle('fa-times');
   navbar.classList.toggle('active');
};

window.onscroll = () =>{
   menuBtn.classList.remove('fa-times');
   navbar.classList.remove('active');
};

var swiper = new Swiper(".home-slider", {
   grabCursor:true,
   loop:true,
   centeredSlides:true,
   navigation: {
     nextEl: ".swiper-button-next",
     prevEl: ".swiper-button-prev",
   },
});

var swiper = new Swiper(".food-slider", {
   grabCursor:true,
   loop:true,
   centeredSlides:true,
   spaceBetween: 20,
   pagination: {
      el: ".swiper-pagination",
      clickable: true,
   },
   breakpoints: {
      0: {
        slidesPerView: 1,
      },
      700: {
        slidesPerView: 2,
      },
      1000: {
        slidesPerView: 3,
      },
   },
});

let previewContainer = document.querySelector('.food-preview-container');
let previewBox = previewContainer.querySelectorAll('.food-preview');

document.querySelectorAll('.food .slide').forEach(food =>{
   food.onclick = () =>{
      previewContainer.style.display = 'flex';
      let name = food.getAttribute('data-name');
      previewBox.forEach(preveiw =>{
         let target = preveiw.getAttribute('data-target');
         if(name == target){
            preveiw.classList.add('active');
         }
      });
   };
});

previewContainer.querySelector('#close-preview').onclick = () =>{
   previewContainer.style.display = 'none';
   previewBox.forEach(close =>{
      close.classList.remove('active');
   });
};

var swiper = new Swiper(".menu-slider", {
   grabCursor:true,
   loop:true,
   autoHeight:true,
   centeredSlides:true,
   spaceBetween: 20,
   pagination: {
      el: ".swiper-pagination",
      clickable: true,
   },
});

var swiper = new Swiper(".blogs-slider", {
   grabCursor:true,
   loop:true,
   centeredSlides:true,
   autoHeight:true,
   spaceBetween: 20,
   pagination: {
      el: ".swiper-pagination",
      clickable: true,
   },
   breakpoints: {
      0: {
        slidesPerView: 1,
      },
      700: {
        slidesPerView: 2,
      },
      1000: {
        slidesPerView: 3,
      },
   },
});


Thats it
Thank you GITHUB !
