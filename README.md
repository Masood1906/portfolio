# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohammed Masood Ahmed - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
    <style>
        /* Ensure the home icon is fixed to the bottom-right */
        #home-icon {
            position: fixed;
            bottom: 10px;
            right: 10px;
            width: 50px; /* Small icon */
            height: 50px;
        }

        /* Additional style for body and layout */
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>
    <header>
        <h1 class="name">Mohammed Masood Ahmed</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#recommendations">Recommendations</a></li>
            </ul>
        </nav>
    </header>
    
    <div id="home"></div>

    <section id="about">
        <img src="InShot_20220212_170238753.jpg" alt="Your Profile Image">
        <h2>Hi, I'm Mohammed Masood Ahmed! 👋</h2>
        <p>Master of Science in Software Design with Artificial Intelligence</p>
    </section>
    
    <section id="skills">
        <h2>Skills</h2>
        <div class="skill-card">HTML - 2 years</div>
        <div class="skill-card">CSS - 2 years</div>
        <div class="skill-card">JavaScript - 1.5 years</div>
        <div class="skill-card">Python - 4</div>
        <div class="skill-card">React - 1 year</div>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li><strong>Virtual Try-On System:</strong> <br>• Created a Virtual Try-On system for clothing using Computer Vision.</li>
            <hr>
            <li><strong>Smart Extract:</strong> <br>• Developed a system for extracting structured data from unstructured machinery manuals using NLP and OCR.</li>
            <hr>
            <li><strong>Intrusion Detection System:</strong> <br>• Implemented an intrusion detection system using PCA and Random Forest Algorithm to detect anomalies in network traffic.</li>
            <hr>
        </ul>
    </section>
    
    <section id="recommendations">
        <h2>Recommendations</h2>
        <div id="recommendations-list">
            <p>"Mohammed is a quick learner and a great team player..."</p>
        </div>
        <h3>Leave a Recommendation</h3>
        <input type="text" id="name" placeholder="Your Name (Optional)">
        <textarea id="message" placeholder="Write your recommendation..."></textarea>
        <button onclick="addRecommendation()">Submit</button>
    </section>

    <!-- Home Icon positioned at the bottom-right -->
    <a href="#home">
        <img src="home-icon.png" alt="Home Icon" id="home-icon">
    </a>

</body>
</html>
