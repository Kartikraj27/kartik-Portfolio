# kartik-Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kartik Raj | Portfolio</title>
<link rel="stylesheet" href="style.css">

<link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">
</head>

<body>

<header>
<nav>
<h2>Kartik Raj</h2>
<ul>
<li><a href="#about">About</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>
</header>

<!-- HERO -->
<section class="hero">

<div class="hero-content">

<img src="profile.jpg" class="profile" data-aos="zoom-in">

<h1 data-aos="fade-up">Hi, I'm Kartik Raj</h1>
<p data-aos="fade-up" data-aos-delay="200">
Full Stack Developer
</p>

<a href="#contact" class="btn" data-aos="zoom-in">Hire Me</a>

</div>

</section>

<!-- ABOUT -->
<section id="about" data-aos="fade-right">
<h2>About Me</h2>
<p>
I am a passionate developer from Government Engineering College Vaishali.
I build modern, responsive websites using HTML, CSS, JavaScript, PHP and MySQL.
</p>
</section>

<!-- SKILLS -->
<section id="skills">
<h2 data-aos="fade-up">Skills</h2>

<div class="skills">
<div data-aos="flip-left">HTML</div>
<div data-aos="flip-left">CSS</div>
<div data-aos="flip-left">JavaScript</div>
<div data-aos="flip-left">Bootstrap</div>
<div data-aos="flip-left">PHP</div>
<div data-aos="flip-left">MySQL</div>
</div>

</section>

<!-- PROJECTS -->
<section id="projects">
<h2 data-aos="fade-up">Projects</h2>

<div class="project" data-aos="zoom-in">
<h3>Portfolio Website</h3>
<p>Modern animated portfolio website.</p>
</div>

<div class="project" data-aos="zoom-in">
<h3>Login System</h3>
<p>Authentication system using PHP & MySQL.</p>
</div>

<div class="project" data-aos="zoom-in">
<h3>College Management</h3>
<p>Student data management system.</p>
</div>

</section>

<!-- CONTACT -->
<section id="contact" data-aos="fade-left">
<h2>Contact</h2>
<p>Email: kartik898708@email.com</p>
<p>GitHub: github.com/kartikraj27</p>
</section>

<footer>
<p>© 2026 Kartik Raj</p>
</footer>

<script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
<script>
AOS.init({
duration:1000,
once:true
});
</script>

</body>
</html>
