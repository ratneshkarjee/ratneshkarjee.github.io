<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio | Ratnesh Karjee</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/5.3.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            scroll-behavior: smooth;
        }
        .section {
            display: none;
            padding: 50px 0;
        }
        .section.active {
            display: block;
        }
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
            text-align: center;
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
        .nav-buttons {
            text-align: center;
            margin-top: 20px;
        }
        .nav-buttons button {
            margin: 0 10px;
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
                        <a class="nav-link" href="#skills">Skills & Expertise</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#publication">Publication</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#stories">Stories & Blogs</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#cv">CV</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Home Page -->
    <section id="home" class="section active hero-section">
        <div class="container d-flex">
            <div class="hero-text col-md-12">
                <h1>Welcome!</h1>
                <p>Curiosity to explore and discover new knowledge and learn new things should form the base for any researcher. Growing up in a village in West Bengal, I was intrigued when I first encountered subjects such as animal behaviour in my bachelor’s degree coursework. These courses helped me better understand the animals I had seen back home, including the human-elephant conflicts in my region. I believe this was the start of my journey in wildlife conservation.</p>
            </div>
        </div>
    </section>

    <!-- About Me Page -->
    <section id="about" class="section">
        <div class="container text-center">
            <h2>About Me</h2>
            <img src="images/about.jpg" alt="Ratnesh Karjee" class="about-image">
            <p>I am a PhD student at Ashoka University. My research focuses on wildlife and biodiversity conservation. With expertise in taxonomy, geospatial data processing, and more, I am committed to understanding and protecting wildlife.</p>
        </div>
    </section>

    <!-- Skills & Expertise Section -->
    <section id="skills" class="section">
        <div class="container text-center">
            <h2 class="mb-4">Skills & Expertise</h2>
            <div class="row">
                <div class="col-md-3 mb-4">
                    <div class="card skill-card">
                        <img src="images/skills/1.png" alt="Skill 1" class="card-img-top">
                        <div class="card-body">
                            <h5 class="card-title">Skill 1</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                            <a href="#" class="btn btn-primary">Link to course or bootcamp</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 mb-4">
                    <div class="card skill-card">
                        <img src="images/skills/2.png" alt="Skill 2" class="card-img-top">
                        <div class="card-body">
                            <h5 class="card-title">Skill 2</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                            <a href="#" class="btn btn-primary">Link to course or bootcamp</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 mb-4">
                    <div class="card skill-card">
                        <img src="images/skills/3.png" alt="Skill 3" class="card-img-top">
                        <div class="card-body">
                            <h5 class="card-title">Skill 3</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                            <a href="#" class="btn btn-primary">Link to course or bootcamp</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 mb-4">
                    <div class="card skill-card">
                        <img src="images/skills/4.png" alt="Skill 4" class="card-img-top">
                        <div class="card-body">
                            <h5 class="card-title">Skill 4</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                            <a href="#" class="btn btn-primary">Link to course or bootcamp</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Publication Section -->
    <section id="publication" class="section">
        <div class="container text-center">
            <h2 class="mb-4">Publication</h2>
            <p>Details about your publications will be listed here.</p>
        </div>
    </section>

    <!-- Stories & Blogs Section -->
    <section id="stories" class="section">
        <div class="container text-center">
            <h2 class="mb-4">Stories & Blogs</h2>
            <p>Details about your stories and blogs will be listed here.</p>
        </div>
    </section>

    <!-- CV Section -->
    <section id="cv" class="section">
