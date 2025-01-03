# Project Responsive Web Design using Bootstrap
## Date:

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
    <title>Hey!</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #f8f9fa;
        }
        .navbar {
            background-color: #333;
        }
        .navbar-brand, .nav-link {
            color: #fff !important;
        }
        footer {
            background-color: #333;
        }
        footer p {
            color: #fff;
        }
        .card {
            background-color: #e9ecef;
            border: none;
        }
        .card-title {
            font-size: 1rem;
            font-weight: bold;
        }
        .card-text {
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="#">It's been a long time coming now...🪩</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#shots">Merch</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Write here..💕</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="text-white text-center py-5" style="background-color: #555;">
        <div class="container">
            <h1>Dear Taylor,</h1>
            <p class="lead">A secret vault for Swifties to pen notes to Taylor.</p>
            <a href="#shots" class="btn btn-light btn-lg">Browse Merch🛍️</a>
        </div>
    </header>

    <section id="shots" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">ERAS</h2>
            <div class="row">
                <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                    <div class="card">
                        <img src="tay swift.jpg" class="card-img-top" alt="Shot 1">
                        <div class="card-body">
                            <h5 class="card-title">Taylor Swift</h5>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                    <div class="card">
                        <img src="fearless.jpg" class="card-img-top" alt="Shot 2">
                        <div class="card-body">
                            <h5 class="card-title">Fearless</h5>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                    <div class="card">
                        <img src="speak now.jpg" class="card-img-top" alt="Shot 3">
                        <div class="card-body">
                            <h5 class="card-title">Speak Now</h5>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                    <div class="card">
                        <img src="red.jpg" class="card-img-top" alt="Shot 4">
                        <div class="card-body">
                            <h5 class="card-title">Red</h5>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                    <div class="card">
                        <img src="1989.jpg" class="card-img-top" alt="Shot 5">
                        <div class="card-body">
                            <h5 class="card-title">1989</h5>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                    <div class="card">
                        <img src="rep.jpg" class="card-img-top" alt="Shot 6">
                        <div class="card-body">
                            <h5 class="card-title">Reputation</h5>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                    <div class="card">
                        <img src="lover.jpg" class="card-img-top" alt="Shot 7">
                        <div class="card-body">
                            <h5 class="card-title">Lover</h5>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                    <div class="card">
                        <img src="folklore.jpg" class="card-img-top" alt="Shot 8">
                        <div class="card-body">
                            <h5 class="card-title">Folklore</h5>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                    <div class="card">
                        <img src="evermore.jpg" class="card-img-top" alt="Shot 9">
                        <div class="card-body">
                            <h5 class="card-title">Evermore</h5>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                    <div class="card">
                        <img src="midnight.jpg" class="card-img-top" alt="Shot 10">
                        <div class="card-body">
                            <h5 class="card-title">Midnights</h5>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                    <div class="card">
                        <img src="ttpd.jpg" class="card-img-top" alt="Shot 11">
                        <div class="card-body">
                            <h5 class="card-title">The Tortured Poets Department</h5>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">Write here...✏️</h2>
            <form class="mt-4">
                <div class="mb-3">
                    <label for="name" class="form-label">Name</label>
                    <input type="text" class="form-control" id="name" placeholder="Enter your name">
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter your email">
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Message💗</label>
                    <textarea class="form-control" id="message" rows="4" placeholder="Your message"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Submit</button>
            </form>
        </div>
    </section>

    <footer class="text-white text-center py-3">
        <div class="container">
            <p>Designed by Darshini B (24008783)</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```
## OUTPUT:
![alt text](<Screenshot 2024-12-24 202151.png>)

![alt text](<Screenshot 2024-12-24 202221.png>)

![alt text](<Screenshot 2024-12-24 202317.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
