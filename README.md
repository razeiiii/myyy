Razel Javier
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RAZEL JAVIER's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            scroll-behavior: smooth;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: white;
            padding: 15px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #666;
        }

        section {
            display: none; 
            padding: 50px 20px;
            margin: 20px;
        }
        section h2 {
            color: #333;
        }

        #about {
            display: block;
        }

        section img {
            width: 100%;
            max-width: 600px;
            margin: 20px 0;
            border-radius: 8px;
        }

        .skills, .projects {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .skill, .project {
            background-color: white;
            padding: 20px;
            margin: 10px;
            width: 30%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .skill h3, .project h3 {
            margin-top: 0;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }

        nav a.active {
            background-color: #666;
        }
    </style>
</head>
<body>
    <header>
        <h1>Razel Javier's Website</h1>
        <p>LIFE PORTFOLIO</p>
    </header>

    <nav>
        <a href="javascript:void(0);" onclick="showSection('about')" class="active">About Me</a>
        <a href="javascript:void(0);" onclick="showSection('skills')">Skills</a>
        <a href="javascript:void(0);" onclick="showSection('projects')">Projects</a>
        <a href="javascript:void(0);" onclick="showSection('contact')">Contact</a>
        <a href="javascript:void(0);" onclick="showSection('academic')">Academic & Training</a>
        <a href="javascript:void(0);" onclick="showSection('blogs')">Blogs</a>
        <a href="javascript:void(0);" onclick="showSection('testimonials')">Testimonials</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <head>
            <title>Image</title>
        </head>
        <body>
            <img src=https://scontent-mnl1-2.xx.fbcdn.net/v/t39.30808-6/475878528_581793615009786_7334511068054126664_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=a5f93a&_nc_eui2=AeF3bLCvWulCIVmF02Zi0Ei-BIBCUpB2nFwEgEJSkHacXJ7B_-TzDNpzaEd2FcMkrV7AwhAfmTkOnzyv6HNptSwN&_nc_ohc=btbGwPK2t8sQ7kNvgHwvlZ7&_nc_oc=AdhaFtpZe7NzZgEYeI6I6_DPn-_IVV2aPNZj-Uoe4H4SqnAYGBR9Lu_trraViuaQckQ&_nc_zt=23&_nc_ht=scontent-mnl1-2.xx&_nc_gid=APzgFwI-yjSk6EOxteljeCh&oh=00_AYCAgUXQpUy3mBicOE145UfEQdxI-cx-xTJa6burGFSj1A&oe=67B0C0C1
            width= "400px" height="500px">
        </body>
        <p>Hi! I'm Razel, A BSIT student.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <img src="skills-image.jpg" alt="Skills Image">
        <div class="skills">
            <div class="skill">
                <h3>HTML</h3>
                <p>Expert in HTML5 and building structured, semantic web pages.</p>
            </div>
            <div class="skill">
                <h3>CSS</h3>
                <p>Skilled in CSS3, flexbox, grid, and responsive design principles.</p>
            </div>
            <div class="skill">
                <h3>JavaScript</h3>
                <p>Proficient in JavaScript and building interactive web applications.</p>
            </div>
        </div>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <img src="projects-image.jpg" alt="Projects Image">
        <div class="projects">
            <div class="project">
                <h3>Project 1</h3>
                <p>A description of your first project. It could be a website or web app you've built.</p>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>A description of your second project. Include technologies used and the impact it had.</p>
            </div>
            <div class="project">
                <h3>Project 3</h3>
                <p>A description of your third project. Make sure to highlight your role and the results.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <img src="contact-image.jpg" alt="Contact Image">
        <p>If you'd like to work with me or have any questions, feel free to reach out!</p>
        <ul>
            <li>Email: razeljavier13@gmail.com</li>
            <li>LinkedIn: <a href=https://www.linkedin.com/in/razel-javier-147777350/overlay/about-this-profile/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3BUcE8n6c4SXK6obuxbnKusg%3D%3D target="_blank">Razel Javier</a></li>
            <li>GitHub: <a href="https://github.com/razeiiii" target="_blank">Your GitHub</a></li>
        </ul>
    </section>

    <section id="academic">
        <h2>Academic & Training</h2>
        <img src="academic-image.jpg" alt="Academic Image">
        <p>Details of your academic background, certifications, and any relevant training you've completed. For example:</p>
        <ul>
            <li><strong>Degree:</strong> Bachelor of Science in Computer Science, </li>
            <li><strong>Certification:</strong> Front-End Web Development</li>
            <li><strong>Training:</strong> </li>
        </ul>
    </section>

    <section id="blogs">
        <h2>Blogs</h2>
        <img src="blogs-image.jpg" alt="Blogs Image">
        <p>Here are some of the blog posts I’ve written on topics like web development, design, and technology:</p>
        <ul>
            <li><a href="https://yourbloglink.com" target="_blank">The Future of Web Design</a></li>
            <li><a href="https://yourbloglink.com" target="_blank">Why JavaScript is Essential for Web Development</a></li>
            <li><a href="https://yourbloglink.com" target="_blank">Tips for Responsive Web Design</a></li>
        </ul>
    </section>

    <section id="testimonials">
        <h2>Testimonials</h2>
        <img src="testimonials-image.jpg" alt="Testimonials Image">
        <p>Here’s what some people have said about working with me:</p>
        <blockquote>
            <p>"Your Name was an absolute pleasure to work with. Their expertise in front-end development and attention to detail made the project a success!"</p>
            <footer>- Client Name, Company</footer>
        </blockquote>
        <blockquote>
            <p>"Working with Your Name was a game-changer. They brought creativity, technical skills, and dedication to the table, making every project a joy!"</p>
            <footer>- Colleague Name, Company</footer>
        </blockquote>
    </section>

    <footer>
        <p>&copy; 2025 Razel Javier. All Rights Reserved.</p>
    </footer>

    <script>
        function showSection(sectionId) {
            const sections = document.querySelectorAll('section');
            sections.forEach(section => section.style.display = 'none');

            document.getElementById(sectionId).style.display = 'block';

            const links = document.querySelectorAll('nav a');
            links.forEach(link => link.classList.remove('active'));
            const activeLink = [...links].find(link => link.innerText.toLowerCase() === sectionId);
            if (activeLink) {
                activeLink.classList.add('active');
            }
        }
        showSection('about');
    </script>
</body>
</html>




<footer>
  
</footer>

</body>
</html>

