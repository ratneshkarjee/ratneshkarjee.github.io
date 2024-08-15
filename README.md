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
            min-height: 100vh; /* Full viewport height */
            padding: 80px 0; /* Increased padding for better appearance */
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            background: #f0f0f0; /* Light background color for contrast */
        }

        .profile-img {
            width: 100%;
            max-width: 500px; /* Adjusted size */
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

        .publication-container {
            display: flex;
            align-items: flex-start;
        }

        .publication-container img {
            width: 300px;
            height: auto;
            margin-right: 20px;
        }

        .publication-list {
            max-width: 600px;
        }

        .publication-list ul {
            list-style: none;
            padding: 0;
        }

        .publication-list li {
            margin-bottom: 10px;
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
    <section id="home">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6">
                    <img src="images/profile.jpg" alt="Profile Picture" class="profile-img">
                </div>
                <div class="col-md-6">
                    <h1 class="display-4">Hello, Welcome to Ratnesh's Profile</h1>
                    <p style="text-align: justify;">Curiosity to explore and discover new knowledge and learn new things should form the base for any researcher. Growing up in a village in West Bengal, I was intrigued when I first encountered subjects such as animal behaviour in my bachelor’s degree coursework. These courses helped me better understand the animals I had seen back home, including the human-elephant conflicts in my region. I believe this was the start of my journey in wildlife conservation.</p>
                </div>
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
            <div class="publication-container">
                <img src="images/publications.jpg" alt="Publications" class="img-fluid">
                <div class="publication-list">
                    <ul>
                        <li><strong>Ghosh, D., Karjee, R., and Subramanian, K. A. 2024.</strong> Notes on the Cleptoparasitic Bees from Tawang District in Arunachal Pradesh, India with Special Reference to Family Apidae of Order Hymenoptera. Records of Zoological Survey of India. 124 (iS), 501-512. doi:10.26515/rzsi/v124/i1S/2024/172758</li>
                        <li><strong>Ghosh, D., Chatterjee, P., Karjee, R., and Subramanian, K.A. 2023.</strong> Flower visitor assemblage and foraging profile of a pollinator attractant non-crop plant Isodon coetsa (Buch.-Ham. ex D.Don) Kudô from eastern Himalayas, India. Proceedings of Zoological Society. <a href="https://doi.org/10.1007/s12595-023-00498-x" target="_blank">https://doi.org/10.1007/s12595-023-00498-x</a> [online]</li>
                        <li><strong>Karjee, R., Palei, H. S., Konwar, A., Gogoi, A., & Mishra, R. K. 2022.</strong> Bird assemblages in a peri-urban landscape in eastern India. Birds. 3(4), 383-401 <a href="https://doi.org/10.3390/birds3040026" target="_blank">https://doi.org/10.3390/birds3040026</a> [online]</li>
                        <li><strong>Patra, A., Ahmed, T.M., Karjee, R., and Bhandari, S. 2019.</strong> Sighting of madras tree shrew Anathana ellioti (Waterhouse, 1850) with first photographic evidence at Ajodhya range, district Purulia, West Bengal, India. International Journal of Fauna and Biological Studies. 6(1):41-42</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Collaborators Section -->
    <section id="collaborators">
        <h2 class="display-4 text-center">Collaborators</h2>
        <div class="container">
            <!-- Add content for Collaborators -->
        </div>
    </section>

    <!-- Stories & Blogs Section -->
    <section id="blogs">
        <h2 class="display-4 text-center">Stories & Blogs</h2>
        <div class="container">
            <!-- Add content for Stories & Blogs -->
        </div>
    </section>

    <!-- Footer -->
    <footer class="text-center">
        <p>&copy; 2024 Ratnesh Karjee. All rights reserved.</p>
    </footer>

    <!-- Scripts -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
