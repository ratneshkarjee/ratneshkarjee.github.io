<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            background: linear-gradient(to right, #0000ff, #000000);
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        .sticky-nav {
            background-color: #333;
            color: white;
            padding: 10px 0;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .sticky-nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        .sticky-nav a:hover {
            text-decoration: underline;
        }
        .container {
            margin-top: 60px; /* Adjust this if needed */
        }
        .section-heading {
            text-align: center;
            margin: 40px 0;
        }
        .about-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid #000;
        }
        .card-img-top {
            width: 100%;
            height: auto; /* Maintains the original aspect ratio */
        }
        .card-deck {
            margin-top: 20px;
        }
        .card {
            margin-bottom: 20px;
        }
        #home {
            padding: 60px 0; /* Adjust padding if needed */
        }
        #home .row {
            display: flex;
            align-items: center;
        }
        #home img {
            max-height: 300px; /* Ensure the image doesn’t exceed this height */
            width: 100%;
            object-fit: cover;
        }
        #home .col-md-6 {
            padding: 15px;
        }
        #home h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        #home p {
            font-size: 1.25rem;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <!-- Sticky Navigation Bar -->
    <nav class="sticky-nav navbar navbar-expand-lg navbar-dark">
        <a class="navbar-brand" href="#home">Portfolio</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
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
                    <a class="nav-link" href="#stories">Stories & Blogs</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="container text-center mt-5">
        <div class="row align-items-center">
            <div class="col-md-6">
                <img src="images/profile.jpg" alt="Profile Picture" class="img-fluid" style="width: 100%; max-height: 300px; object-fit: cover;">
            </div>
            <div class="col-md-6">
                <h1 class="display-4">Hello, Welcome to Ratnesh's Profile</h1>
                <p style="text-align: justify;">Curiosity to explore and discover new knowledge and learn new things should form the base for any researcher. Growing up in a village in West Bengal, I was intrigued when I first encountered subjects such as animal behaviour in my bachelor’s degree coursework. These courses helped me better understand the animals I had seen back home, including the human-elephant conflicts in my region. I believe this was the start of my journey in wildlife conservation.</p>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="container text-center mt-5">
        <h2 class="section-heading">About</h2>
        <img src="images/about.jpg" alt="About Me" class="about-img mb-4">
        <p style="text-align: justify;">Hello! I'm <strong>Ratnesh Karjee</strong>. I am a Wildlife Biologist and currently pursuing a Ph.D. from <a href="https://www.ashoka.edu.in/" target="_blank">Ashoka University</a>. Before joining Ashoka's PhD program, I completed my master’s degree in Wildlife & Biodiversity Conservation at North Orissa University. In 2019, I was hired as a research biologist by the Zoological Survey of India. In addition, I have several years of multidisciplinary research experience in various Indian landscapes, as well as competence in Taxonomy, Geospatial data processing, Biodiversity Impact Assessment, and Biodiversity Monitoring. Aside from that, I am passionate about human-animal conflict, landscape ecology, and the effects of climate change on wildlife. I was working at Ashoka University as a Junior Research Fellow on the project “Whole genome sequencing and comparative genomics to study the evolution, genetic diversity, and immunology of bats from the Indian subcontinent.</p>
        <p style="text-align: justify;">My research interest lies in the integrated approach of modern tools like genomic and GIS to answer various ecological questions. Apart from academic and research pursuits, I love to play football, volleyball, cricket, etc. Also, I find pleasure in photography, hiking, drawing, and painting.</p>
    </section>

    <!-- Skills & Expertise Section -->
    <section id="skills" class="container mt-5">
        <h2 class="section-heading">Skill & Expertise</h2>
        <div class="card-deck">
            <div class="card">
                <img src="images/1.jpg" class="card-img-top" alt="Conservation Genomics">
                <div class="card-body">
                    <h5 class="card-title">Conservation Genomics</h5>
                    <p class="card-text">Description of Conservation Genomics and related skills.</p>
                </div>
            </div>
            <div class="card">
                <img src="images/2.jpg" class="card-img-top" alt="Landscape Ecology">
                <div class="card-body">
                    <h5 class="card-title">Landscape Ecology</h5>
                    <p class="card-text">Description of Landscape Ecology and related skills.</p>
                </div>
            </div>
            <div class="card">
                <img src="images/3.jpg" class="card-img-top" alt="Human-Wildlife Conflict">
                <div class="card-body">
                    <h5 class="card-title">Human-Wildlife Conflict</h5>
                    <p class="card-text">Description of Human-Wildlife Conflict and related skills.</p>
                </div>
            </div>
            <div class="card">
                <img src="images/4.jpg" class="card-img-top" alt="Climate Change Impacts">
                <div class="card-body">
                    <h5 class="card-title">Climate Change Impacts</h5>
                    <p class="card-text">Description of Climate Change Impacts and related skills.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="text-center mt-5">
        <p>&copy; 2024 Ratnesh Karjee. All rights reserved.</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
