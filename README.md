# Yashraj-Moury
It is an pro broadcast of every best YouTubers, and you will definitely like it 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yashraj | Portfolio</title>

    <style>
        body{
            margin:0;
            font-family: 'Poppins', sans-serif;
            background:#0d1117;
            color:white;
        }
        header{
            display:flex;
            justify-content:space-between;
            align-items:center;
            padding:20px 40px;
            background:rgba(255,255,255,0.05);
            backdrop-filter:blur(10px);
            position:sticky;
            top:0;
        }
        header h1{
            margin:0;
            font-size:28px;
            color:#00eaff;
        }
        nav a{
            color:white;
            margin-left:20px;
            text-decoration:none;
            font-size:18px;
        }
        .section{
            padding:80px 40px;
            text-align:center;
        }
        .section h2{
            font-size:40px;
            color:#00eaff;
        }
        .about, .skills, .projects{
            max-width:900px;
            margin:auto;
            font-size:20px;
            line-height:1.6;
        }
        .skill-box{
            background:rgba(255,255,255,0.08);
            padding:20px;
            margin:15px;
            border-radius:10px;
        }
        .projects-grid{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
            gap:20px;
            margin-top:40px;
        }
        .project-card{
            background:rgba(255,255,255,0.05);
            padding:20px;
            border-radius:10px;
            box-shadow:0 0 10px rgba(0,0,0,0.4);
        }
        footer{
            background:#111;
            padding:20px;
            text-align:center;
            margin-top:40px;
        }
        .contact a{
            color:#00eaff;
            font-size:20px;
            text-decoration:none;
        }
    </style>
</head>

<body>
<header>
    <h1>Yashraj</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="home" class="section">
    <h2>Hello, I'm <span style="color:#00eaff;">Yashraj</span></h2>
    <p>A passionate learner, developer & creator.</p>
</section>

<section id="about" class="section">
    <h2>About Me</h2>
    <div class="about">
        I’m Yashraj, a student and a passionate creator who loves technology, design and creativity.
        I enjoy building cool websites, learning new things, and improving my skills every day.
    </div>
</section>

<section id="skills" class="section">
    <h2>Skills</h2>

    <div class="skills">
        <div class="skill-box">HTML</div>
        <div class="skill-box">CSS</div>
        <div class="skill-box">JavaScript</div>
        <div class="skill-box">UI/UX Design</div>
    </div>
</section>

<section id="projects" class="section">
    <h2>Projects</h2>

    <div class="projects-grid">
        <div class="project-card">
            <h3>Project 1</h3>
            <p>A simple webpage using HTML & CSS.</p>
        </div>

        <div class="project-card">
            <h3>Project 2</h3>
            <p>JavaScript interactive project.</p>
        </div>

        <div class="project-card">
            <h3>Project 3</h3>
            <p>Portfolio website (this one!).</p>
        </div>
    </div>
</section>

<section id="contact" class="section">
    <h2>Contact</h2>
    <div class="contact">
        <p>Email me at:</p>
        <a href="mailto:yashraj@gmail.com">yashraj@gmail.com</a>
    </div>
</section>

<footer>
    © 2025 Yashraj — All Rights Reserved
</footer>

</body>
</html>
