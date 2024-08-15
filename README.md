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
        .nav-links {
            margin: 10px 0;
        }
        .nav-links a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
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

    <!-- Your existing content starts here -->

    <!-- Home Section -->
    <section id="home" class="home-section">
        <!-- Content for Home Section -->
    </section>

    <!-- About Section -->
    <section id="about" class="about-section">
        <!-- Content for About Section -->
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills-section">
        <!-- Content for Skills & Expertise Section -->
    </section>

    <!-- Publications Section -->
    <section id="publications" class="publications-section">
        <!-- Content for Publications Section -->
    </section>

    <!-- Collaborators Section -->
    <section id="collaborators" class="collaborators-section">
        <!-- Content for Collaborators Section -->
    </section>

    <!-- Stories & Blogs Section -->
    <section id="stories" class="stories-section">
        <!-- Content for Stories & Blogs Section -->
    </section>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
