<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style type="text/css">
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: auto;
    color: white;
}
  .video{
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            z-index: -1;
        }

header {
    background: rgba(255, 255, 255, 0.1);;
    padding: 20px;
    text-align: center;
    color: white;
    border-radius: 200;
    font-weight: bold;
}
nav {
    margin-top: 10px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-size: 18px;
    padding: 8px;
    border-radius: 5px;
}

nav a:hover {
    background: white;
    color: hotpink;
}

.port {
    text-align: center;
    padding: 50px 20px;
    background:  rgba(255, 255, 255, 0.1);
    margin :auto;
}

.port h2 {
    color: green;
}
.port img {
    height: 150px ;
    width: 100px;
}

section {
    text-align: center;
    padding: 40px 20px;
    margin: auto;
    background:  rgba(255, 255, 255, 0.1);
    border-radius: 8px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}
.about {
    padding: 20px;
    text-align: center;
    margin: auto;     
}
#about h2 {
    color: green;
}
#about {
    margin-top: 20px;
    margin-left: 50px;
    margin-right: 50px;
}
#skills {
    margin-left: 350px;
    margin-right: 350px;
    margin-top: 20px;
    margin-bottom: 20px;
    background: rgba(255, 255, 255, 0.1);
}

.skills-inside {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 15px;
}

.skill {
    background: purple;
    color: white;
    padding: 12px 20px;
    border-radius: 5px;
    font-size: 18px;
}
#skills h2 {
    color: green;
}

.projects-inside {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
    border-radius: 400;
}

.project {
    background: rgba(255, 255, 255, 0.1);
    padding: 15px;
    text-align: center;
    width: 300px;
    box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
    margin: 10;
}
#projects {
    margin-top: 20px;
    margin-left: 400px;
    margin-right: 400px;

}
#projects h2 {
    color: green;
}
.project img {
    width: 100%;
    border-radius: 5px;
}
.project {
    margin: 40;
    border-radius: 400;
}
form {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
    max-width: 400px;
    margin: auto;
}
#contact h2 {
    color: green;
}
#contact {
    margin-right: 50px;
    margin-left: 50px;
    margin-top: 20px;
    margin-bottom: 20px;
}

form input, form textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    background: purple;
    color: white;
    padding: 12px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

form button:hover {
    background: seagreen;
}

footer {
    text-align: center;
    padding: 15px;
    background:  rgba(255, 255, 255, 0.1);
    color: white;
}
    </style>
</head>
<body>
 <div class="video">
    <video autoplay loop muted playsinline>
        <source src="bg sea.mp4" type="video/mp4">
        Your browser does not support HTML5 video.
    </video>
</div>

    <header>
        <h1>My Portfolio</h1>
        <nav>
           <u> <a href="#about">About</a></u>
            <u><a href="#skills">Skills</a></u>
            <u><a href="#projects">Projects</a></u>
            <u><a href="#contact">Contact</a></u>
        </nav>
    </header>

    <section class="port">
        <h2>Welcome to My Portfolio</h2>
         <img src="me.jpg">
        <p>I am a front-end developer skilled in HTML and CSS. I create modern, responsive, and user-friendly websites with clean, well-documented code</p>
    </section>

    <section id="about">
        <h2>About Me</h2>
       <div class="about"> <p>.I am a passionate front-end web developer with expertise in HTML and CSS, dedicated to creating clean, responsive, and visually appealing websites. My focus is on writing well-structured, semantic HTML and crafting modern, elegant CSS designs that enhance user experience across all devices.

With a strong eye for detail and a deep understanding of CSS Flexbox, Grid, and animations, I ensure that every project I build is both functional and aesthetically pleasing. I believe in transparent work, meaning my code is always well-documented, easy to maintain, and optimized for efficiency. Whether working independently or collaborating with a team, I prioritize clear communication, timely delivery, and high-quality results.

I am committed to continuous learning, staying updated with the latest web design trends, and pushing the boundaries of what’s possible with HTML and CSS. If you're looking for a developer who values clarity, precision, and professionalism, I'm the perfect fit!</p></div>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <div class="skills-inside">
            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
        </div>
    </section>

    <section id="projects">
        <h2>Projects</h2>
    </section>
    <section>
        <div class="projects-inside">
            <div class="project">
                <img src="calculator.jpg" alt="Simple Calculator">
                <h3>Simple Calculator</h3>
                <p>A minimal calculator built with HTML and CSS.</p>
            </div>

            <div class="project">
                <img src="contact form.jpg" alt="Contact Form">
                <h3>Basic Contact Form</h3>
                <p>A clean and user-friendly contact form.</p>
            </div>

            <div class="project">
                <img src="portfolio.webp" alt="Portfolio Website">
                <h3>Portfolio Website</h3>
                <p>A personal portfolio website to showcase my work.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 My Portfolio. All rights reserved.</p>
    </footer>

</body>
</html>
