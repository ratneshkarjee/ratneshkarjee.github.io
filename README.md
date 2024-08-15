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
        .header h1 {
            margin: 0;
        }
        .nav-links {
            margin: 10px 0;
        }
        .nav-links a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        .home-section, .about-section, .skills-section {
            padding: 50px 20px;
        }
        .home-section {
            background-color: #f5f5f5;
        }
        .home-section h1 {
            font-size: 36px;
            color: #333;
        }
        .home-img {
            width: 100%;
            height: 300px;
            object-fit: cover;
            margin-bottom: 20px;
        }
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid #333;
            margin: 0 auto 20px;
            display: block;
            object-fit: cover;
        }
        .about-section h1 {
            font-size: 36px;
            margin-bottom: 20px;
            color: #333;
        }
        .about-text {
            max-width: 800px;
            margin: 0 auto;
            text-align: justify;
            line-height: 1.6;
            font-size: 18px;
            color: #555;
        }
        .skills-section h2 {
            margin-bottom: 30px;
            color: #333;
        }
        .card-img-top {
            height: 200px;
            object-fit: cover;
        }
        .card {
            margin-bottom: 20px;
        }
        @media (min-width: 768px) {
            .card-deck .card {
                margin-bottom: 0;
            }
        }
        @media (max-width: 768px) {
            .about-text {
                font-size: 16px;
                padding: 0 10px;
            }
        }
    </style>
</head>
<body>
    <header class="header">
        <h1>Ratnesh Karjee's Portfolio</h1>
        <div class="nav-links">
            <a href="#home">Home</a>
            <a href="#about">About Me</a>
            <a href="#skills">Skills & Expertise</a>
        </div>
    </header>

    <section id="home" class="home-section">
        <h1 class="text-center">Welcome to My Portfolio</h1>
        <img src="images/home-image.jpg" alt="Home Image" class="home-img">
        <div class="text-center">
            <img src="images/profile.jpg" alt="Profile Picture" class="profile-img">
            <p><strong>Hello, Welcome to Ratnesh's profiles</strong></p>
            <p style="text-align: justify;">Curiosity to explore and discover new knowledge and learn new things should form the base for any researcher. Growing up in a village in West Bengal, I was intrigued when I first encountered subjects such as animal behaviour in my bachelor’s degree coursework. These courses helped me better understand the animals I had seen back home, including the human-elephant conflicts in my region. I believe this was the start of my journey in wildlife conservation.</p>
        </div>
    </section>

    <section id="about" class="about-section">
        <h1 class="text-center">About</h1>
        <img src="images/about.gif" alt="Profile Picture" class="profile-img">
        <div class="about-text">
            <p>Hello! I'm Ratnesh Karjee. I am a Wildlife Biologist and currently pursuing a Ph.D. from <a href="https://www.ashoka.edu.in/" target="_blank">Ashoka University</a>. Before joining Ashoka's PhD program, I completed my master’s degree in Wildlife & Biodiversity Conservation at North Orissa University. In 2019, I was hired as a research biologist by the Zoological Survey of India. In addition, I have several years of multidisciplinary research experience in various Indian landscapes, as well as competence in Taxonomy, Geospatial data processing, Biodiversity Impact Assessment, and Biodiversity Monitoring.</p>
            <p>Apart from that, I am passionate about human-animal conflict, landscape ecology, and the effects of climate change on wildlife. I was working at Ashoka University as a Junior Research Fellow on the project “Whole genome sequencing and comparative genomics to study the evolution, genetic diversity, and immunology of bats from the Indian subcontinent.” My research interest lies in an integrated approach of modern tools like genomic and GIS to answer various ecological questions. Apart from academic and research pursuits, I love to play football, volleyball, cricket, etc. Also, I find pleasure in photography, hiking, drawing, and painting.</p>
        </div>
    </section>

    <section id="skills" class="skills-section">
        <h2 class="text-center">Skills & Expertise</h2>
        <div class="container">
            <div class="row">
                <div class="col-md-6 col-lg-3">
                    <div class="card">
                        <img src="images/1.jpg" class="card-img-top" alt="Skill 1">
                        <div class="card-body">
                            <h5 class="card-title">Conservtion Genomics</h5>
                            <p class="card-text">Expertise in analyzing genetic data to understand conservation challenges.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-3">
                    <div class="card">
                        <img src="images/2.jpg" class="card-img-top" alt="Skill 2">
                        <div class="card-body">
                            <h5 class="card-title">Landscape Ecology</h5>
                            <p class="card-text">Study of landscapes and their ecological processes and interactions.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-3">
                    <div class="card">
                        <img src="images/3.jpg" class="card-img-top" alt="Skill 3">
                        <div class="card-body">
                            <h5 class="card-title">Human-Wildlife Interaction</h5>
                            <p class="card-text">Research on interactions between humans and wildlife to mitigate conflicts.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-3">
                    <div class="card">
                        <img src="images/4.jpg" class="card-img-top" alt="Skill 4">
                        <div class="card-body">
                            <h5 class="card-title">Biodiversity Conservation & Management</h5>
                            <p class="card-text">Strategies and practices for preserving biodiversity and managing ecosystems.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
