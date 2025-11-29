Task 1 Portfolio @CodSoft


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* ----------- Global Styles ----------- */
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: #f4f4f4;
        }

        header {
            background: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-size: 18px;
        }

        nav a:hover {
            color: #ffcc00;
        }

        section {
            padding: 60px;
            text-align: center;
        }

        h2 {
            font-size: 32px;
            margin-bottom: 20px;
        }

        /* ----------- Hero Section ----------- */
        .hero {
            background: #222;
            color: white;
            padding: 100px 20px;
        }

        .hero h1 {
            font-size: 50px;
        }

        .hero p {
            font-size: 20px;
            opacity: 0.8;
        }

        /* ----------- About ----------- */
        #about {
            background: white;
        }

        #about p {
            width: 70%;
            margin: auto;
            font-size: 18px;
            line-height: 1.6;
        }

        /* ----------- Skills ----------- */
        .skills {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        .skill-box {
            background: white;
            width: 250px;
            margin: 15px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgb(0,0,0,0.1);
        }

        /* ----------- Projects ----------- */
        .projects {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        .project-card {
            background: white;
            width: 300px;
            margin: 15px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgb(0,0,0,0.1);
        }
        
        /* ----------- Contact ----------- */
        #contact a {
            background: #333;
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
        }

        #contact a:hover {
            background: #ff9900;
        }

        /* ----------- Responsive ----------- */
        @media (max-width: 768px) {
            section {
                padding: 40px 20px;
            }

            .hero h1 {
                font-size: 35px;
            }

            .skills, .projects {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <header>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <h1>Hello, I'm <span style="color:#ffcc00">Your Name</span></h1>
        <p>Web Developer | Designer | Programmer</p>
    </section>

    <!-- About -->
    <section id="about">
        <h2>About Me</h2>
        <p>
            Hi! I am a passionate web developer who loves creating beautiful and functional websites.
            I specialize in HTML, CSS, JavaScript and love learning new technologies.
        </p>
    </section>

    <!-- Skills -->
    <section id="skills">
        <h2>My Skills</h2>
        <div class="skills">
            <div class="skill-box">HTML</div>
            <div class="skill-box">CSS</div>
            <div class="skill-box">JavaScript</div>
            <div class="skill-box">Python</div>
            <div class="skill-box">C Programming</div>
            <div class="skill-box">Java</div>
        </div>
    </section>

    <!-- Projects -->
    <section id="projects">
        <h2>My Projects</h2>
        <div class="projects">
            <div class="project-card">
                <h3>Project 1</h3>
                <p>A simple description of your project. Explain what you built and how it works.</p>
            </div>

            <div class="project-card">
                <h3>Project 2</h3>
                <p>A simple description of your project. Explain what you built and how it works.</p>
            </div>

            <div class="project-card">
                <h3>Project 3</h3>
                <p>A simple description of your project. Explain what you built and how it works.</p>
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: yourname@example.com</p>
        <a href="mailto:yourname@example.com">Send Email</a>
    </section>

</body>
</html>