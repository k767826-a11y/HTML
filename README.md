<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
            font-family: Arial, sans-serif;
        }

        body {
            background: #f5f7fa;
            color: #222;
            line-height: 1.6;
        }

        /* Navbar */
        header {
            background: #111827;
            padding: 15px 8%;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            color: white;
            font-size: 25px;
            font-weight: bold;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 25px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 16px;
        }

        nav ul li a:hover {
            color: #38bdf8;
        }

        /* Home */
        #home {
            min-height: 90vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 40px;
            background: linear-gradient(135deg, #dbeafe, #f0f9ff);
        }

        .home-content h1 {
            font-size: 50px;
            color: #111827;
        }

        .home-content h2 {
            color: #2563eb;
            margin: 10px 0;
        }

        .home-content p {
            max-width: 600px;
            margin: 15px auto;
        }

        .btn {
            display: inline-block;
            background: #2563eb;
            color: white;
            padding: 12px 25px;
            border-radius: 6px;
            text-decoration: none;
            margin-top: 15px;
        }

        .btn:hover {
            background: #1d4ed8;
        }

        /* Common Section */
        section {
            padding: 70px 8%;
        }

        section h2 {
            text-align: center;
            font-size: 35px;
            margin-bottom: 35px;
            color: #111827;
        }

        /* About */
        .about {
            max-width: 800px;
            margin: auto;
            text-align: center;
        }

        /* Skills */
        .skills-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
        }

        .skill {
            background: white;
            padding: 18px 30px;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            font-weight: bold;
        }

        /* Experience */
        .experience-box {
            background: white;
            max-width: 800px;
            margin: auto;
            padding: 25px;
            border-left: 5px solid #2563eb;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }

        /* Projects */
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .project-card {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 3px 12px rgba(0,0,0,0.1);
        }

        .project-card h3 {
            color: #2563eb;
            margin-bottom: 10px;
        }

        .project-card a {
            display: inline-block;
            margin-top: 10px;
            color: #2563eb;
            text-decoration: none;
            font-weight: bold;
        }

        /* Education */
        .education-box {
            background: white;
            max-width: 800px;
            margin: auto;
            padding: 25px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }

        /* Resume */
        #resume {
            text-align: center;
            background: #e0f2fe;
        }

        /* Contact */
        .contact {
            max-width: 700px;
            margin: auto;
        }

        .contact input,
        .contact textarea {
            width: 100%;
            padding: 13px;
            margin: 8px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .contact textarea {
            height: 130px;
        }

        /* Footer */
        footer {
            background: #111827;
            color: white;
            text-align: center;
            padding: 25px;
        }

        /* Mobile */
        @media (max-width: 768px) {
            nav {
                flex-direction: column;
                gap: 15px;
            }

            nav ul {
                flex-wrap: wrap;
                justify-content: center;
                gap: 12px;
            }

            .home-content h1 {
                font-size: 38px;
            }
        }
    </style>
</head>

<body>

    <!-- Navbar -->
    <header>
        <nav>
            <div class="logo">My Portfolio</div>

            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#resume">Resume</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>


    <!-- Home -->
    <section id="home">
        <div class="home-content">

            <h1>Hello, I'm Your Name</h1>

            <h2>Frontend Developer</h2>

            <p>
                I am a passionate developer interested in creating
                modern, responsive and user-friendly websites.
            </p>

            <a href="#projects" class="btn">
                View My Projects
            </a>

        </div>
    </section>


    <!-- About -->
    <section id="about">

        <h2>About Me</h2>

        <div class="about">

            <p>
                Hello! I am Your Name. I am interested in web development
                and programming. I enjoy creating websites and learning
                new technologies.
            </p>

        </div>

    </section>


    <!-- Skills -->
    <section id="skills">

        <h2>My Skills</h2>

        <div class="skills-container">

            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">JavaScript</div>
            <div class="skill">Python</div>
            <div class="skill">Pandas</div>
            <div class="skill">NumPy</div>
            <div class="skill">Matplotlib</div>
            <div class="skill">Power BI</div>
            <div class="skill">Git & GitHub</div>

        </div>

    </section>


    <!-- Experience -->
    <section id="experience">

        <h2>Experience</h2>

        <div class="experience-box">

            <h3>Web Development Intern</h3>

            <p>
                Company Name | 2026
            </p>

            <p>
                Worked on frontend development, website design,
                HTML, CSS and JavaScript projects.
            </p>

        </div>

    </section>


    <!-- Projects -->
    <section id="projects">

        <h2>My Projects</h2>

        <div class="projects">

            <div class="project-card">

                <h3>Portfolio Website</h3>

                <p>
                    A personal responsive portfolio website
                    created using HTML and CSS.
                </p>

                <a href="#">GitHub Code</a>

            </div>


            <div class="project-card">

                <h3>Student Performance Analysis</h3>

                <p>
                    Student performance data analysis using
                    Python, Pandas and visualization.
                </p>

                <a href="#">View Project</a>

            </div>


            <div class="project-card">

                <h3>Power BI Dashboard</h3>

                <p>
                    Interactive dashboard created using
                    Power BI for data analysis.
                </p>

                <a href="#">View Dashboard</a>

            </div>

        </div>

    </section>


    <!-- Education -->
    <section id="education">

        <h2>Education</h2>

        <div class="education-box">

            <h3>Your Degree / Course</h3>

            <p>Your College Name</p>

            <p>2023 - 2026</p>

        </div>

    </section>


    <!-- Resume -->
    <section id="resume">

        <h2>My Resume</h2>

        <p>
            Download my resume to know more about my
            education, skills and experience.
        </p>

        <br>

        <a href="resume.pdf" download class="btn">
            Download Resume
        </a>

    </section>


    <!-- Contact -->
    <section id="contact">

        <h2>Contact Me</h2>

        <div class="contact">

            <form>

                <input
                    type="text"
                    placeholder="Your Name"
                    required
                >

                <input
                    type="email"
                    placeholder="Your Email"
                    required
                >

                <textarea
                    placeholder="Your Message"
                    required>
                </textarea>

                <button type="submit" class="btn">
                    Send Message
                </button>

            </form>

        </div>

    </section>


    <!-- Footer -->
    <footer>

        <p>
            © 2026 Your Name | All Rights Reserved
        </p>

        <p>
            GitHub | LinkedIn | Email
        </p>

    </footer>

</body>
</html>
