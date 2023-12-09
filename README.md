# dry-fruit-shop
!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>rahul enterprises dryfruit shop </title>
  <style>
    /* Add your CSS styles here */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: yellow;
    }

    header {
      background-color: blue;
      color: #fff;
      padding: 10px 0;
      text-align: center;
    }

    nav ul {
      list-style: blak;
      padding: 0;
      text-align: center;
    }

    nav ul li {
      display: inline;
      margin: 0 10px;
    }

    nav ul li a {
      text-decoration: none;
      color: #fff;
    }

    section {
      display: none;
      padding: 20px;
    }

    section:target {
      display: block;
    }

    .container {
      width: 80%;
      margin: auto;
      overflow: hidden;
    }

    .product {
      float: left;
      width: 30%;
      margin: 2%;
      padding: 10px;
      background: white;
      border-radius: 5px;
      box-shadow: 0 0 5px rgba(0,0,0,0.3);
    }

    .product img {
      width: 100%;
      border-radius: 5px;
    }

    footer {
      background-color: green;
      color: #fff;
      text-align: center;
      padding: 10px 0;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#products">Products</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <div class="container">
      <h1>Welcome to Rahul enterprises dryfruit shop</h1>
      <p>Delicious cashew nuts waiting for you!</p>
    </div>
	<!-- Featured Products Section -->
      <h2>Featured Products</h2>
      <div class="product">
        <img src="image1.jpeg" height="400px" width="200%" alt="Cashew Nut 1">
		 <img src="image2.jpeg" height="400px" width="200%" alt="Cashew Nut 2">
        <h3>desai goan Cashew Nut - Grade w180 </h3>
        <p>Delicious and fresh cashew nuts.</p>
      </div>
      <div class="product">
        <img src="cashew2.jpg" alt="Cashew Nut 2">
        <h3>Cashew Nut - Organic</h3>
        <p>Organically grown, healthy cashews.</p>
      </div>
      <!-- Add more featured products as needed -->

      <!-- Special Offers Section -->
      <h2>Special Offers</h2>
      <p>Check out our latest promotions and discounts!</p>
      <!-- Display any special offers or deals -->

      <!-- Testimonials Section -->
      <h2>What Our Customers Say</h2>
      <div class="testimonial">
        <blockquote>"Absolutely love the quality and taste of their products! Highly recommend."</blockquote>
        <p>- Happy Customer</p>
      </div>
      <!-- Add more testimonials if available -->
	  
	  <!-- Interactive Elements or CTA Buttons -->
      <h2>Explore Our Products</h2>
	  <div>
      <p>Find your favorite dry fruits now!</p>
	  </div>
      <!-- Add buttons or interactive elements directing to product pages -->

  </section>

  <section id="products">
    <div class="container">
      <h2>Our Products</h2>
      <div class="product">
        <img src="cashew1.jpg" alt="Cashew Nut 1">
        <h3>Cashew Nut - Grade A</h3>
        <p>Delicious and fresh cashew nuts.</p>
      </div>
      <div class="product">
        <img src="cashew2.jpg" alt="Cashew Nut 2">
        <h3>Cashew Nut - Organic</h3>
        <p>Organically grown, healthy cashews.</p>
      </div>
      <div class="product">
        <img src="cashew3.jpg" alt="Cashew Nut 3">
        <h3>Cashew Nut - Roasted</h3>
        <p>Perfectly roasted cashews for a crunchy snack.</p>
      </div>
    </div>
  </section>
  
  <section id="extendedForm" style="display: none;">
  <div class="container">
    <h2>Contact Form</h2>
    <form action="mailto:rajuramvayad@gmail.com" method="post" enctype="text/plain">
      <!-- Add your form fields here -->
      <!-- ... -->
      <input type="submit" value="Submit">
    </form>
  </div>
</section>

<script>
  function showForm() {
    const extendedForm = document.getElementById('extendedForm');
    extendedForm.style.display = 'block';
  }
</script>

  <section id="about">
    <div class="container">
      <h2>About Rahul enterprises dryfruit shop </h2>
      <p>We are passionate about providing high-quality cashew nuts to our customers.</p>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact Rahul enterprises dryfruit shop </h2>
      <p>Email: rajuramvayad@gmail.com </p>
      <p>Phone: +919890077705  <p>
	  <p>NAME: Rajuram bishnoi <p>
	   <h3>Contact Form</h3>
    <form action="mailto:rajuramvayad@gmail.com" method="post" enctype="text/plain">
      <label for="name">Name:</label><br>
      <input type="text" id="name" name="name"><br>
	  <label for="NUMBER">NUMBER:</LABEL><BR>
	  <INPUT TYPE="text" id="number" number="number"><br>
      <label for="email">Email:</label><br>
      <input type="email" id="email" name="email"><br>
      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="4" cols="50"></textarea><br>
      <input type="submit" value="Submit">
    </form>
	<!-- Social Media Links -->
      <h2>Connect with Us</h2>
      <p>Follow us on social media for more updates!</p>
      <!-- Include icons or links to your social media profiles -->
	  </div>
	  </section>
