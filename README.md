<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ratnesh Karjee - Portfolio</title>
    <link rel="stylesheet" href="vendor/bootstrap/css/bootstrap.min.css">
    <link rel="stylesheet" href="vendor/font-awesome/css/all.min.css">
    <link rel="stylesheet" href="css/eco.css">
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Header Styles */
        .header {
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            background: linear-gradient(145deg, #f0f0f0, #e0e0e0);
        }

        .navbar {
            background: #fff;
            border-bottom: 2px solid #ddd;
        }

        .navbar-nav .nav-item {
            position: relative;
        }

        .navbar-nav .nav-item.active a {
            background: #009688;
            color: #fff;
            border-radius: 5px;
        }

        .navbar-nav .nav-item a {
            transition: background 0.3s, color 0.3s;
            border-radius: 5px;
        }

        .tab-content {
            margin-top: 80px;
        }

        .tab-pane {
            padding: 20px;
            border-radius: 10px;
            background: #f9f9f9;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .tab-pane[data-color="home"] {
            background-color: #e0f2f1;
        }

        .tab-pane[data-color="about"] {
            background-color: #fce4ec;
        }

        .tab-pane[data-color="research"] {
            background-color: #e8f5e9;
        }

        .tab-pane[data-color="publications"] {
            background-color: #f3e5f5;
        }

        .tab-pane[data-color="collaborators"] {
            background-color: #e1f5fe;
        }

        .tab-pane[data-color="grants"] {
            background-color: #fff9c4;
        }

        .tab-pane[data-color="blogs"] {
            background-color: #e8f0fe;
        }

        .tab-pane[data-color="cv"] {
            background-color: #f1f8e9;
        }

        /* 3D Effect */
        .header {
            perspective: 1000px;
        }

        .navbar {
            transform: rotateX(10deg);
            transform-style: preserve-3d;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <div class="header">
        <nav class="navbar navbar-expand-lg navbar-light">
            <a class="navbar-brand" href="#">Ratnesh Karjee</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item" data-section="home">
                        <a class="nav-link" href="#home" data-toggle="tab">Home</a>
                    </li>
                    <li class="nav-item" data-section="about">
                        <a class="nav-link" href="#about" data-toggle="tab">About Me</a>
                    </li>
                    <li class="nav-item" data-section="research">
                        <a class="nav-link" href="#research" data-toggle="tab">Research Interest</a>
                    </li>
                    <li class="nav-item" data-section="publications">
                        <a class="nav-link" href="#publications" data-toggle="tab">Publications</a>
                    </li>
                    <li class="nav-item" data-section="collaborators">
                        <a class="nav-link" href="#collaborators" data-toggle="tab">Collaborators</a>
                    </li>
                    <li class="nav-item" data-section="grants">
                        <a class="nav-link" href="#grants" data-toggle="tab">Grants & Awards</a>
                    </li>
                    <li class="nav-item" data-section="blogs">
                        <a class="nav-link" href="#blogs" data-toggle="tab">Blogs & Stories</a>
                    </li>
                    <li class="nav-item" data-section="cv">
                        <a class="nav-link" href="#cv" data-toggle="tab">CV</a>
                    </li>
                </ul>
            </div>
        </nav>
    </div>

    <!-- Main Content -->
    <div class="container mt-4">
        <div class="tab-content">
            <!-- Home Tab -->
            <div class="tab-pane fade show active" id="home" data-color="home">
                <div class="row align-items-center">
                    <div class="col-md-4">
                        <img src="images/about.jpg" alt="Ratnesh Karjee" class="img-fluid rounded-circle mb-4">
                    </div>
                    <div class="col-md-8">
                        <h1>Hello, I'm Ratnesh Karjee</h1>
                        <p>Welcome to my page. <>Curiosity to explore and discover new knowledge and learn new things should form the base for any researcher. Growing up in a village in West Bengal, I was intrigued when I first encountered subjects such as animal behaviour in my bachelor’s degree coursework. These courses helped me better understand the animals I had seen back home, including the human-elephant conflicts in my region. I believe this was the start of my journey in wildlife conservation.</p>
                    </div>
                </div>
            </div>

            <!-- About Me Tab -->
            <div class="tab-pane fade" id="about" data-color="about">
                <h2>About Me</h2>
                <img src="images/about.jpg" alt="Ratnesh Karjee" class="img-fluid rounded-circle mb-4">
                <p>Ratnesh pursued his master’s degree in Wildlife & Biodiversity Conservation at North Orissa University after developing an interest in wildlife studies. In 2019, he was hired as a research biologist by the Zoological Survey of India. In addition, he has several years of multidisciplinary research experience in various Indian landscapes, as well as competence in Taxonomy, Geospatial data processing, Biodiversity Impact Assessment, and Biodiversity Monitoring. Aside from that, he is passionate about human-animal conflict, landscape ecology, and the effects of climate change on wildlife. He was working at Ashoka University as a Junior Research Fellow on the project “Whole genome sequencing and comparative genomics to study the evolution, genetic diversity, and immunology of bats from the Indian subcontinent.”</p>
                <p>His interest lies in integrated approaches using modern tools like genomics and GIS to address various ecological questions. Apart from academic and research pursuits, he loves playing football, volleyball, cricket, and finds pleasure in photography, drawing, and painting.</p>
                <p>Email: <a href="mailto:ratneshkarjeeatherasteyahoo.com">ratneshkarjeeatherasteyahoo.com</a></p>
                <p>ResearchGate Profile: <a href="https://www.researchgate.net/profile
