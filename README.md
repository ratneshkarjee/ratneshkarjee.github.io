<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ratnesh Karjee - Portfolio</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }
        header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            background: rgba(0, 0, 0, 0.8);
            color: #fff;
            padding: 10px 0;
            z-index: 1000;
        }
        header nav {
            display: flex;
            justify-content: center;
            align-items: center;
        }
        header nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
            transition: color 0.3s;
        }
        header nav a:hover {
            color: #f8f9fa;
        }
        section {
            padding: 80px 20px 20px;
            min-height: 100vh;
        }
        #home {
            background: url('images/home-bg.jpg') no-repeat center center;
            background-size: cover;
            color: #fff;
            text-align: center;
        }
        #home h1, #home p {
            margin: 0;
        }
        #about img {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 50%;
            border: 5px solid #007bff;
        }
        #projects .card {
            margin-bottom: 20px;
        }
        #skills .card {
            margin-bottom: 20px;
        }
        #contact {
            background-color: #343a40;
            color: #fff;
        }
        #contact .icon {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background-color: #007bff;
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 10px;
        }
        #contact .icon img {
            width: 24px;
            height: 24px;
        }
    </style>
</head>
<body>

<header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Me</a>
        <a href="#skills">Skills & Expertise</a>
        <a href="#projects">Projects</a>
        <a href="#collaborators">Collaborators</a>
        <a href="#publication">Publication</a>
        <a href="#stories">Stories & Blogs</a>
        <a href="#cv">CV</a>
        <a href="#contact">Contact Me</a>
    </nav>
</header>

<section id="home" class="text-center">
    <div class="container">
        <div class="row">
            <div class="col-md-6">
                <img src="images/profile.jpg" alt="Ratnesh Karjee" class="img-fluid rounded-circle">
            </div>
            <div class="col-md-6">
                <h1>Hello, I'm Ratnesh Karjee</h1>
                <p>Curiosity to explore and discover new knowledge and learn new things should form the base for any researcher. Growing up in a village in West Bengal, I was intrigued when I first encountered subjects such as animal behaviour in my bachelor’s degree coursework. These courses helped me better understand the animals I had seen back home, including the human-elephant conflicts in my region. I believe this was the start of my journey in wildlife conservation.</p>
            </div>
        </div>
    </div>
</section>

<section id="about">
    <div class="container text-center">
        <h2>About Me</h2>
        <div class="row justify-content-center">
            <div class="col-md-4 mb-4">
                <img src="images/about.jpg" alt="Ratnesh Karjee">
            </div>
            <div class="col-md-8">
                <p>
                    I am Ratnesh Karjee, a Wildlife Biologist currently pursuing a Ph.D. in Biology at <a href="https://www.ashoka.edu.in/" target="_blank">Ashoka University</a>. Before joining Ashoka University, I completed my master’s degree in Wildlife & Biodiversity Conservation at North Orissa University, where my fascination with wildlife studies began. In 2019, I joined the Zoological Survey of India as a research biologist. My research spans various Indian landscapes, focusing on Taxonomy, Geospatial data processing, Biodiversity Impact Assessment, and Biodiversity Monitoring.
                </p>
                <p>
                    My passion extends to understanding human-animal conflicts, landscape ecology, and the impacts of climate change on wildlife. At Ashoka University, as a Junior Research Fellow, I am involved in a project on “Whole genome sequencing and comparative genomics to study the evolution, genetic diversity, and immunology of bats from the Indian subcontinent.”
                </p>
                <p>
                    I am particularly interested in using modern tools like genomics and GIS to address various ecological questions. Outside of my academic and research endeavors, I enjoy playing football, volleyball, and cricket, as well as photography, drawing, and painting.
                </p>
            </div>
        </div>
    </div>
</section>

<section id="skills">
    <div class="container text-center">
        <h2>Skills & Expertise</h2>
        <div class="row">
            <div class="col-md-3">
                <div class="card">
                    <img src="images/skills/1.png" class="card-img-top" alt="Skill 1">
                    <div class="card-body">
                        <h5 class="card-title">Python</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla vel purus et dolor dictum cursus.</p>
                        <a href="#" class="btn btn-primary">Link to course or bootcamp</a>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="images/skills/2.png" class="card-img-top" alt="Skill 2">
                    <div class="card-body">
                        <h5 class="card-title">Data Visualization</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla vel purus et dolor dictum cursus.</p>
                        <a href="#" class="btn btn-primary">Link to course or bootcamp</a>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="images/skills/3.png" class="card-img-top" alt="Skill 3">
                    <div class="card-body">
                        <h5 class="card-title">SQL</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla vel purus et dolor dictum cursus.</p>
                        <a href="#" class="btn btn-primary">Link to course or bootcamp</a>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="images/skills/4.png" class="card-img-top" alt="Skill 4">
                    <div class="card-body">
                        <h5 class="card-title">Data Storytelling</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla vel purus et dolor dictum cursus.</p>
                        <a href="#" class="btn btn-primary">Link to course or bootcamp</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="projects">
    <div class="container text-center">
        <h2>Projects</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <img src="images/projects/1.jpg" class="card-img-top" alt="Project 1">
                    <div class="card-body">
                        <h5 class="card-title">Project 1</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla vel purus et dolor dictum cursus.</p>
                        <a href="#" class="btn btn-primary">Blog Post</a>
                        <a href="#" class="btn btn-secondary">Source Code</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="images/projects/2.jpg" class="card-img-top" alt="Project 2">
                    <div class="card-body">
                        <h5 class="card-title">Project 2</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur
