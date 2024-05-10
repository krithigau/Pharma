# Project Responsive Web Design using Bootstrap
## Date:8.05.2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
cure.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Health our Legacy</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url('bg1.jpeg');
      background-size: cover;
      background-repeat: no-repeat;
    }
    footer{
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #e31d0b; 
      color: rgb(247, 242, 242);
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-danger">
    <a class="navbar-brand" href="#">HealthX Solution</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div  class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="cure.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item dropdown active">
            <a class="nav-link dropdown-toggle" href="about.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              About
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
              <a class="dropdown-item" href="#innovation">Innovation</a>
              <a class="dropdown-item" href="#compassion">Compassion</a>
              <a class="dropdown-item" href="#join us">Join us</a>
              <!-- Add more subheadings as needed -->
            </div>
          </li>
        <li class="nav-item">
          <a class="nav-link" href="prod.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="reachout.html">Reachout</a>
        </li>
      </ul>
    </div>
  </nav>
  <center>
  <img src="img1.jpeg" width="300spx">
  </center>
  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <font color="white">
        <h1>Your Health Our Priority</h1>
        <br>
        <br>
        <h5>Welcome to HealthX Solutions, where innovation meets compassion in healthcare. As a leading pharmaceutical company, we are dedicated to revolutionizing the way diseases are treated and managed.
            Driven by a passion for improving health outcomes, we embrace diversity, collaboration, and integrity in everything we do. Whether it's developing breakthrough therapies or providing support to communities in need, we are dedicated to making a positive impact on global health.
            Join us in our mission to redefine healthcare and empower people to live healthier, happier lives. Together, we can shape a better future for generations to come.</h5>
        <h5>Thank you for choosing HealthX Solution for your healthcare needs. We try to serve you the best as always!!</h5>
        </font> 
    </div>
      
    </div>
  </div>

  <!-- Footer -->
  <footer>
    <h6> HealthX Solution-Your Health Our Vision </h6>
    <h6>&copy; KRITHIGA U (212223240076)</h6>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
```
abt.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url('bg1.jpeg');
      background-size: cover;
      background-repeat: no-repeat;
    }
    footer{
    position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #f50404; 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-danger">
    <a class="navbar-brand" href="#">HealthX Solution</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div  class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="cure.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="prod.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="reachout.html">Reachout</a>
        </li>
        <li class="nav-item dropdown active">
          <a class="nav-link dropdown-toggle" href="about.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            About
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
            <a class="dropdown-item" href="#innovation">Innovation</a>
            <a class="dropdown-item" href="#compassion">Compassion</a>
            <a class="dropdown-item" href="#join us">Join us</a>
            <!-- Add more subheadings as needed -->
          </div>
        </li>

      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <font color="white">
        <h1>About Us</h1>
        <br>
        <div id="innovation">
          <h2>Innovative Pharmaceutical Excellence</h2>
          <p>Discover the forefront of pharmaceutical innovation at Medix Solutions. Our commitment to excellence drives us to continually push boundaries, delivering groundbreaking therapies that redefine healthcare standards.</p>
        </div>
        <div id="compassion">
          <h2>Compassionate Patient-Centric Care</h2>
          <p>At Medix Solutions, patients are at the heart of everything we do. Our compassionate approach ensures that each medication we develop addresses unmet medical needs with empathy and understanding.</p>
        </div>
        <div id="join us">
          <h2>Join Us in Shaping the Future of Healthcare</h2>
         <p> Join us in our mission to redefine healthcare. Together, we can create a healthier, brighter future for all. Welcome to Medix Solutions, where innovation meets compassion in every dose.</p>
        </font>
        
        </div>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer>
    <h6> HealthX Solution-Your Health Our Vision </h6>
    <h6>&copy; KRITHIGA U (212223240076)</h6>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
```
prod.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Health our Legacy</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url('bg1.jpeg');
      background-size: cover;
      background-repeat: no-repeat;
    }
    footer{
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #e31d0b; 
      color: rgb(247, 242, 242);
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-danger">
    <a class="navbar-brand" href="#">HealthX Solution</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div  class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="cure.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item dropdown active">
            <a class="nav-link dropdown-toggle" href="about.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              About
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
              <a class="dropdown-item" href="#innovation">Innovation</a>
              <a class="dropdown-item" href="#compassion">Compassion</a>
              <a class="dropdown-item" href="#join us">Join us</a>
              <!-- Add more subheadings as needed -->
            </div>
          </li>
        <li class="nav-item">
          <a class="nav-link" href="prod.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="reachout.html">Reachout</a>
        </li>
      </ul>
    </div>
  </nav>

   <!-- Page Content -->
   <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <font color="white">
        <h1>HealthX PRODUCTS</h1>
        </font>
        <div class="card-deck">
          <div class="card">
            <img src="med1.png" class="card-img-top" alt="Product 1">
            <div class="card-body">
              <h5 class="card-title">Product 1</h5>
              <p class="card-text">A healthy skin care routine for daily use.
                Use the clenser and the skin care pack today!
              </p>
              <br>
              <br>
              <br>
              <br>
              <br>
              <a href="#" class="btn btn-success">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="med2.png" class="card-img-top" alt="Product 2">
            <div class="card-body">
              <h5 class="card-title">Product 2</h5>
              <p class="card-text">For a daily shine of your damaged hair use our 3-pack combo for a shinny and hair.Don't miss out! </p>
              <br>
              <br>
              <br>
              <br>
              <br>
              <a href="#" class="btn btn-success">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="med3.png" class="card-img-top" alt="Product 3">
            <div class="card-body">
              <h5 class="card-title">Product 3</h5>
              <p class="card-text">Try out our new product for this summer and keep your skin protected from uv rays!..Try out our sunscreen serum and much more!</p>
              <a href="#" class="btn btn-success">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
<!-- Footer -->
<footer>
    <h6> HealthX Solution-Your Health Our Vision </h6>
    <h6>&copy; KRITHIGA U (212223240076)</h6>
  </footer>
</body>
</html>
```
```
reachout.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - PharmaCompany</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url('bg1.jpeg');
      background-size: cover;
      background-repeat: no-repeat;
    }
    footer{
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #343a40; 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
    .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color:rgb(247, 243, 243);
        }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-danger">
    <a class="navbar-brand" href="#">HealthX Solution</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div  class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="cure.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item dropdown active">
            <a class="nav-link dropdown-toggle" href="about.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              About
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
              <a class="dropdown-item" href="#innovation">Innovation</a>
              <a class="dropdown-item" href="#compassion">Compassion</a>
              <a class="dropdown-item" href="#join us">Join us</a>
              </div>
          </li>
        <li class="nav-item">
          <a class="nav-link" href="prod.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="reachout.html">Reachout</a>
        </li>
      </ul>
    </div>
  </nav>
  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
        <font color="white">
      <div>
        <h3 class="heading3"><b>ANY QUERIES FEEL FREE TO CONTACT US</b></h3>
        <div class="queries">
            <table cellpadding="15px" cellspacing="15px" class="table2">
                <tr>
                    <td>
                        <h3><b>NAME :</b></h3>
                    </td>
                    <td>
                        <input type="name" placeholder="Enter Name"> 
                    </td>
                </tr>
                <tr>
                    <td>
                        <h3><b>EMAIL :</b></h3>
                    </td>
                    <td>
                        <input type="email" placeholder="Enter E-mail">
                    </td>
                </tr>
                <tr>
                    <td>
                        <h3><b>MESSAGE :</b></h3>
                    </td>
                    <td>
                        <input type="text" placeholder="Enter text">
                    </td>
                </tr>
                <tr>
                    <td colspan="2">
                        <div style="text-align:center;">
                        <input type="submit" style="background-color: rgb(213, 218, 221); color: black;" >
                        </div>
                    </td>
                </tr>
        </table>
    </div>
      <div class="col-md-4">
        <h2>HealthX Solutions</h2>
        <address>
          <strong>Address:</strong><br>
          123 Oakwood Springs Blvd, Maple Street,Cityville,Stateville-64528<br>
        <br><br>
          <strong>Email:</strong><br>
          HealthX.com<br><br>
          <strong>Phone:</strong><br>
          +91-7562134789
        </font>
        </address>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer>
    <h6> HealthX Solution-Your Health Our Vision </h6>
    <h6>&copy; KRITHIGA U (212223240076)</h6>
  </footer>
  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
## OUTPUT:

![alt text](<Screenshot (131).png>)

![alt text](<Screenshot (132).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
