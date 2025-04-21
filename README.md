<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diya Rao - Student Portfolio</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #1a1a2e;
            overflow-x: hidden;
        }
        header {
            background: linear-gradient(90deg, #ff7e5f, #feb47b);
            color: white;
            padding: 2rem 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            animation: fadeIn 2s ease;
        }
        header h1 {
            margin: 0;
            font-size: 3rem;
            letter-spacing: 2px;
        }
        header p {
            font-size: 1.2rem;
            margin-top: 0.5rem;
        }
        .profile-image {
            margin-top: 1rem;
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            border: 3px solid white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            animation: zoomIn 1.5s ease;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            padding: 0.8rem 0;
            background: #16213e;
            position: sticky;
            top: 0;
            z-index: 10;
            animation: slideDown 1.5s ease;
        }
        nav a {
            text-decoration: none;
            color: #fff;
            font-size: 1.2rem;
            padding: 0.5rem 1rem;
            transition: background 0.3s, transform 0.3s;
        }
        nav a:hover {
            background: #e94560;
            border-radius: 5px;
            transform: scale(1.1);
        }
        .container {
            width: 90%;
            max-width: 1100px;
            margin: 2rem auto;
            padding: 2rem;
            background: white;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
            border-radius: 10px;
            animation: fadeInUp 2s ease;
        }
        .section {
            margin-bottom: 3rem;
        }
        .section h2 {
            font-size: 2rem;
            color: #e94560;
            margin-bottom: 1rem;
            text-align: center;
        }
        footer {
            text-align: center;
            padding: 1.5rem;
            background: #16213e;
            color: white;
            animation: fadeIn 2s ease;
        }
        .contact-info {
            margin-top: 1rem;
            text-align: center;
        }
        .button {
            display: inline-block;
            padding: 0.7rem 1.5rem;
            font-size: 1rem;
            color: white;
            background: #e94560;
            text-decoration: none;
            border-radius: 5px;
            transition: transform 0.3s, background 0.3s;
        }
        .button:hover {
            background: #ff7e5f;
            transform: scale(1.1);
        }
        .project {
            border: 1px solid #ccc;
            padding: 1.5rem;
            border-radius: 10px;
            margin: 1.5rem 0;
            background: #f9f9f9;
            transition: transform 0.3s;
            animation: fadeInUp 2s ease;
        }
        .project:hover {
            transform: scale(1.03);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: center;
            margin-top: 1rem;
        }
        .skill {
            background: #16213e;
            color: white;
            padding: 0.8rem 1.2rem;
            border-radius: 5px;
            font-size: 1rem;
            animation: fadeIn 2s ease;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
        @keyframes zoomIn {
            from {
                transform: scale(0.8);
                opacity: 0;
            }
            to {
                transform: scale(1);
                opacity: 1;
            }
        }
        @keyframes slideDown {
            from {
                transform: translateY(-50px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }
        @keyframes fadeInUp {
            from {
                transform: translateY(50px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Diya Rao</h1>
        <p>B.Tech in Computer Engineering, MITAOE</p>
        <img src="diya2.jpg" alt="Diya Rao" class="profile-image">
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>Hello! I'm Diya Rao, a passionate and dedicated computer engineering student at MITAOE. I have a strong interest in software development, web design, and emerging technologies. I am always eager to learn and work on innovative projects. In my free time, I enjoy exploring new tools, reading tech blogs, and enhancing my coding skills.</p>
        </section>
        <section id="skills" class="section">
            <h2>Skills</h2>
            <div class="skills">
                <div class="skill">HTML & CSS</div>
                <div class="skill">JavaScript</div>
                <div class="skill">Python</div>
                <div class="skill">Java</div>
                <div class="skill">React.js</div>
                <div class="skill">SQL</div>
                <div class="skill">Problem Solving</div>
                <div class="skill">UI/UX Design</div>
            </div>
        </section>
        <section id="projects" class="section">
            <h2>Projects</h2>
            <div class="project">
                <h3>Personal Portfolio Website</h3>
                <p>Developed an interactive and aesthetic portfolio website using HTML, CSS, and JavaScript to showcase skills and projects.</p>
            </div>
            <div class="project">
                <h3>Library Management System</h3>
                <p>Created a library management application using Python and SQLite to streamline book lending processes.</p>
            </div>
            <div class="project">
                <h3>Weather App</h3>
                <p>Designed a weather forecasting application using React.js and OpenWeather API for real-time updates.</p>
            </div>
        </section>
        <section id="contact" class="section">
            <h2>Contact Me</h2>
            <p>If you'd like to get in touch, feel free to reach out via email or phone!</p>
            <div class="contact-info">
                <p>Email: <a href="mailto:diyarao611@gmail.com">diyarao611@gmail.com</a></p>
                <p>Phone: <a href="tel:9587336021">9587336021</a></p>
