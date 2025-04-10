# SWC2363-PROJECT
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vanderline Tech</title>

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Font Awesome (Public Link) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Custom CSS -->
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">
                <i class="fa-solid fa-store"></i> VANDERLINE TECH
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#"><i class="fa-solid fa-house"></i> Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#"><i class="fa-solid fa-info-circle"></i> About</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">
                            <i class="fa-solid fa-list"></i> Services
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#"><i class="fa-solid fa-laptop-code"></i> Package PC</a></li>
                            <li><a class="dropdown-item" href="#"><i class="fa-solid fa-chart-line"></i> PC Parts</a></li>
                            <li><hr class="dropdown-divider"></li>
                            <li><a class="dropdown-item" href="#"><i class="fa-solid fa-ellipsis"></i> More Services</a></li>
                        </ul>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#"><i class="fa-solid fa-shopping-cart"></i> Cart (0)</a>
                    </li>
                </ul>
                <button id="dark-mode-toggle" class="btn btn-dark">🌙 Dark Mode</button>
            </div>
        </div>
    </nav>
<!--Background-->
    <section id="home">
      <h1>Welcome to Vanderline Tech</h1>
      <p>Your best source for tech products</p>
      
  

    <!-- Home Section -->
    <section id="home">
        <div class="container text-center text-white">
            <h5>NEW ARRIVAL</h5>
            <h1>BEST PRICES FOR THIS MONTH</h1>
            <p>GET THE BEST DEALS ON THE LATEST TECH PRODUCTS</p>
            <button class="btn btn-primary" onclick="location.href='products.html'">SHOP NOW</button>


        </div>
    </section>

<!-- Featured Products -->
<section id="featured" class="container my-5">
  <h2 class="text-center">🔥 Featured Products</h2>
  <div class="row">
      <!-- Product 1 -->
      <div class="col-md-4">
          <div class="card">
              <img src="assets/img/product1.jpg" class="card-img-top" alt="Gaming Laptop">
              <div class="card-body">
                  <h5 class="card-title">Gaming Laptop</h5>
                  <p class="card-text">High-performance laptop with RGB keyboard.</p>
                  <a href="#" class="btn btn-primary">Buy Now</a>
              </div>
          </div>
      </div>
      
      <!-- Product 2 -->
      <div class="col-md-4">
          <div class="card">
              <img src="assets/img/product2.jpg" class="card-img-top" alt="Casing Pc">
              <div class="card-body">
                  <h5 class="card-title">Gaming Casing Pc</h5>
                  <p class="card-text">RGB Casing pc for gaming.</p>
                  <a href="#" class="btn btn-primary">Buy Now</a>
              </div>
          </div>
      </div>

      <!-- Product 3 -->
      <div class="col-md-4">
          <div class="card">
              <img src="assets/img/product3.jpg" class="card-img-top" alt="Asus Gaming Monitor">
              <div class="card-body">
                  <h5 class="card-title">Gaming Monitor</h5>
                  <p class="card-text">Hiqh Qualitiy of Gaming Monitor</p>
                  <a href="#" class="btn btn-primary">Buy Now</a>
              </div>
          </div>
      </div>
  </div>
</section>

<!--Brand-->
<section id="brand" class="container">
  <div class ="row">
    <img class ="img-fluid col-lg-3 col-md-6 col-sm-12" src ="assets/img/brand 1.jpg"/>
    <img class ="img-fluid col-lg-3 col-md-6 col-sm-12" src ="assets/img/brand 2.jpg"/>
    <img class ="img-fluid col-lg-3 col-md-6 col-sm-12" src ="assets/img/brand 3.jpg"/>
    <img class ="img-fluid col-lg-3 col-md-6 col-sm-12" src ="assets/img/brand 4.jpg"/>
   <div></div>


    <!-- Contact Section -->
    <section id="contact" class="bg-light py-5">
        <div class="container text-center">
            <h2>📞 Contact Us</h2>
            <p>Email: support@vanderlinetech.com | Phone: +123 456 7890</p>
            <div>
                <a href="#"><i class="fa-brands fa-facebook fa-2x"></i></a>
                <a href="#"><i class="fa-brands fa-instagram fa-2x"></i></a>
                <a href="#"><i class="fa-brands fa-twitter fa-2x"></i></a>
            </div>
        </div>
    </section>

    

    <!-- Customer Testimonials -->
    <section id="testimonials" class="py-5">
        <div class="container">
            <h2 class="text-center">📦 What Our Customers Say</h2>
            <div class="row">
                <div class="col-md-4">
                    <blockquote class="blockquote">
                        <p>“Amazing service! My PC arrived within 2 days.”</p>
                        <footer class="blockquote-footer">John Doe</footer>
                    </blockquote>
                </div>
            </div>
        </div>
    </section>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

    <!-- Custom JS for Dark Mode -->
    <script>
        document.getElementById('dark-mode-toggle').addEventListener('click', function() {
            document.body.classList.toggle('dark-mode');
        });
    </script>
</body>
</html>



/* Global Styles */
body {
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    transition: background-color 0.3s, color 0.3s;
}

/* Dark Mode */
.dark-mode {
    background-color: #121212;
    color: white;
}

/* Navbar Hover Effects */
.navbar-nav .nav-link {
    transition: color 0.3s ease-in-out;
}
.navbar-nav .nav-link:hover {
    color: #ff4c4c !important;
}

/* Home Section */
#home {
    background-image: url('../assets/img/background.jpg');
    width: 100%;
    height: 100vh;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: white; /* Text color for visibility */
}



/* Featured Products */
.card img {
    height: 200px;
    object-fit: cover;
}

/* Contact Section */
#contact a {
    margin: 10px;
    color: black;
}
#contact a:hover {
    color: #007bff;
}


