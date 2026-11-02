<!DOCTYPE html>
<html>
<head>
<title>My Portfolio</title>
<style>
body {
    font-family: Arial;
    margin: 0;
    background: #f0f4f8;
    text-align: center;
}
nav {
    background: navy;
    padding: 15px;
}
nav a {
    color: white;
    margin: 12px;
    text-decoration: none;
}
nav a:hover {
    color: yellow;
}
section {
    padding: 30px;
}
.card {
    background: white;
    margin: 15px auto;
    padding: 15px;
    width: 70%;
    border-radius: 10px;
    box-shadow: 0 2px 8px #aaa;
    animation: fade 1.5s;
}
h1, h2 {
    color: navy;
}
button {
    background: navy;
    color: white;
    padding: 10px;
    border: none;
    cursor: pointer;
}
@keyframes fade {
    from {opacity: 0;}
    to {opacity: 1;}
}
footer {
    background: navy;
    color: white;
    padding: 15px;
}
@media(max-width:600px) {
    nav a { display: inline-block; }
    .card { width: 85%; }
}
</style>
</head>

<body>

<nav>
<a href="#home">Home</a>
<a href="#education">Education</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>

<section id="home">
<h1>Welcome to My Portfolio</h1>
<h3>Hello, I am siva nandhini</h3>
<p>Student and Web Developer</p>
</section>

<section id="education">
<h2>Education</h2>
<div class="card">B.Tech - College Name</div>
<div class="card">Intermediate - College Name</div>
</section>

<section id="skills">
<h2>Technical Skills</h2>
<div class="card">HTML, CSS, JavaScript, Python</div>
</section>

<section>
<h2>Hobbies & Achievements</h2>
<div class="card">Reading, Music, Coding</div>
<div class="card">Web Development Certificate</div>
</section>

<section id="projects">
<h2>My Projects</h2>
<div class="card">Personal Portfolio Website</div>
<div class="card">Calculator Project</div>
</section>

<section>
<h2>Resume</h2>
<a href="resume.pdf" download>Download Resume</a>
</section>

<section id="contact">
<h2>Contact Me</h2>
<p>Email: yourname@gmail.com</p>
<p>Phone: 9876543210</p>
<button onclick="alert('Thank you for contacting me!')">
Contact Me
</button>
</section>

<footer>
<p>© 2026 My Portfolio</p>
</footer>

</body>
</html>
