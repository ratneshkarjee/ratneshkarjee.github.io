<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio | Ratnesh Karjee</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/5.3.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        .hero-section {
            background: url('images/hero-bg.jpg') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            align-items: center;
            position: relative;
            overflow: hidden;
        }
        .hero-section::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('images/header-image1.jpg') no-repeat center center/cover;
            opacity: 0.5;
            z-index: 1;
        }
        .hero-section::after {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('images/header-image2.jpg') no-repeat center center/cover;
            opacity: 0.3;
            z-index: 2;
        }
        .hero-text {
            color: white;
            position: relative;
            z-index: 3;
        }
        .hero-image img {
            border-radius: 50%;
            border: 5px solid #fff;
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
        .about-image {
            border-radius: 50%;
            border: 5px solid #000;
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
        .card-img-top {
            height: 180px;
            object-fit: cover;
        }
        .skill-card img {
            width: 100px;
            height: 100px;
        }
        .contact-icon {
            background-color: pink;
            border-radius: 50%;
            padding: 10px;
            margin: 5px;
            display: inline-block;
            color: white;
        }
        .contact-icon:hover {
            background-color: #e91e63;
            cursor: pointer;
        }
        .contact-section {
            background-color: #333;
            color: white;
            padding: 50px 0;
        }
    </style>
</head>
<body>
    <!-- Header Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Ratnesh Karjee</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About Me</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#projects">Projects</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#skills">Skills</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact Me</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#cv">CV</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Home Page -->
    <section id="home" class="hero-section">
        <div class="container d-flex">
            <div class="hero-text col-md-6">
                <div class="hero-image mb-4">
                    <img src="images/about.jpg" alt="Ratnesh Karjee">
                </div>
                <h1>Hello, I'm Ratnesh Karjee</h1>
                <p>Welcome to my page. I am a PhD student at Ashoka University with a passion for wildlife studies and research. Explore my work and connect with me!</p>
            </div>
        </div>
    </section>

    <!-- About Me Page -->
    <section id="about" class="py-5 text-center">
        <h2>About Me</h2>
        <div id="aboutCarousel" class="carousel slide">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="images/about1.jpg" alt="About Image 1">
                </div>
                <div class="carousel-item">
                    <img src="images/about2.jpg" alt="About Image 2">
                </div>
                <div class="carousel-item">
                    <img src="images/about3.jpg" alt="About Image 3">
                </div>
            </div>
            <a class="carousel-control-prev" href="#aboutCarousel" role="button" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </a>
            <a class="carousel-control-next" href="#aboutCarousel" role="button" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </a>
        </div>
        <div class="mt-4">
            <img src="images/about.jpg" alt="Ratnesh Karjee" class="about-image">
            <p>Ratnesh Karjee is Ph.D student at Ashoka University. Ratnesh pursued his master’s degree in Wildlife & Biodiversity Conservation at North Orissa University after developing an interest in wildlife studies. In 2019, he was hired as a research biologist by the Zoological Survey of India. In addition, he has several years of multidisciplinary research experience in various Indian landscapes, as well as competence in Taxonomy, Geospatial data processing, Biodiversity Impact Assessment, and Biodiversity Monitoring. Aside from that, he is passionate about human-animal conflict, landscape ecology, and the effects of climate change on wildlife. He was working at Ashoka University as a Junior Research Fellow on the project “Whole genome sequencing and comparative genomics to study the evolution, genetic diversity, and immunology of bats from the Indian subcontinent.”His interest lies in integrated approach of modern tools like genomic and GIS to answer various ecological question. Apart from the academic and research pursuits, he loves to paly football, vollyball, cricket etc. Also, he finds pleasure in photography, drawing and painting.</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-5">
        <div class="container text-center">
            <h2 class="mb-4">Projects</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="images/projects/1.jpg" class="card-img-top" alt="Project 1">
                        <div class="card-body">
                            <h5 class="card-title">Project 1</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                            <a href="#" class="btn btn-primary">Blog Post</a>
                            <a href="#" class="btn btn-secondary">Source Code</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="images/projects/2.jpg" class="card-img-top" alt="Project 2">
                        <div class="card-body">
                            <h5 class="card-title">Project 2</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                            <a href="#" class="btn btn-primary">Blog Post</a>
                            <a href="#" class="btn btn-secondary">Source Code</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="images/projects/3.jpg" class="card-img-top" alt="Project 3">
                        <div class="card-body">
                            <h5 class="card-title">Project 3</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                            <a href="#" class="btn btn-primary">Blog Post</a>
                            <a href="#" class="btn btn-secondary">Source Code</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-5">
        <div class="container text-center">
            <h2 class="mb-4">Skills</h2>
            <div class="row">
                <div class="col-md-3 mb-4">
                    <div class="card skill-card">
                        <img src="images/skills/1
