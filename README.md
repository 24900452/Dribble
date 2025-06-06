# Project Responsive Web Design using Bootstrap
## Date:30.05.25

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
<html>
<head>
    <meta charset="UTF-8">
    <title>Dribble</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand fw-bold text-danger" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item"><a class="nav-link text-white" href="#">Shots</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Designers</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Teams</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Community</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Jobs</a></li>
                </ul>
            </div>
            <a class="btn btn-outline-light me-2" href="#">Sign in</a>
            <a class="btn btn-outline-light me-2" href="#">Sign Up</a>
            <input type="search" class="form-control w-auto" placeholder="Search" style="margin: 20px;">
        </div>
    </nav>

    <section id="home" class="bg-white py-5"  style="height: 45vh;" >
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6 text-center text-md-middle">
                    <h1 class="display-4 fw-bold">Wanna make things work?</h1>
                    <p class="my-3">Dribbble is a show-and-tell platform for designers.</p>
                    <button class="btn btn-secondary me-2">Learn More</button>
                    <button class="btn btn-primary">Sign up</button>
                </div>
                <div class="col-md-6 text-center">
                    <img src="home.jpg" class="img-fluid" alt="Design Work" style="height: 45vh;">
                </div>
            </div>
        </div>
    </section>

    <section class="py-5">
        <div class="container">
            <div class="row mb-4">
                <div class="col-md-4">
                    <h2 class="fw-bold">Popular</h2>
                </div>
                <div class="col-md-4 text-center">
                    <button class="btn btn-light btn-secondary btn-outline-dark">Now</button>
                    <button class="btn btn-light btn-secondary btn-outline-dark">Shots</button>
                </div>
            </div>
            <div class="row g-4">
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="img1.jpg" width="300" height="225">
                      
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Design Studio</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="coffee.jpg" width="300" height="225">
                        
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Kaffeteria</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="dawg.jpg" width="300" height="225">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Scenary pops</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="speak out.jpg" width="300" height="225">
                       
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Speak out</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="dogreat.jpg" width="300" height="225">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Greatbuys</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="stars.jpg" width="300" height="225">
                        
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Gazing</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="key.jpg"width="300" height="225">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Keys</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="man.jpg" width="300" height="225">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Manhole</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        </div>
    </section>
    <footer class="bg-dark text-white py-3">
        <div class="container text-center">
            <p class="mb-0">&copy; Works By JOTHI 2025</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```


## OUTPUT:

![alt text](image.png)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
