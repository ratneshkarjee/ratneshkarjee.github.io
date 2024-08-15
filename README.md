<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        .navbar { background-color: #333; }
        .navbar-nav .nav-link { color: #fff !important; }
        .navbar-nav .nav-link:hover { color: #ddd !important; }
        .profile-img { border-radius: 50%; border: 5px solid #fff; }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="#home"></a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
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
                        <a class="nav-link" href="#collaborators">Collaborators</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#publications">Publications</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#blogs">Stories & Blogs</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#cv">CV</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact Me</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="section bg-light">
        <div class="container text-center">
            <img src="images/profile.jpg" alt="Profile Picture" class="profile-img">
            <h1 class="mt-4">Welcome to My Portfolio</h1>
            <p>Explore my work, skills, and expertise in the field of Biology.</p>
        </div>
    </section>

    <!-- About Me Section -->
    <section id="about" class="section">
        <div class="container">
            <h2 class="section-heading text-center">About Me</h2>
            <div class="text-center">
                <img src="images/about.jpg" alt="About Image" class="profile-img mb-4">
            </div>
            <p class="text-center">[Insert detailed information about you here...]</p>
        </div>
    </section>

    <!-- Skills & Expertise Section -->
    <section id="skills" class="section bg-light">
        <div class="container text-center">
            <h2 class="section-heading">Skills & Expertise</h2>
            <div class="row">
                <!-- Skill cards go here -->
            </div>
        </div>
    </section>

    <!-- Collaborators Section -->
    <section id="collaborators" class="section">
        <div class="container">
            <h2 class="section-heading text-center">Collaborators</h2>
            <div class="row">
                <!-- Collaborator details go here -->
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
