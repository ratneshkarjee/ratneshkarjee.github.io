<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ratnesh Karjee's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background: linear-gradient(to right, #0000ff, #000000);
            color: white;
            padding: 15px;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.5);
            position: relative;
            z-index: 1;
        }
        .header-img {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            opacity: 0.2;
            z-index: -1;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        .profile-img {
            float: left;
            margin-right: 20px;
            border-radius: 5px;
            width: 150px;
            height: auto;
        }
        .rect-img {
            width: 100%;
            height: auto;
            border-radius: 15px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.3);
        }
        .text-justify {
            text-align: justify;
        }
        .section-title {
            font-size: 28px;
            font-weight: bold;
            color: #333;
        }
        .section-content {
            font-size: 18px;
            color: #555;
        }
        .skill-card {
            margin: 10px;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.2);
        }
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .skills-container .skill-card {
            width: 22%;
            margin: 10px;
        }
        .social-icons img {
            width: 30px;
            height: 30px;
            margin: 0 10px;
        }
        .collaborator-img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-right: 10px;
        }
        .collaborator-item {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
        }
        .collaborator-item a {
            color: #000;
            text-decoration: none;
        }
        .collaborator-item a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <img src="images/header_background.gif" alt="Header Background" class="header-img">
        Ratnesh Karjee's Portfolio
    </header>

    <div class="container">
        <!-- Home Section -->
        <section id="home" class="section">
            <h2 class="section-title">Home</h2>
            <img src="images/profile_picture.jpg" alt="Profile Picture" class="profile-img">
            <div class="section-content">
                <h3>Hello, Welcome to Ratnesh's Profile!</h3>
                <p class="text-justify">Curiosity to explore and discover new knowledge and learn new things should form the base for any researcher. Growing up in a village in West Bengal, I was intrigued when I first encountered subjects such as animal behaviour in my bachelor’s degree coursework. These courses helped me better understand the animals I had seen back home, including the human-elephant conflicts in my region. I believe this was the start of my journey in wildlife conservation.</p>
                <div class="social-icons">
                    <a href="mailto:ratneshkarjee@yahoo.com"><img src="icons/email.png" alt="Email"></a>
                    <a href="https://github.com/ratneshkarjee/"><img src="icons/github.png" alt="GitHub"></a>
                    <a href="https://www.researchgate.net/profile/Ratnesh-Karjee"><img src="icons/researchgate.png" alt="ResearchGate"></a>
                    <a href="https://scholar.google.com/citations?user=HtWRd9gAAAAJ&hl=en&authuser=1"><img src="icons/google-scholar.png" alt="Google Scholar"></a>
                </div>
                <img src="images/rectangular_image.jpg" alt="Rectangular Image" class="rect-img">
            </div>
        </section>

        <!-- About Me Section -->
        <section id="about-me" class="section">
            <h2 class="section-title">About Me</h2>
            <img src="images/about.gif" alt="My Picture" class="profile-img">
            <div class="section-content">
                <h3>Hello! I'm <strong>Ratnesh Karjee</strong></h3>
                <p>I am a Wildlife Biologist and currently pursuing Ph.D. from <a href="https://www.ashoka.edu.in/" target="_blank">Ashoka University</a>. Before joining Ashoka's PhD program, I completed my master’s degree in Wildlife & Biodiversity Conservation at North Orissa University. In 2019, I was hired as a research biologist by the Zoological Survey of India. In addition, I have several years of multidisciplinary research experience in various Indian landscapes, as well as competence in Taxonomy, Geospatial data processing, Biodiversity Impact Assessment, and Biodiversity Monitoring. Aside from that, I am passionate about human-animal conflict, landscape ecology, and the effects of climate change on wildlife. I was working at Ashoka University as a Junior Research Fellow on the project “Whole genome sequencing and comparative genomics to study the evolution, genetic diversity, and immunology of bats from the Indian subcontinent. My research interest lies in an integrated approach of modern tools like genomic and GIS to answer various ecological questions. Apart from the academic and research pursuits, I love to play football, volleyball, cricket, etc. Also, I find pleasure in photography, hiking, drawing, and painting.</p>
            </div>
        </section>

        <!-- Skills & Expertise Section -->
        <section id="skills" class="section">
            <h2 class="section-title">Skills & Expertise</h2>
            <div class="skills-container">
                <div class="skill-card">
                    <h3>Conservation Genomics</h3>
                    <p>Expertise in analyzing genetic data to understand conservation challenges.</p>
                </div>
                <div class="skill-card">
                    <h3>Landscape Ecology</h3>
                    <p>Study of landscapes and their ecological processes and interactions.</p>
                </div>
                <div class="skill-card">
                    <h3>Human-Wildlife Interaction</h3>
                    <p>Research on interactions between humans and wildlife to mitigate conflicts.</p>
                </div>
                <div class="skill-card">
                    <h3>Biodiversity Conservation & Management</h3>
                    <p>Strategies and practices for preserving biodiversity and managing ecosystems.</p>
                </div>
            </div>
        </section>

        <!-- Collaborators Section -->
        <section id="collaborators" class="section">
            <h2 class="section-title">Collaborators</h2>
            <div class="section-content">
                <div class="collaborator-item">
                    <img src="images/collaborator1.jpg" alt="Collaborator 1" class="collaborator-img">
                    <a href="http://collaborator1.com" target="_blank">Collaborator 1</a>
                </div>
                <div class="collaborator-item">
                    <img src="images/collaborator2.jpg" alt="Collaborator 2" class="collaborator-img">
                    <a href="http://collaborator2.com" target="_blank">Collaborator 2</a>
                </div>
                <!-- Add more collaborators as needed -->
            </div>
        </section>

        <!-- Publications Section -->
        <section id="publications" class="section">
            <h2 class="section-title">Publications</h2>
            <div class="section-content">
                <ul>
                    <li><strong>2024:</strong> Publication Title</li>
                    <li><strong>2023:</strong> Publication Title</li>
                    <li><strong>2022:</strong> Publication Title</li>
                    <!-- Add more publications as needed -->
                </ul>
            </div>
        </section>

        <!-- Stories & Blogs Section -->
        <section id="stories-blogs" class="section">
            <h2 class="section-title">Stories & Blogs</h2>
            <div class="section-content">
                <ul>
                    <li><strong>2024:</strong> Blog Title</li>
                    <li><strong>2023:</strong> Blog Title</li>
                    <li><strong>2022:</strong> Blog Title
