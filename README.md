<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Krish Kunal | Web Developer</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI',sans-serif;
scroll-behavior:smooth;
}

body{
background:#0f172a;
color:white;
}

header{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
background:linear-gradient(135deg,#0f172a,#1e293b);
}

header h1{
font-size:4rem;
margin-bottom:10px;
}

header span{
color:#38bdf8;
}

header p{
font-size:1.2rem;
color:#cbd5e1;
max-width:700px;
}

.btn{
display:inline-block;
margin-top:25px;
padding:12px 30px;
background:#38bdf8;
color:black;
text-decoration:none;
font-weight:bold;
border-radius:30px;
transition:.3s;
}

.btn:hover{
transform:translateY(-5px);
}

section{
padding:80px 10%;
}

.section-title{
text-align:center;
font-size:2.5rem;
margin-bottom:40px;
color:#38bdf8;
}

.about{
background:#111827;
border-radius:20px;
padding:30px;
line-height:1.8;
}

.skills{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
gap:20px;
}

.skill{
background:#1e293b;
padding:20px;
text-align:center;
border-radius:15px;
transition:.3s;
}

.skill:hover{
transform:translateY(-8px);
}

.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:#1e293b;
padding:25px;
border-radius:15px;
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.project{
background:#1e293b;
padding:20px;
border-radius:15px;
}

.contact{
text-align:center;
background:#111827;
padding:40px;
border-radius:20px;
}

footer{
text-align:center;
padding:20px;
background:#020617;
color:#94a3b8;
}
</style>
</head>

<body>

<header>
<h1>Hi, I'm <span>Krish Kunal</span></h1>
<p>
Passionate Web Developer skilled in HTML, CSS and JavaScript.
I create modern, responsive and user-friendly websites that
help businesses and individuals build a strong online presence.
</p>

<a href="#contact" class="btn">Hire Me</a>
</header>

<section>
<h2 class="section-title">About Me</h2>

<div class="about">
<p>
Hello! My name is Krish Kunal and I am a Frontend Web Developer.
I enjoy designing beautiful websites and turning ideas into real web experiences.

I specialize in HTML, CSS and JavaScript and focus on creating responsive,
fast and attractive websites.

I am a quick learner, creative thinker and always eager to improve my skills.
My goal is to build websites that look professional and provide a great user experience.
</p>
</div>
</section>

<section>
<h2 class="section-title">My Skills</h2>

<div class="skills">
<div class="skill">HTML5</div>
<div class="skill">CSS3</div>
<div class="skill">JavaScript</div>
<div class="skill">Responsive Design</div>
<div class="skill">Web Development</div>
<div class="skill">UI Design</div>
<div class="skill">Problem Solving</div>
<div class="skill">Frontend Development</div>
</div>
</section>

<section>
<h2 class="section-title">Services</h2>

<div class="services">
<div class="card">
<h3>Portfolio Websites</h3>
<p>Professional personal portfolio websites.</p>
</div>

<div class="card">
<h3>Landing Pages</h3>
<p>High-converting modern landing pages.</p>
</div>

<div class="card">
<h3>Business Websites</h3>
<p>Responsive websites for businesses.</p>
</div>

<div class="card">
<h3>Website Redesign</h3>
<p>Improve existing websites with modern design.</p>
</div>
</div>
</section>

<section>
<h2 class="section-title">Projects</h2>

<div class="projects">
<div class="project">
<h3>Personal Portfolio</h3>
<p>Responsive portfolio website built using HTML and CSS.</p>
</div>

<div class="project">
<h3>Landing Page</h3>
<p>Modern landing page with responsive design.</p>
</div>

<div class="project">
<h3>Business Website</h3>
<p>Professional website for local businesses.</p>
</div>
</div>
</section>

<section id="contact">
<div class="contact">
<h2>Let's Work Together</h2>
<br>
<p><strong>Name:</strong> Krish Kunal</p>
<p><strong>Role:</strong> Frontend Web Developer</p>
<p><strong>Skills:</strong> HTML, CSS, JavaScript</p>
<p><strong>Status:</strong> Available for Freelance & Remote Work</p>
</div>
</section>

<footer>
© 2026 Krish Kunal | Web Developer
</footer>

</body>
</html>
