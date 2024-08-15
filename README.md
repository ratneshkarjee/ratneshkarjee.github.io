<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ratnesh Karjee Portfolio</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        /* Sticky Navigation Bar */
        .navbar {
            background: linear-gradient(to right, #0033cc, #000000);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .navbar-nav .nav-link {
            color: #ffffff !important;
            font-weight: bold;
        }

        .navbar-nav .nav-link:hover {
            color: #cccccc !important;
        }

        /* Home Section */
        #home {
            padding: 60px 0;
        }

        .profile-img {
            width: 100%;
            max-width: 900px; /* Adjusted size */
            height: auto;
            margin: 0 auto;
        }

        /* About Section */
        #about {
            padding: 60px 0;
            text-align: center;
        }

        .about-img {
            width: 120px; /* Adjusted size */
            height: 120px; /* Adjusted size */
            border-radius: 50%;
            border: 5px solid #333;
            margin-bottom: 20px;
        }

        /* Skill & Expertise Section */
        #skills {
            padding: 60px 0;
        }

        .card {
            margin: 10px 0;
            border: none;
            border-radius: 10px;
        }

        .card-img-top {
            height: 180px; /* Adjusted size */
            object-fit: cover;
        }

        /* Publication Section */
        #publications {
            padding: 60px 0;
        }

        /* Collaborators Section */
        #collaborators {
            padding: 60px 0;
        }

        /* Stories & Blogs Section */
        #blogs {
            padding: 60px 0;
        }

        /* Footer */
        footer {
            background-color: #f8f9fa;
            padding: 10px;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
        <a class="navbar-brand" href="#">Ratnesh Karjee</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link" href="#home">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#about">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#skills">Skill & Expertise</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#publications">Publication</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#collaborators">Collaborators</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#blogs">Stories & Blogs</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="container text-center mt-5">
        <div class="row align-items-center">
            <div class="col-md-6">
                <img src="images/profile.jpg" alt="Profile Picture" class="profile-img">
            </div>
            <div class="col-md-6">
                <h1 class="display-4">Hello, Welcome to Ratnesh's Profile</h1>
                <p style="text-align: justify;">Curiosity to explore and discover new knowledge and learn new things should form the base for any researcher. Growing up in a village in West Bengal, I was intrigued when I first encountered subjects such as animal behaviour in my bachelor’s degree coursework. These courses helped me better understand the animals I had seen back home, including the human-elephant conflicts in my region. I believe this was the start of my journey in wildlife conservation.</p>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2 class="display-4">About</h2>
        <img src="images/about.jpg" alt="About Me" class="about-img">
        <p>Hello! I'm Ratnesh Karjee. I am a Wildlife Biologist currently pursuing a Ph.D. from <a href="https://www.ashoka.edu.in/" target="_blank">Ashoka University</a>. Before joining Ashoka's PhD program, I completed my master’s degree in Wildlife & Biodiversity Conservation at North Orissa University. In 2019, I was hired as a research biologist by the Zoological Survey of India. In addition, I have several years of multidisciplinary research experience in various Indian landscapes, as well as competence in Taxonomy, Geospatial data processing, Biodiversity Impact Assessment, and Biodiversity Monitoring. Aside from that, I am passionate about human-animal conflict, landscape ecology, and the effects of climate change on wildlife. I was working at Ashoka University as a Junior Research Fellow on the project “Whole genome sequencing and comparative genomics to study the evolution, genetic diversity, and immunology of bats from the Indian subcontinent.</p>
        <p>My research interest lies in integrated approach of modern tools like genomic and GIS to answer various ecological question. Apart from the academic and research pursuits, I love to play football, volleyball, cricket etc. Also, I find pleasure in photography, hiking, drawing and painting.</p>
    </section>

    <!-- Skill & Expertise Section -->
    <section id="skills">
        <h2 class="display-4 text-center">Skill & Expertise</h2>
        <div class="container">
            <div class="row">
                <div class="col-md-3">
                    <div class="card">
                        <img src="images/1.jpg" class="card-img-top" alt="Conservation Genomics">
                        <div class="card-body">
                            <h5 class="card-title">Conservation Genomics</h5>
                            <p class="card-text">Description of Conservation Genomics and related skills.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="images/2.jpg" class="card-img-top" alt="Landscape Ecology">
                        <div class="card-body">
                            <h5 class="card-title">Landscape Ecology</h5>
                            <p class="card-text">Description of Landscape Ecology and related skills.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="images/3.jpg" class="card-img-top" alt="Human-Wildlife Conflict">
                        <div class="card-body">
                            <h5 class="card-title">Human-Wildlife Conflict</h5>
                            <p class="card-text">Description of Human-Wildlife Conflict and related skills.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="images/4.jpg" class="card-img-top" alt="Climate Change Impacts">
                        <div class="card-body">
                            <h5 class="card-title">Climate Change Impacts</h5>
                            <p class="card-text">Description of Climate Change Impacts and related skills.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Publication Section -->
    <section id="publications">
        <h2 class="display-4 text-center">Publications</h2>
        <div class="container">
            <ul>
                <li><strong>2024:</strong> Title of Recent Publication - <a href="link-to-publication">Link</a></li>
                <li><strong>2023:</strong> Title of Another Publication - <a href="link-to-publication">Link</a></li>
                <li><strong>2022:</strong> Title of Earlier Publication - <a href="link-to-publication">Link</a></li>
                <li><strong>2021:</strong> Title of Previous Publication - <a href="link-to-publication">Link</a></li>
                <li><strong>2020:</strong> Title of Older Publication - <a href="link-to-publication">Link</a></li>
                <li><strong>2019:</strong> Title of the First Publication - <a href="link-to-publication">Link</a></li>
            </ul>
       
