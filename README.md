# Task-1
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home Maintenance & Interior Design</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

  <!-- Custom CSS -->
  <style>
    /* General Styles */
    body {
      background-color: #728FCE; /* light blue background */
      color: #333;
      font-family: Arial, sans-serif;
    }
    .navbar-brand {
      font-size: 1.8rem;
      color: #333;
      letter-spacing: 1px;
    }
    .navbar-brand:hover {
      color: #000000; /* black on hover */
      text-decoration: none;
    }
    .navbar-nav .nav-item .nav-link {
      color: #333;
    }
    .navbar-nav .nav-item .nav-link:hover {
      color: #000000; /* black on hover */
    }
    .navbar-nav .nav-item.active .nav-link {
      font-weight: bold;
      color: #000000; /* black on hover */
    }
    /* Hero Section */
    .hero {
      color: #000000; /* black on hover */
      padding: 160px 0;
      text-align: center;
      color: #fff;
    }
    /* Button Styling */
    .btn-primary {
      background-color: #333; /* Dark gray button */
      border-color: #333;
    }
    .btn-primary:hover {
      background-color: #555; /* Darker gray on hover */
      border-color: #555;
    }
    /* Sections */
    .service,
    .portfolio-item,
    .testimonial-item,
    .blog-post,
    .client-item,
    .partner {
      background-color: #FFC0CB;
      border: 1px solid #ddd;
      padding: 60px;
      margin-bottom: 20px;
      border-radius: 5px;
    }
    /* Borders and Hover Effects */
    .service:hover,
    .portfolio-item:hover,
    .testimonial-item:hover,
    .blog-post:hover,
    .client-item:hover,
    .partner:hover {
      border-color: #FFC0CB; /* pink border on hover */
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.1); /* Shadow on hover */
    }
    /* Footer */
    .footer {
      background-color: #333; /* Dark footer */
      color: #fff;
      text-align: center;
      padding: 20px 0;
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Home Maintenance & Interior Design</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse justify-content-center" id="navbarSupportedContent">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link" href="home.html">Home <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#services">Our Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h1>Welcome to Home Maintenance & Interior Design</h1>
      <p>Your one-stop solution for all home maintenance and interior design needs.</p>
      <a href="#contact" class="btn btn-primary btn-lg">Get Started</a>
    </div>
  </section>
  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <p>&copy; 2024 Home Maintenance & Interior Design. All Rights Reserved.</p>
    </div>
  </footer>
  

  <!-- Bootstrap and jQuery -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
