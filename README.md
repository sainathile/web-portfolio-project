# web-portfolio-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Sai Nathile's portfolio showcasing her skills, projects, and achievements in Computer Science & Engineering.">
    <meta name="keywords" content="Sai Nathile, Portfolio, HTML, CSS, JavaScript, Developer, Event Manager">
    <title>Sai Nathile | Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@500&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: #f8d7e6; 
            color: #333;
            text-align: center;
            position: relative;
        }

        header {
            background: linear-gradient(135deg, #ff66b2, #ff1493);
            padding: 30px;
            font-size: 1.8em;
            font-weight: bold;
            font-family: 'Dancing Script', cursive;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .nav-menu {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 15px;
            background: #ff6699;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .nav-menu a {
            text-decoration: none;
            color: #fff;
            font-weight: bold;
            padding: 10px 20px;
            background: #ff1493;
            border-radius: 10px;
            transition: 0.3s;
        }

        .nav-menu a:hover {
            background: #fff;
            color: #ff1493;
        }

        .content-container {
            display: flex;
            justify-content: center;
            gap: 40px;
            padding: 40px;
            align-items: center;
            flex-wrap: wrap;
        }

        .photo-container {
            width: 380px; 
            height: 380px; 
            border-radius: 50%;
            overflow: hidden;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.4); 
            border: 6px solid #ff1493; 
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
            order: 2; 
            margin-left: 100px; 
        }

        .photo-container:hover {
            transform: scale(1.1) rotate(5deg); 
            box-shadow: 0 0 25px 10px rgba(255, 20, 147, 0.6); 
        }

        .photo-container img {
            width: 100%;
            height: auto;
        }

        .card {
            padding: 20px;
            width: 300px;
            border-radius: 20px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease-in-out;
            position: relative;
            background: radial-gradient(circle, rgba(255,255,255,1) 0%, rgba(255,240,240,1) 100%);
            order: 1; 
        }

        .card:hover {
            transform: translateY(-5px);
        }

        #skills {
            background: radial-gradient(circle, #b3e0ff, #add8e6);
        }

        #projects {
            background: radial-gradient(circle, #e6ccff, #d8b9f2);
        }

        #extracurricular {
            background: radial-gradient(circle, #fff5cc, #fffacd);
        }

        #contact {
            background: radial-gradient(circle, #ffddbb, #ffdab9);
        }

        footer {
            background: #ff66b2;
            padding: 15px;
            margin-top: 20px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1>Sai Nathile</h1>
        <p>✨ Creative Developer | Tech Enthusiast | Event Manager ✨</p>
    </header>

    <nav class="nav-menu">
        <a href="#about">📖 About</a>
        <a href="#skills">💡 Skills</a>
        <a href="#projects">💻 Projects</a>
        <a href="#extracurricular">🎭 Extra-Curricular</a>
        <a href="#contact">📬 Contact</a>
    </nav>

    <div class="content-container">
        <div class="card" id="about">
            <h2>📖 About Me</h2>
            <p>As a dedicated second-year Computer Science student, I am passionate about coding, design, and bringing ideas to life through technology. I thrive on creativity and logic, blending innovation with aesthetics. Beyond coding, I excel in organizing events, ensuring seamless execution with strong management skills. Constantly exploring new trends, I aspire to build impactful projects that merge technology with creativity.</p>
        </div>
        <div class="photo-container">
            <img src="portfolio.jpeg" alt="Sai Nathile">
        </div>
    </div>

    <div class="content-container">
        <div class="card" id="skills">
            <h2>💡 Skills</h2>
            <p>HTML, CSS, JavaScript, C, C++, Python, Management, Event Planning</p>
        </div>
        <div class="card" id="projects">
            <h2>💻 Projects</h2>
            <p><a href="http://127.0.0.1:5500/moodtracker.html" target="_blank">Mood-Based Quote Project</a></p>
            <p><a href="http://127.0.0.1:5500/artani.html" target="_blank">Dreamy Memory Match</a></p>
            <p><a href="http://127.0.0.1:5500/popcultureit.html" target="_blank">Pop Culture Quiz</a></p>
            <p><a href="http://127.0.0.1:5500/digitalplanner.html" target="_blank">Gradient Pop Doodle~</a></p>
        </div>
        <div class="card" id="extracurricular">
            <h2>🎭 Extra-Curricular</h2>
            <p>Active event manager at the FYI Club, coordinating tech events and workshops.</p>
        </div>
        <div class="card" id="contact">
            <h2>📬 Contact</h2>
            <p>Email: sainathile@gmail.com</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Sai Nathile. All Rights Reserved.</p>  
    </footer>
</body>
</html>

