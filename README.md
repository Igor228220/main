# Frontend Mentor - Product preview card component

![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="preconnect" href="https://fonts.googleapis.com"> 
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> 
  <link href="https://fonts.googleapis.com/css2?family=Fraunces:wght@700&family=Montserrat:wght@500;700&display=swap" rel="stylesheet">
  
  <link rel="stylesheet" href="styles.css">
  <title>Product preview card component</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
  </style>
</head>

<body>

  <main class='panel'>
    <img class="mobile" src="/images/image-product-mobile.jpg">
    <img class="desktop" src="/images/image-product-desktop.jpg">
    <section class="content-container flow">
      <section class="text-content flow">
        <p class="product-type">perfume</p>
        <h1 class="product-title">Gabrielle Essence Eau De Parfum</h1>
        <p class="product-description">
          A floral, solar and voluptuous interpretation composed by Olivier Polge, 
  Perfumer-Creator for the House of CHANEL.
        </p>
      </section>
      <div class="price-ctr">
        <div class="product-price">$149.99</div>
        <p class="product-sale-price">$169.99</p>
      </div>
      <a class="btn btn-primary" href="#">Add to cart</a>      
    </section>
  </main>

  <!-- Preview

  Gabrielle Essence Eau De Parfum

  A floral, solar and voluptuous interpretation composed by Olivier Polge, 
  Perfumer-Creator for the House of CHANEL.

  $149.99
  $169.99

  Add to Cart
  
  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="#">Your Name Here</a>.
  </div> -->
</body>
</html>
