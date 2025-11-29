# CodSoft-Task1, task 2 and task 3
Task 1 creating Portfolio @CodSoft
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


Task 2 Landing Page @CodSoft

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>

    <style>
        /* Global Styling */
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f7f7f7;
        }

        /* Navbar */
        header {
            background: #222;
            padding: 20px 40px;
            color: white;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 16px;
        }

        nav a:hover {
            color: #ffcc00;
        }

        /* Hero Section */
        .hero {
            background: url('https://images.unsplash.com/photo-1519389950473-47ba0277781c') 
                        center/cover no-repeat;
            height: 90vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            padding: 20px;
        }

        .hero h1 {
            font-size: 60px;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 20px;
            margin-bottom: 25px;
        }

        .hero a {
            background: #ffcc00;
            padding: 14px 28px;
            text-decoration: none;
            color: black;
            font-weight: bold;
            border-radius: 5px;
        }

        .hero a:hover {
            background: #ff9900;
        }

        /* Features Section */
        .features {
            padding: 60px 20px;
            text-align: center;
        }

        .feature-box {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        .card {
            width: 300px;
            background: white;
            margin: 15px;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }

        .card h3 {
            margin-bottom: 10px;
        }

        /* Footer */
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 20px;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 40px;
            }
            .hero p {
                font-size: 18px;
            }
            header {
                flex-direction: column;
            }
        }
    </style>
</head>

<body>

    <!-- Header -->
    <header>
        <h2>MyBrand</h2>
        <nav>
            <a href="#hero">Home</a>
            <a href="#features">Features</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="hero" class="hero">
        <div>
            <h1>Welcome to Our Landing Page</h1>
            <p>Your solution for modern, fast and responsive web design.</p>
            <a href="#features">Get Started</a>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="features">
        <h2>Our Features</h2>
        <div class="feature-box">

            <div class="card">
                <h3>Fast Performance</h3>
                <p>We ensure that your website loads quickly and runs smoothly.</p>
            </div>

            <div class="card">
                <h3>Modern Design</h3>
                <p>Clean and beautiful layout designs that attract users.</p>
            </div>

            <div class="card">
                <h3>Fully Responsive</h3>
                <p>Looks great on mobile, tablet, and desktop screens.</p>
            </div>

        </div>
    </section>

    <!-- Footer -->
    <footer id="contact">
        <p>Contact us at: mybrand@gmail.com</p>
        <p>© 2025 MyBrand - All Rights Reserved</p>
    </footer>

</body>
</html>


Task 3 simple calculator @CodSoft

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Calculator</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .calculator {
            background: #fff;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
            width: 300px;
            text-align: center;
        }

        input {
            width: 80%;
            padding: 10px;
            margin: 8px 0;
            border-radius: 6px;
            border: 1px solid #aaa;
            font-size: 16px;
        }

        button {
            width: 45%;
            padding: 10px;
            margin: 5px;
            background: #333;
            color: white;
            border: none;
            border-radius: 6px;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background: #ff9900;
        }

        h2 {
            margin-bottom: 15px;
        }

        #result {
            margin-top: 15px;
            padding: 10px;
            background: #eaeaea;
            border-radius: 6px;
            font-size: 18px;
            min-height: 30px;
        }
    </style>

</head>
<body>

    <div class="calculator">
        <h2>Simple Calculator</h2>

        <input type="number" id="num1" placeholder="Enter Number 1">
        <input type="number" id="num2" placeholder="Enter Number 2">

        <div>
            <button onclick="add()">Sum</button>
            <button onclick="subtract()">Difference</button>
            <button onclick="multiply()">Product</button>
            <button onclick="divide()">Quotient</button>
            <button onclick="remainder()">Remainder</button>
            <button onclick="power()">Power</button>
            <button onclick="squareRoot()">Square Root</button>
        </div>

        <div id="result">Result will appear here</div>
    </div>

    <script>
        function getValues() {
            return {
                n1: parseFloat(document.getElementById("num1").value),
                n2: parseFloat(document.getElementById("num2").value)
            };
        }

        function add() {
            let { n1, n2 } = getValues();
            document.getElementById("result").innerHTML = "Sum: " + (n1 + n2);
        }

        function subtract() {
            let { n1, n2 } = getValues();
            document.getElementById("result").innerHTML = "Difference: " + (n1 - n2);
        }

        function multiply() {
            let { n1, n2 } = getValues();
            document.getElementById("result").innerHTML = "Product: " + (n1 * n2);
        }

        function divide() {
            let { n1, n2 } = getValues();
            if (n2 === 0) {
                document.getElementById("result").innerHTML = "Cannot divide by zero!";
            } else {
                document.getElementById("result").innerHTML = "Quotient: " + (n1 / n2);
            }
        }

        function remainder() {
            let { n1, n2 } = getValues();
            document.getElementById("result").innerHTML = "Remainder: " + (n1 % n2);
        }

        function power() {
            let { n1, n2 } = getValues();
            document.getElementById("result").innerHTML = "Power: " + (n1 ** n2);
        }

        function squareRoot() {
            let n1 = parseFloat(document.getElementById("num1").value);
            if (n1 < 0) {
                document.getElementById("result").innerHTML = "Square root of negative number is invalid!";
            } else {
                document.getElementById("result").innerHTML = "Square Root: " + Math.sqrt(n1);
            }
        }
    </script>

</body>
</html>