<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>International Hub</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body { font-family: Arial, sans-serif; }
        .hero { background: linear-gradient(to right, #007bff, #28a745); color: white; padding: 100px 0; text-align: center; }
        .section { padding: 50px 0; }
    </style>
</head>
<body>
    <header class="bg-dark text-white">
        <nav class="navbar navbar-expand-lg navbar-dark container">
            <a class="navbar-brand" href="#">International Hub</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#news">News</a></li>
                    <li class="nav-item"><a class="nav-link" href="#culture">Culture</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="container">
            <h1>Welcome to the International Hub</h1>
            <p>Explore global news, cultures, and connections from around the world.</p>
            <a href="#news" class="btn btn-light btn-lg">Learn More</a>
        </div>
    </section>

    <section id="news" class="section bg-light">
        <div class="container">
            <h2>Latest International News</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://via.placeholder.com/300x200" class="card-img-top" alt="News Image">
                        <div class="card-body">
                            <h5 class="card-title">Global Climate Summit</h5>
                            <p class="card-text">Leaders from 50 countries discuss urgent action on climate change.</p>
                            <a href="#" class="btn btn-primary">Read More</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://via.placeholder.com/300x200" class="card-img-top" alt="News Image">
                        <div class="card-body">
                            <h5 class="card-title">Cultural Exchange Program</h5>
                            <p class="card-text">New initiatives to promote art and music across borders.</p>
                            <a href="#" class="btn btn-primary">Read More</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://via.placeholder.com/300x200" class="card-img-top" alt="News Image">
                        <div class="card-body">
                            <h5 class="card-title">Economic Trends</h5>
                            <p class="card-text">Analysis of international trade and market shifts.</p>
                            <a href="#" class="btn btn-primary">Read More</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="culture" class="section">
        <div class="container">
            <h2>World Cultures</h2>
            <p>Discover diverse traditions, cuisines, and festivals from every continent.</p>
            <div class="row">
                <div class="col-md-6">
                    <h3>Asia</h3>
                    <p>From Japanese tea ceremonies to Indian festivals, explore rich heritages.</p>
                </div>
                <div class="col-md-6">
                    <h3>Europe</h3>
                    <p>Medieval castles, Renaissance art, and modern innovations.</p>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact" class="bg-dark text-white text-center py-4">
        <div class="container">
            <p>&copy; 2023 International Hub. All rights reserved.</p>
            <p>Contact us: info@internationalhub.com</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
