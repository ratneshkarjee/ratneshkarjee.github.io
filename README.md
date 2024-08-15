<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ratnesh Karjee's Portfolio</title>
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <!-- Custom CSS -->
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Custom styles for the portfolio */
        .profile-picture {
            width: 200px;
            height: auto;
            max-width: 600px;
            border-radius: 10px;
        }
        .about-image {
            width: 100%;
            height: auto;
            max-width: 800px;
            border-radius: 10px;
        }
        .about-text {
            text-align: justify;
        }
        .section {
            padding: 60px 0;
        }
        .section-heading {
            margin-bottom: 40px;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
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
                    <a class="nav-link" href="#about">About Me</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#skills">Skills & Expertise</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#publications">Selected Publications</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contact">Contact Me</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="section">
        <div class="container text-center">
            <div class="row align-items-center">
                <div class="col-md-6">
                    <img src="images/profile-rmbg.png" class="profile-picture" alt="Profile Picture">
                </div>
                <div class="col-md-6 text-left">
                    <h1>Welcome to My Scientific World</h1>
                    <p>Hi, Welcome to my portfolio where you can explore my research, skills, and publications. My curiosity to explore and discover new skills and gained knowledges for any research. I believe that this is the foundation of an excellent researcher. Growing up in a village of Purulia District in West Bengal, I was intrigued when I first encountered subjects such as animal behaviour in my Bachelor’s degree coursework. These courses helped me better understand the animals I had seen during my childhood, including the rolling eggs of hens, defensive behaviour of chickens, and human-elephant conflicts in my region. I believe this was the start of my journey in wildlife studies. If my research interests and skills resonate with you, I would be delighted to explore potential collaboration opportunities in the future. Please feel free to reach out if you're interested in working together!</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Me Section -->
    <section id="about" class="section bg-light">
        <div class="container">
            <h2 class="section-heading text-center">About Me</h2>
            <div class="row">
                <div class="col-md-6">
                    <img src="images/about.gif" class="about-image" alt="About Me">
                </div>
                <div class="col-md-6 about-text">
                    <p>I'm Ratnesh Karjee, a Wildlife Biologist currently pursuing a Ph.D. in Biology at <a href="https://www.ashoka.edu.in" target="_blank">Ashoka University</a>. The theme of my doctoral research is based on understanding the influence of the Anthropocene and climate change on small mammals, particularly bats and rodents, across India’s key biodiversity hotspots—the Northeast (NEI) and the Western Ghats (WG). Both the regions are globally recognized for their rich biodiversity and unique ecological significance. I earned my master’s degree in wildlife & Biodiversity Conservation from <a href="https://www.nou.nic.in/" target="_blank">North Orissa University</a> and have previously worked as a research biologist at the <a href="https://zsi.gov.in/" target="_blank">Zoological Survey of India</a>. In addition, I have muldisciplinary research experience in various domain of biology like taxonomy, geospatial data processing, biodiversity impact assessment, and monitoring. My deep commitment to addressing human-animal conflicts, coupled with a passion for landscape ecology, fuels my research. I was also engaged in an innovative project on bat genomics at Ashoka University. Moreover, I am interested in integrating advanced genomics techniques and GIS tools to push the boundaries of ecological research and enhance our understanding for sustainable conservation practice.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills & Expertise Section -->
    <section id="skills" class="section bg-light">
        <div class="container">
            <h2 class="section-heading text-center">Skills & Expertise</h2>
            <div class="row">
                <!-- Skill Card 1 -->
                <div class="col-md-3">
                    <div class="card">
                        <img src="remote.jpg" class="card-img-top" alt="RS & GIS Icon">
                        <div class="card-body">
                            <h5 class="card-title">Remote Sensing & GIS</h5>
                            <p class="card-text">I am proficient in geospatial modelling (including Species Distribution Modelling). Apart from this, I use to teach and provide technical assistance to graduate students, interns, and professionals in RS and GIS. In addition, I can handle various software like QGIS, ArcGIS, GeoDa, Google Earth Engine, and Diva-GIS.</p>
                        </div>
                    </div>
                </div>
                <!-- Skill Card 2 -->
                <div class="col-md-3">
                    <div class="card">
                        <img src="genomics.jpg" class="card-img-top" alt="Molecular Biology Icon">
                        <div class="card-body">
                            <h5 class="card-title">Molecular & Ecological Data Analysis</h5>
                            <p class="card-text">I have expertise in analyzing ecological and genomic data using various software such as R, PopArt, DnaSP, and MEGA.</p>
                        </div>
                    </div>
                </div>
                <!-- Skill Card 3 -->
                <div class="col-md-3">
                    <div class="card">
                        <img src="field.jpg" class="card-img-top" alt="Field Experience Icon">
                        <div class="card-body">
                            <h5 class="card-title">Field Experience</h5>
                            <p class="card-text">I have five years of working experience in various landscapes of India like the Eastern & Western Himalayas, Western Ghats, Gangetic Flood Plain, Chotanagpur, etc., which helps me to gain systematic study design, conduct field surveys, data collection, and lead team members. In addition, my expertise in monitoring wildlife using non-invasive sampling methods like camera traps, fecal, and sign surveys.</p>
                        </div>
                    </div>
                </div>
                <!-- Skill Card 4 -->
                <div class="col-md-3">
                    <div class="card">
                        <img src="biodiv.png" class="card-img-top" alt="Biodiversity Monitoring">
                        <div class="card-body">
                            <h5 class="card-title">Biodiversity Monitoring, Conservation & Impact Assessment</h5>
                            <p class="card-text">I possess expertise in conducting systematic field studies to assess biodiversity (invertebrates and vertebrates). I can design experiment for biodiversity management and impact assessment for sustainable conservation practices. In addition, during my master’s course, I also prepared People Biodiversity Register (PBR) using both Traditional Ecological Knowledge (TEK) and scientific methods. Furthermore, I can identify bats, scorpions, and centipedes through morphological taxonomy.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Selected Publications Section -->
    <section id="publications" class="section">
        <div class="container">
            <h2 class="section-heading text-center">Selected Publications</h2>
            <ul class="list-unstyled">
                <li><strong>Ghosh, D., <span class="font-weight-bold">Karjee, R.</span>, and Subramanian, K. A. 2024.</strong> Notes on the Cleptoparasitic Bees from Tawang District of Arunachal Pradesh, India (Hymenoptera: Apidae: Nomadinae). <em>Journal of Threatened Taxa</em>.</li>
                <li><strong>Karjee, R., Das, A. K., Ghosh, D., and Raghavan, R. 2023.</strong> Population structure of isolated Indian populations of the Little River Tern Sterna aurantia. <em>Avian Research</em>. <a href="https://doi.org/10.1007/s40479-023-00045-w">https://doi.org/10.1007/s40479-023-00045-w</a></li>
                <li><strong>Karjee, R., and Ghosh, D. 2022.</strong> Human-elephant conflict in the changing landscape of Eastern Ghats, India. <em>Biodiversity and Conservation</em>. <a href="https://doi.org/10.1007/s10531-022-02484-3">https://doi.org/10.1007/s10531-022-02484-3</a></li>
                <li><strong>Ghosh, D., <span class="font-weight-bold">Karjee, R.</span>, and Mondal, M. 2021.</strong> A new species of cricket frog (Amphibia: Anura: Dicroglossidae) from the Eastern Himalayas, India. <em>Salamandra</em>.</li>
                <li><strong>Karjee, R. 2021.</strong> Notes on the butterfly diversity of the forests of Purulia, West Bengal, India. <em>Journal of Insect Biodiversity</em>.</li>
            </ul>
        </div>
    </section>

    <!-- Contact Me Section -->
    <section id="contact" class="section bg-light">
        <div class="container text-center">
            <h2 class="section-heading">Contact Me</h2>
            <p>If you'd like to get in touch, feel free to reach out through any of the following platforms:</p>
            <div class="d-flex justify-content-center">
                <a href="mailto:ratnesh@example.com"><img src="icons/email.png" alt="Email Icon"></a>
                <a href="https://scholar.google.com" target="_blank"><img src="icons/scholar.png" alt="Google Scholar Icon"></a>
                <a href="https://www.researchgate.net" target="_blank"><img src="icons/researchgate.png" alt="ResearchGate Icon"></a>
                <a href="https://github.com/ratneshkarjee" target="_blank"><img src="icons/github.png" alt="GitHub Icon"></a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="text-center py-4">
        <p>&copy; 2024 Ratnesh Karjee. All rights reserved.</p>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
