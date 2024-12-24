# Project Responsive Web Design using Bootstrap
## Date:24.12.24

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
main
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Castle Rings</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body class="text-center">

   
    <nav class="navbar navbar-expand-lg navbar-light bg-warning">
        <div class="container-fluid">
            <a class="navbar-brand text-dark" href="#">CASTLE RINGS</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link text-white" href="C:\Users\admin\Dribble\proj\app\static\home.html">HOME</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white" href="C:\Users\admin\Dribble\proj\app\static\address.html">ADDRESS</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white" href="C:\Users\admin\Dribble\proj\app\static\contact.html">CONTACT</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <section class="hero bg-light py-5">
        <h1 class="display-4 text-dark">Welcome to Castle Rings</h1>
        <p class="lead">Explore the finest collection of rings that will make you shine.</p>
    </section>

    <section class="container py-5">
        <h2 class="text-center mb-4">Our Featured Collections</h2>
        <div class="row">
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="ring.jpg" class="card-img-top" alt="Ring 1">
                    <div class="card-body">
                        <h5 class="card-title">Elegant Gold Ring</h5>
                        <p class="card-text">A timeless gold ring that fits all occasions.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="ring2.jpg" class="card-img-top" alt="Ring 2">
                    <div class="card-body">
                        <h5 class="card-title">Diamond Ring</h5>
                        <p class="card-text">Shining diamonds set in exquisite craftsmanship.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="ring3.jpg" class="card-img-top" alt="Ring 3">
                    <div class="card-body">
                        <h5 class="card-title">Silver Ring</h5>
                        <p class="card-text">A sleek silver ring perfect for everyday wear.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="bg-light py-5">
        <h2>About Us</h2>
        <p class="lead">At Castle Rings, we design and craft rings that make every moment special. From custom designs to ready-made collections, our rings are built with elegance and precision.</p>
    </section>

 
    <footer class="bg-dark text-white text-center py-3">
        <p>Designed and Developed by V. SHREYA</p>
    </footer>

</body>
</html>
 
home
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Info - Castle Rings</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body class="text-center">

   
    <nav class="navbar navbar-expand-lg navbar-light bg-warning">
        <div class="container-fluid">
            <a class="navbar-brand text-dark" href="#">CASTLE RINGS</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link text-white" href="C:\Users\admin\Dribble\proj\app\static\main.html">MAIN</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white" href="C:\Users\admin\Dribble\proj\app\static\address.html">ADDRESS</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white" href="C:\Users\admin\Dribble\proj\app\static\contact.html">CONTACT</a>
                    </li>
                    
                   
                </ul>
            </div>
        </div>
    </nav>


    <section class="container py-5">
        <h1 class="display-4 text-dark mb-4">About Castle Rings</h1>
        <p class="lead">Castle Rings is a place where elegance and craftsmanship meet. We specialize in creating timeless rings that capture the essence of luxury and style. Whether you're looking for a ring for a special occasion or something to wear every day, our collection has something for everyone.</p>

        <h2 class="mt-5">Our Mission</h2>
        <p class="lead">Our mission is to offer high-quality, finely crafted rings that bring joy and beauty to every customer. We believe in providing exceptional value, with each piece designed to stand the test of time and become a cherished part of your life.</p>

       

        <h2 class="mt-5">Why Choose Us?</h2>
        <p class="lead">At Castle Rings, we offer more than just beautiful rings. We provide a personalized shopping experience and a wide variety of designs to suit your needs. From custom rings to pre-designed collections, our goal is to create jewelry that you can cherish forever.</p>
    </section>

   
    <footer class="bg-dark text-white text-center py-3">
        <p>Designed and Developed by V. SHREYA</p>
    </footer>

</body>
</html>

address
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Address - Castle Rings</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body class="text-center">

    
    <nav class="navbar navbar-expand-lg navbar-light bg-warning">
        <div class="container-fluid">
            <a class="navbar-brand text-dark" href="#">CASTLE RINGS</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link text-white" href="#">HOME</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white" href="#">ADDRESS</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white" href="#">CONTACT</a>
                    </li>
                   
                </ul>
            </div>
        </div>
    </nav>

    <section class="container py-5">
        <h1 class="display-4 text-dark mb-4">Our Address</h1>
        <p class="lead">Visit us at the following location:</p>
        
        <!-- Address Info -->
        <div class="mb-4">
            <h2 class="text-dark">Castle Rings Store</h2>
            <p class="lead">123 Jewelry Street, City Center, Downtown</p>
            <p class="lead">Phone: +1 234 567 890</p>
            <p class="lead">Email: contact@castlerings.com</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <p>Designed and Developed by V. SHREYA</p>
    </footer>

</body>
</html>

contact
<html>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-warning">
            <div class="container-fluid">
                <a class="navbar-brand text-dark" href="#">CASTLE RINGS</a>
                
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav d-flex">
                        <li class="nav-item " >
                            <a class="nav-link text-white" href="">HOME</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link text-white" href="C:\Users\admin\product.html">ADDRESS</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-white" href="C:\Users\admin\about.html">CONTACT </a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
       
        <div class="row">
            <div class="col-12">
                <h2>Contact Us</h2>
                <form>
                    <div class="form-group">
                        <label for="name">Your Name</label>
                        <input type="text" class="form-control" id="name" placeholder="Enter your name">
                    </div>
                    <div class="form-group">
                        <label for="email">Email address</label>
                        <input type="email" class="form-control" id="email" placeholder="Enter email">
                    </div>
                    <div class="form-group">
                        <label for="message">Message</label>
                        <textarea class="form-control" id="message" rows="3" placeholder="Your message"></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Submit</button>
                </form>
            </div>
        </div>
    </div>
    <footer class="bg-light text-center py-3">
        <p>Designed and Developed by V.SHREYA</p>
    </footer>

    
        
        
    </body>

</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-24 220400.png>)
![alt text](<Screenshot 2024-12-24 220430.png>)
![alt text](<Screenshot 2024-12-24 220446.png>)
![alt text](<Screenshot 2024-12-24 220506.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
