<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }
        .header {
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 15px 0;
            z-index: 1000;
            display: flex;
            justify-content: center; /* Center the nav items horizontally */
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .header .container {
            max-width: 1200px; /* Adjust this value to increase/decrease header width */
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .header a {
            color: white;
            padding: 15px;
            text-decoration: none;
            display: inline-block;
        }
        .header a:hover {
            background-color: rgba(255, 255, 255, 0.3);
            border-radius: 5px;
        }
        .section {
            padding: 60px 20px;
            min-height: 100vh;
        }
        .home-img {
            width: 400px; /* Adjust width as needed */
            height: 250px; /* Adjust height as needed */
            object-fit: cover; /* Ensures the image covers the dimensions without distortion */
            border: 5px solid #fff;
            border-radius: 10px; /* Rounded corners for a softer look */
        }
        .contact-info {
            margin-top: 20px;
        }
        .contact-info p {
            margin: 5px 0;
        }
        .contact-info i {
            margin-right: 10px;
        }
        .contact-info a {
            color: #fff;
            text-decoration: none;
        }
        .contact-info a:hover {
            text-decoration: underline;
        }
        .container {
            text-align: justify;
        }
        .container h1 {
            text-align: center;
            margin-bottom: 20px;
        }
        .section img {
            width: 100%; /* Makes images responsive */
            height: auto; /* Maintains aspect ratio */
        }
    </style>
</head>
<body>

    <!-- Header -->
    <div class="header">
        <div class="container">
            <a href="#home">Home</a>
            <a href="#about">About Me</a>
            <a href="#skills">Skills & Expertise</a>
            <a href="#projects">Projects</a>
            <a href="#collaborators">Collaborators</a>
            <a href="#publication">Publication</a>
            <a href="#stories">Stories & Blogs</a>
            <a href="#cv">CV</a>
            <a href="#contact">Contact Me</a>
        </div>
    </div>

    <!-- Home Section -->
    <section id="home" class="section">
        <div class="container text-center">
            <img src="images/about.jpg" alt="Ratnesh Karjee" class="home-img">
            <h1>Welcome</h1>
            <p>Curiosity to explore and discover new knowledge and learn new things should form the base for any researcher. Growing up in a village in West Bengal, I was intrigued when I first encountered subjects such as animal behaviour in my bachelor’s degree coursework. These courses helped me better understand the animals I had seen back home, including the human-elephant conflicts in my region. I believe this was the start of my journey in wildlife conservation.</p>
            
            <div class="contact-info">
                <p><i class="fa fa-envelope"></i><a href="mailto:ratneshkarjeeatherasteyahoo.com">ratneshkarjeeatherasteyahoo.com</a></p>
                <p><i class="fa fa-google"></i><a href="https://scholar.google.com/citations?user=HtWRd9gAAAAJ&hl=en" target="_blank">Google Scholar</a></p>
                <p><i class="fa fa-researchgate"></i><a href="https://www.researchgate.net/profile/Ratnesh-Karjee" target="_blank">ResearchGate</a></p>
                <p><i class="fa fa-github"></i><a href="https://github.com/your-github" target="_blank">GitHub</a></p>
            </div>
        </div>
    </section>

    <!-- Add other sections here -->

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
