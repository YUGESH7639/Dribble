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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DRIBBLE</title>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    
</head>
<body class="bg-light text-light">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">DRIBBLE</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#HOME">HOME</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#PRODUCTS">ORDERS</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#LOGIN ">LOGIN</a>
                    </li>
                    <li class="nav-item">
                        <a href="#SIGN UP" class="btn btn-success ms-2">SIGN UP</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    
    <section class="text-center py-5 bg-secondary">
        <div class="container ">
            <h1 class="display-4 text-dark">TOP SHOPPING BRANDS</h1>
            
            <img src="BG.jpg" height="454" width="786">
            
        </div>
    </section>
   
    <div class="container my-5">
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card">
                        <img src="AD.png" class="card-img-top" alt="Forests">
                        <div class="card-body">
                            <h5 class="card-title">ADIDAS</h5>
                            <p class="card-text">adidas is a multinational corporation, founded and headquartered in Herzogenaurach, Germany, which designs and manufactures footwear, apparel, and accessories.</p>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card">
                        <img src="APP.JPG" class="card-img-top" alt="APPLE">
                        <div class="card-body">
                            <h5 class="card-title">APPLE</h5>
                            <p class="card-text">Apple Inc. (formerly Apple Computer Inc.) is an American computer and consumer electronics company famous for creating the iPhone, iPad and Macintosh computers.</p>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card">
                        <img src="TITAN.JPG" class="card-img-top" alt="WATCHES">
                        <div class="card-body">
                            <h5 class="card-title">WATCHES</h5>
                            <p class="card-text">we explore a few of our collections that pay homage to the legacy of watchmaking and are crafted with the discerning Indian customer in mind.</p>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card">
                        <img src="OTTO.jpg" class="card-img-top" alt="OTTO">
                        <div class="card-body">
                            <h5 class="card-title">OTTO</h5>
                            <p class="card-text">OTTO is a premier menswear lifestyle brand, dedicated to offering contemporary styles, diverse selections, comfort, and excellent value in each garment tailored for modern men. </p>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card">
                        <img src="FW.jpg" class="card-img-top" alt="FACE WASH">
                        <div class="card-body">
                            <h5 class="card-title">FACE WASH</h5>
                            <p class="card-text">Moisturising and healing properties bring a natural glow from within yourself. Its active ingredients help remove excess oil and give a long-lasting fresh face.</p>
                        </div>
                    </div>
                </a>
            </div>
            <div class="col">
                <a href="#" class="text-decoration-none">
                    <div class="card">
                        <img src="LG.jpg" class="card-img-top" alt="HOME APPLIENCE">
                        <div class="card-body">
                            <h5 class="card-title">HOME APPLIENCE</h5>
                            <p class="card-text">LG is a leading manufacturer of consumer and commercial products ranging from TVs, home appliances, air solutions, monitors, automotive components and solutions</p>
                        </div>
                    </div>
                </a>
            </div>
        </div>
    </div>

    
    <footer class="bg-dark text-light py-3">
        <div class="container text-center">
            <p>&copy; DESIGNED BY YUGESH M(24900164)</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>



```

## OUTPUT:
![alt text](<Screenshot (126).png>)
![alt text](<Screenshot (127).png>)
![alt text](<Screenshot (128).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
