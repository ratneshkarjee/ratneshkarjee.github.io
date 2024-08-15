<! DOCTYPE html >
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Title -->
    <title>Ratnesh Karjee</title>
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <!-- Custom CSS -->
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Custom styles for the portfolio */
        .profile-picture {
            width: 200px;
            height: auto;
            border-radius: 10px;
        }
        .about-image {
            width: 100%;
            height: auto;
            max-width: 600px;
            border: 5px solid #ddd;
        }
        .about-text {
            text-align: justify;
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
                    <h1>Welcome to My Scientific Portfolio</h1>
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
                    <p>I'm Ratnesh Karjee, a Wildlife Biologist currently pursuing a Ph.D. in Biology at <a href="https://www.ashoka.edu.in" target="_blank">Ashoka University</a>. I completed my master's degree in Wildlife & Biodiversity Conservation at North Orissa University and worked as a research biologist at the Zoological Survey of India. My multidisciplinary research experience spans various Indian landscapes, with expertise in Taxonomy, Geospatial data processing, Biodiversity Impact Assessment, and Biodiversity Monitoring. I am passionate about human-animal conflict, landscape ecology, and climate change impacts on wildlife. Currently, I'm also involved in a project on bat genomics at Ashoka University, integrating modern tools like genomics and GIS for ecological research.</p>
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
                            <a href="#" class="btn btn-primary">Link to course or bootcamp</a>
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
                        <img src="images/field_experience_icon.png" class="card-img-top" alt="Field Experience Icon">
                        <div class="card-body">
                            <h5 class="card-title">Field Experience</h5>
                            <p class="card-text">I have five years of working experience in various landscapes of India like the Eastern & Western Himalayas, Western Ghats, Gangetic Flood Plain, Chotanagpur, etc., which helps me to gain systematic study design, conduct field surveys, data collection, and lead team members. In addition, my expertise in monitoring wildlife using non-invasive sampling methods like camera traps, fecal, and sign surveys.</p>
                        </div>
                    </div>
                </div>
                <!-- Skill Card 4 -->
                <div class="col-md-3">
                    <div class="card">
                        <img src="images/field_experience_icon.png" class="card-img-top" alt="Field Experience Icon">
                        <div class="card-body">
                            <h5 class="card-title">Biodiversity Monitoring & Impact Assessment</h5>
                            <p class="card-text">I possess expertise in conducting systematic field studies to assess biodiversity (invertebrates and vertebrates). During my master’s course, I also prepared People Biodiversity Register (PBR) using both Traditional Ecological Knowledge (TEK) and scientific methods. Furthermore, I can identify bats, scorpions, and centipedes through morphological taxonomy.</p>
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
                <li><strong>Ghosh, D., <span class="font-weight-bold">Karjee, R.</span>, and Subramanian, K. A. 2024.</strong> Notes on the Cleptoparasitic Bees from Tawang District in Arunachal Pradesh, India with Special Reference to Family Apidae of Order Hymenoptera. Records of Zoological Survey of India. 124 (iS), 501-512. <a href="https://doi.org/10.26515/rzsi/v124/i1S/2024/172758" target="_blank">[online]</a></li>
            <li><strong>Ghosh, D., Chatterjee, P., <span class="font-weight-bold">Karjee, R.</span>, and Subramanian, K.A. 2023.</strong> Flower visitor assemblage and foraging profile of a pollinator attractant non-crop plant Isodon coetsa (Buch.-Ham. ex D.Don) Kudô from eastern Himalayas, India. Proceedings of Zoological Society. <a href="https://doi.org/10.1007/s12595-023-00498-x" target="_blank">[online]</a></li>
            <li><strong><span class="font-weight-bold">Karjee, R.</span>, Palei, H. S., Konwar, A., Gogoi, A., & Mishra, R. K. 2022.</strong> Bird assemblages in a peri-urban landscape in eastern India. Birds. 3(4), 383-401 <a href="https://doi.org/10.3390/birds3040026" target="_blank">[online]</a></li>
            <li><strong>Patra, A., Ahmed, T.M., <span class="font-weight-bold">Karjee, R.</span>, and Bhandari, S. 2019.</strong> Sighting of madras tree shrew Anathana ellioti (Waterhouse, 1850) with first photographic evidence at Ajodhya range, district Purulia, West Bengal, India. International Journal of Fauna and Biological Studies. 6(1):41-42<a href="https://www.researchgate.net/publication/340810168_Sighting_of_madras_tree_shrew_Anathana_ellioti_Waterhouse_1850_with_first_photographic_evidence_at_Ajodhya_range_district_Purulia_West_Bengal_India" target="_blank">[online]</a></li>
            </ul>
        </div>
    </section>

    <!-- Contact Me Section -->
    <section id="contact" class="section bg-light">
        <div class="container text-center">
            <h2 class="section-heading">Contact Me</h2>
            <div class="row">
                <div class="col-md-12">
                    <a href="mailto:ratneshkarjee@example.com" class="btn btn-primary">Email</a>
                    <a href="https://scholar.google.com/citations?user=XXXXXX" class="btn btn-primary">Google Scholar</a>
                    <a href="https://www.researchgate.net/profile/Ratnesh_Karjee" class="btn btn-primary">ResearchGate</a>
                    <a href="https://github.com/ratneshkarjee" class="btn btn-primary">GitHub</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Bootstrap JS and dependencies -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
