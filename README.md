# Project Responsive Web Design using Bootstrap
## Date:24-12-2024

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
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Dribble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  </head>
  <body>
    <nav class="navbar navbar-expand-sm navbar-dark bg-dark">
      
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">

            <li class="nav-item">
              <a href="#" class="nav-link active" aria-current="page">DRIBBLE CLONE</a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link">Designer</a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link">Sign up</a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link">Sign in</a>
            </li>
          </ul>
          <div class="ms-auto">
            <form class="d-flex" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-primary" type="submit">Search</button>
            </form>
          </div>
        </div>
      </div>
    </nav>

    <section class="text-center py-4 bg-dark text-white">
      <div class="container">
        <p class="lead fw-bold mb-4">What are you working on? Dribbble is show and tell for designers.</p>
        <div class="d-inline-flex gap-2">
          <a href="#" class="btn btn-primary">Learn More</a>
          <a href="#" class="btn btn-outline-danger">Sign Up</a>
        </div>
      </div>
    </section>

    <div class="container py-4">
      <div class="row justify-content-center g-4">
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="WATCH.jpeg" class="card-img-top" alt="GALAXY WATCHES">
            <div class="card-body text-center">
                <h5 class="card-title fw-bold">GALAXY WATCHES</h5>
              <a href="#" class="btn btn-primary btn-sm">Visit</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="smart g.jpeg" class="card-img-top" alt="SMART GLASS">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">SMART GLASS</h5>
              <a href="#" class="btn btn-primary btn-sm">Visit</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="IMG3.png" class="card-img-top" alt="Style Designer's work">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">Style Designer</h5>
              <a href="#" class="btn btn-primary btn-sm">Visit</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="gammer.jpg" class="card-img-top" alt=" Gamer Wallet">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold"> Gamer Wallet</h5>
              <a href="#" class="btn btn-primary btn-sm">Visit</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="ride.png" class="card-img-top" alt="Car Rental App">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">Car Rental AppJslash</h5>
              <a href="#" class="btn btn-primary btn-sm">Visit</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="Drastic Logo.jpg" class="card-img-top" alt="Drastic Logo">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">Drastic Logo</h5>
              <a href="#" class="btn btn-primary btn-sm">Visit</a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <footer class="bg-dark text-white text-center py-3">
      <h2 class="h6 m-0">Designed and developed by YUGESH M (24900164)</h2>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  </body>
</html>




```

## OUTPUT:
![alt text](<Screenshot (129).png>)
![alt text](<Screenshot (130).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
