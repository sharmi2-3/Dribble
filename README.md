# Project Responsive Web Design using Bootstrap
## Date:25.12.2024

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


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
index.html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gallery Page</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Design</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Popular Designs</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Categories</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Login/Sign Up</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  
  <div class="container py-4">
    <h1 class="text-center mb-4">Vintage Design</h1>
    <div class="row g-4">
      
      <div class="col-md-3 col-sm-6">
        <div class="card">
          <img src="bike.jpg" class="card-img-top" alt="Design 2">
          <div class="card-body">
            <h6 class="card-title">Freedom Rider</h6>
          </div>
        </div>
      </div>
      
      <div class="col-md-3 col-sm-6">
        <div class="card">
          <img src="bridge.jpg" class="card-img-top" alt="Design 3">
          <div class="card-body">
            <h6 class="card-title">Pathway to Connection</h6>
          </div>
        </div>
      </div>
      <div class="col-md-3 col-sm-6">
        <div class="card">
          <img src="vinyl.jpg" class="card-img-top" alt="Design 4">
          <div class="card-body">
            <h6 class="card-title">Timeless Grooves</h6>
          </div>
        </div>
      </div>
    </div>
  </div>


  <footer class="bg-dark text-center text-white py-3">
    <p>&copy; 2024 Designed by SHARMILA P</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
```
## OUTPUT:
![alt text](<Screenshot 2024-12-25 202556.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
