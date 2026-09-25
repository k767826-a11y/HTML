# Introduction
My name is Minakshi
I am learning in Machine learning & AI

##Skills
NUMPY
Pandas
Linear regression
Matplotlib

##Experience
Diploma in computer engineering
**10th**:97%
**12th**:75%
**Diploma**:75%

##Tools
Git & Github
VS code

##Code
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Minakshi | Machine learning & Artifical intelligence Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #222;
            background: #f5f7fa;
        }

        
        header {
            background: #111827;
            color:white;
             text-align:center;
             padding:70px 20px;
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

        /* Common */
        section {
            padding: 70px 8%;
        }

        .section-title {
            text-align: center;
            font-size: 32px;
            margin-bottom: 40px;
            color: #111827;
        }

        /* Home */
        #home {
            min-height: 90vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: linear-gradient(135deg, #e0f2fe, #f8fafc);
        }

        #home h1 {
            font-size: 50px;
            margin-bottom: 10px;
        }

        #home h1 span {
            color: #0284c7;
        }

        #home p {
            font-size: 20px;
            margin-bottom: 25px;
        }

        .btn {
            display: inline-block;
            padding: 12px 25px;
            background: #0284c7;
            color: white;
            text-decoration: none;
            border-radius: 6px;
            margin: 5px;
        }

        .btn:hover {
            background: #0369a1;
        }

        /* About */
        .about-box {
            max-width: 850px;
            margin: auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
            text-align: center;
        }

        /* Skills */
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .skill {
            background: white;
            padding: 20px 30px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            font-weight: bold;
        }

        /* Projects */
        .projects-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .project {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
        }

        .project h3 {
            margin-bottom: 10px;
            color: #0284c7;
        }

        /* Education */
        .education {
            max-width: 800px;
            margin: auto;
        }

        .education-item {
            background: white;
            padding: 20px;
            margin-bottom: 15px;
            border-left: 5px solid #0284c7;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
        }

        /* Contact */
        .contact-box {
            max-width: 600px;
            margin: auto;
            text-align: center;
        }

        .contact-box p {
            margin: 12px 0;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background: #111827;
            color: white;
        }

        /* Mobile */
        @media (max-width: 700px) {
            nav {
                flex-direction: column;
                gap: 15px;
            }

            nav ul {
                gap: 12px;
                flex-wrap: wrap;
                justify-content: center;
            }

            #home h1 {
                font-size: 36px;
            }
        }
    </style>
</head>

<body>

    <!-- Navbar -->
    <header>
        <nav>
            <div class="logo">Minakshi</div>

            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home -->
    <section id="home">
        <div>
            <h1>Hello, I'm <span>Minakshi</span></h1>

            <p>
                Frontend Developer | Python Learner | Data Science Enthusiast
            </p>

            <a href="#projects" class="btn">View My Projects</a>

            <a href="resume.pdf" class="btn" download>
                Download Resume
            </a>
        </div>
    </section>

    <!-- About -->
    <section id="about">
        <h2 class="section-title">About Me</h2>

        <div class="about-box">
            <p>
                Hello! I am Minakshi, a passionate learner interested in
                frontend development, Python, data analysis and machine
                learning. I enjoy creating useful projects and improving
                my technical skills.
            </p>
        </div>
    </section>

    <!-- Skills -->
    <section id="skills">
        <h2 class="section-title">My Skills</h2>

        <div class="skills-container">
            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">JavaScript</div>
            <div class="skill">Python</div>
            <div class="skill">Pandas</div>
            <div class="skill">NumPy</div>
            <div class="skill">Matplotlib</div>
            <div class="skill">Machine Learning</div>
            <div class="skill">GitHub</div>
        </div>
    </section>

    <!-- Projects -->
    <section id="projects">
        <h2 class="section-title">My Projects</h2>

        <div class="projects-container">

            <div class="project">
                <h3>Student Performance Analysis</h3>
                <p>
                    Analyzed student data using Python, Pandas and
                    visualization techniques.
                </p>
                <br>
                <a href="#" class="btn">View Project</a>
            </div>

            <div class="project">
                <h3>House Price Prediction</h3>
                <p>
                    Created a machine learning project using
                    Linear Regression to predict house prices.
                </p>
                <br>
                <a href="#" class="btn">View Project</a>
            </div>

            <div class="project">
                <h3>Loan Approval Prediction</h3>
                <p>
                    Built a Decision Tree classification project
                    using income, credit score and loan amount.
                </p>
                <br>
                <a href="#" class="btn">View Project</a>
            </div>

        </div>
    </section>

    <!-- Education -->
    <section id="education">
        <h2 class="section-title">Education & Experience</h2>

        <div class="education">

            <div class="education-item">
                <h3>Your Degree / Course</h3>
                <p>Your College Name</p>
                <p>Year: 2023 - 2026</p>
            </div>

            <div class="education-item">
                <h3>Frontend Development</h3>
                <p>HTML, CSS and JavaScript Projects</p>
            </div>

            <div class="education-item">
                <h3>Python & Data Science</h3>
                <p>
                    Learning Python, Pandas, NumPy,
                    Matplotlib and Machine Learning.
                </p>
            </div>

        </div>
    </section>

    <!-- Contact -->
    <section id="contact">
        <h2 class="section-title">Contact Me</h2>

        <div class="contact-box">

            <p>
                📧 Email:
                <strong>your-email@gmail.com</strong>
            </p>

            <p>
                📱 Phone:
                <strong>+91 XXXXX XXXXX</strong>
            </p>

            <p>
                💻 GitHub:
                <a href="https://github.com/" target="_blank">
                    My GitHub
                </a>
            </p>

            <p>
                🔗 LinkedIn:
                <a href="#" target="_blank">
                    My LinkedIn
                </a>
            </p>

        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 Minakshi. All Rights Reserved.</p>
    </footer>

</body>
</html>



