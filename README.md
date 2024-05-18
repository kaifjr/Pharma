# Ex.10 Responsive Web Design using Bootstrap


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
```C
home.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharmaceutical Website - Home</title>
  <!-- Bootstrap CSS -->
  <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <header>
    <nav class="navbar navbar-dark bg-success">
      <div class="container">
        <a class="navbar-brand" href="#">HEALTHPLUS PHARMACY</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item active">
              <a class="nav-link" href="home.html">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="about.html">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="product.html">Products</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="contact.html">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>

  <section class="container mt-4">
    <h2>Welcome to our Pharmaceutical Website</h2>
    <p class="text-dark">This website is dedicated to providing information about our pharmaceutical products.</p>
        <p>At Pharma, we are dedicated to revolutionizing healthcare through innovation and excellence. As a leading pharmaceutical company, we are committed to developing and delivering high-quality medicines and healthcare solutions that improve the lives of millions around the globe.</p>
        <p>Our mission is to make a meaningful difference in the world by providing safe, effective, and affordable treatments for a wide range of medical conditions. With a focus on research, development, and continuous improvement, we strive to stay at the forefront of medical advancements.</p>
        <p>Whether it's combating infectious diseases, managing chronic conditions, or enhancing overall wellness, Pharma is here to support you on your journey to better health. Our team of dedicated professionals works tirelessly to ensure that our products meet the highest standards of quality, safety, and efficacy.</p>
        <p>Explore our website to learn more about our products, our commitment to sustainability and corporate responsibility, and how we are shaping the future of healthcare. Join us as we continue to innovate, inspire, and make a positive impact on the lives of people everywhere.</p>
    <h3></h3>
    
    

  <body style="background-image: url('home.jpg'); background-size: cover; background-repeat: no-repeat;">
  </section>
  <br><br>
  <br><br>
  <br><br>
  <br><br>
  
  <footer class="bg-dark text-white mt-5">
    <div class="container py-3">
      <div class="row">
        <div class="col-md-6">
          <p>&copy; 2024 HEADPLUS PHARMACY. All rights reserved.</p>
        </div>
        <div class="col-md-6 text-right">
          <p>Contact: HEALTHP.com</p>
        </div>
      </div>
    </div>
  </footer>

  <!-- Bootstrap JS and dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
```C
about.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharmaceutical Company - About</title>
  <!-- Bootstrap CSS -->
  <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">HEALTHPLUS PHARMACY</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="home.html">Home</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="about.html">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="product.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>


  <body style="background-image: url('about1.jpg'); background-size: cover; background-repeat: no-repeat;"></body>
  <div class="container mt-4">
    <div class="row">
      <div class="col-md-12">
        <div class="text-light">
        <h2>About Us</h2>
        <h2>HealthPlus: Providing Comprehensive Healthcare Solutions</h2>
        <p>HealthPlus is a leading healthcare provider dedicated to delivering comprehensive and accessible healthcare services to individuals and families. With a focus on patient-centered care and excellence, HealthPlus offers a wide range of medical services tailored to meet the diverse needs of our patients.</p>
        <h3>Primary Care Excellence</h3>
        <p>At HealthPlus, we prioritize preventive care and early intervention to promote optimal health outcomes. Our team of primary care physicians provides comprehensive health assessments, routine check-ups, and personalized treatment plans to address a wide range of medical concerns.</p>
        <h3>Specialty Care Expertise</h3>
        <p>In addition to primary care, HealthPlus offers specialized medical services across various disciplines, including cardiology, orthopedics, neurology, and more. Our experienced specialists utilize the latest diagnostic and treatment techniques to deliver exceptional care and improve patient outcomes.</p>
        <h3>Wellness Programs for Holistic Health</h3>
        <p>At HealthPlus, we believe in a holistic approach to healthcare that encompasses not only physical health but also mental and emotional well-being. Our wellness programs focus on nutrition, fitness, stress management, and lifestyle modifications to empower individuals to lead healthier and happier lives.</p>
      </div>
    </div>
    </div>
  </div>

  
  <br><br>
  <br>
  
  
  <footer class="bg-dark text-white mt-5">
    <div class="container py-3">
      <div class="row">
        <div class="col-md-6">
          <p>&copy; 2024 HEADPLUS PHARMACY. All rights reserved.</p>
        </div>
        <div class="col-md-6 text-right">
          <p>Contact: HEALTHP.com</p>
        </div>
      </div>
    </div>
  </footer>

  <!-- Bootstrap JS and dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
```C
product.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharmaceutical Company - Products</title>
  <!-- Bootstrap CSS -->
  <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <body style="background-image: url('prod.jpg'); background-size: cover; background-repeat: no-repeat;">
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">HEALTHPLUS PHARMACY</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="home.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">About</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="product.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <div class="container mt-5 content">
    <div class="row">
      <div class="col-md-12">
        <h1>Our Products</h1>
        <div class="card-deck">
          <div class="card">
            <div class="bg-info">
            <img src="dolo.jpeg" class="card-img-top" alt="Product 1" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Product 1</h5>
              <p class="card-text">Dolo 650 can be used for headaches, mild to high fevers, and any other type of bodily aches. It is usually prescribed by doctors in case of recurrent high fevers. Dolo 650 medicine can also be used for toothaches and certain types of inner or middle ear pains.</p>
              <a href="#" class="btn btn-warning">Buy Now</a>
            </div>
            </div>
          </div>
          <div class="card">
            <div class="bg-info">
            <img src="product1.jpg" class="card-img-top" alt="Product 2" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Product 2</h5>
              <p class="card-text">Also known as a blood pressure meter, gauge, or monitor, this device uses an inflatable rubber cuff wrapped around the arm to measure blood pressure.</p>
              <br><br><br>
              <a href="#" class="btn btn-warning">Buy Now</a>
            </div>
            </div>
          </div>
          <div class="card">
            <div class="bg-info">
            <img src="product3.jpeg" class="card-img-top" alt="Product 3" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Product 3</h5>
              <p class="card-text">Tramadol is used for the short-term relief of severe pain. It should only be used when other forms of non-opioid pain relief have not been successful in managing pain or are not tolerated. Tramadol is not usually recommended for the treatment of chronic (long-term) pain.</p>
              <a href="#" class="btn btn-warning">Buy Now</a>
            </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <footer class="bg-dark text-white mt-5">
    <div class="container py-3">
      <div class="row">
        <div class="col-md-6">
          <p>&copy; 2024 HEADPLUS PHARMACY. All rights reserved.</p>
        </div>
        <div class="col-md-6 text-right">
          <p>Contact: HEALTHP.com</p>
        </div>
      </div>
    </div>
  </footer>

  <!-- Bootstrap JS and dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4"></script>
  </body>
</html>
```
```C
contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharmaceutical Company - Contact</title>
  <!-- Bootstrap CSS -->
  <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">HEALTHPLUS PHARMACY</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="home.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="product.html">Products</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <body style="background-image: url('contacts1.webp'); background-size: cover; background-repeat: no-repeat;">

  <div class="container">
    <h2>CONTACT US</h2>
    <form action="/action_page.php">
      <div class="form-group">
        <label for="email">USERNAME:</label>
        <input type="text" class="form-control" id="email" placeholder="Enter USERNAME" name="email">
      </div>
      <div class="form-group">
        <label for="pwd">PHONE NUMBER:</label>
        <input type="number" class="form-control" id="pwd" placeholder="Enter NUMBER" name="pwd">
      </div>
      <div class="form-group">
        <label for="pwd">EMAIL:</label>
        <input type="text" class="form-control" id="pwd" placeholder="Enter EMAIL" name="pwd">
      </div>


      <form>
        <div class="form-group">
          <label for="comment">Comment:</label>
          <textarea class="form-control" rows="5" id="comment"></textarea>
        </div>
      </form>

      <div class="checkbox">
        <label><input type="checkbox" name="remember"> Remember me</label>
      </div>
      <button type="submit" class="btn btn-default">Submit</button>
    </form>

    <br><br>
 
  
  <footer class="bg-primary text-white mt-5">
    <div class="container py-3">
      <div class="row">
        <div class="col-md-6">
          <p>&copy; 2024 HEADPLUS PHARMACY. All rights reserved.</p>
        </div>
        <div class="col-md-6 text-right">
          <p>Contact: HEALTHP.com</p>
        </div>
      </div>
    </div>
  </footer>

  <!-- Bootstrap JS and dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```


## OUTPUT:
![1](https://github.com/kaifjr/Pharma/assets/147469730/ef26a3b0-504d-4483-b3f8-f752eb5ced20)
![2](https://github.com/kaifjr/Pharma/assets/147469730/d12fecc1-dbfb-45e4-abb2-4b5f2fb349e2)
![3](https://github.com/kaifjr/Pharma/assets/147469730/cb8d5f66-ab5b-4e97-8b0a-819584f1febb)
![4](https://github.com/kaifjr/Pharma/assets/147469730/5f0aef5f-6d1b-420d-9e83-bf37584d7c89)






## RESULT:
The program for responsive web design using Bootstrap is completed successfully.
