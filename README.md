# Ex01 Portfolio
## Date:01/11/2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rabi Baskar | Portfolio</title>
</head>

<body bgcolor="#F4F6FC">

<center>

    <br>

    <!-- HEADER -->

    <table width="90%" bgcolor="#DCE6F8" cellpadding="20">
        <tr>
            <td align="center">

                <img src="images/rabi.png"
                     alt="Rabi Baskar"
                     width="120"
                     height="120">

                <br><br>

                <font color="#34466D" size="6">
                    <b>RABI BASKAR PRABURAJAN</b>
                </font>

                <br><br>

                <font color="#526D9B" size="4">
                    Computer Science Engineering Student
                </font>

                <br><br>

                <font color="#64748B">
                    Developer | AI Enthusiast | Technology Explorer
                </font>

                <br><br>

                <a href="#about">About</a> &nbsp; | &nbsp;
                <a href="#skills">Skills</a> &nbsp; | &nbsp;
                <a href="#projects">Projects</a> &nbsp; | &nbsp;
                <a href="#certificates">Certificates</a> &nbsp; | &nbsp;
                <a href="#education">Education</a> &nbsp; | &nbsp;
                <a href="#contact">Contact</a>

            </td>
        </tr>
    </table>

    <br>

    <!-- ANNOUNCEMENT -->

    <marquee behavior="alternate" width="85%" scrollamount="3">
        <font color="#607D9D">
            Turning Ideas Into Innovation • Learning • Building • Exploring
        </font>
    </marquee>

    <br><br>

    <!-- HOME SECTION -->

    <table width="85%" cellpadding="20">
        <tr>
            <td align="center">

                <font color="#35466F" size="6">
                    <b>Hello, I'm Rabi! 👋</b>
                </font>

                <h3>
                    <font color="#7189B5">
                        Building Technology. Creating Impact.
                    </font>
                </h3>

                <p>
                    <font color="#526174" size="3">
                        I'm a passionate Computer Science Engineering
                        student who loves exploring Artificial Intelligence,
                        Software Development and Cybersecurity.
                    </font>
                </p>

                <p>
                    I enjoy transforming creative ideas into practical
                    technology solutions and building projects that
                    solve real-world problems.
                </p>

                <br>

                <a href="#projects">
                    <font color="#526D9B">
                        <b>Explore My Projects ↓</b>
                    </font>
                </a>

                &nbsp;&nbsp;

                <a href="#contact">
                    <font color="#526D9B">
                        <b>Get In Touch</b>
                    </font>
                </a>

            </td>
        </tr>
    </table>

    <br>

    <!-- ABOUT SECTION -->

    <table width="85%" bgcolor="#FFFFFF" cellpadding="20">
        <tr>
            <td>

                <h2>
                    <font color="#526D9B">01. About Me</font>
                </h2>

                <p>
                    I'm Rabi Baskar Praburajan, a Computer Science
                    Engineering student at Saveetha Engineering College.
                </p>

                <p>
                    I'm enthusiastic about technology and passionate
                    about exploring Artificial Intelligence, Web
                    Development, Machine Learning and Cybersecurity.
                </p>

                <p>
                    I enjoy experimenting with new technologies,
                    participating in hackathons and developing
                    innovative solutions.
                </p>

                <p>
                    My ambition is to become an engineer who builds
                    impactful technologies and solves meaningful
                    real-world challenges.
                </p>

                <hr color="#DCE6F8">

                <table width="100%" cellpadding="8">

                    <tr>
                        <td><b>Department</b></td>
                        <td>Computer Science Engineering</td>
                    </tr>

                    <tr>
                        <td><b>College</b></td>
                        <td>Saveetha Engineering College</td>
                    </tr>

                    <tr>
                        <td><b>CGPA</b></td>
                        <td>8.4</td>
                    </tr>

                    <tr>
                        <td><b>Interests</b></td>
                        <td>AI | Development | Cybersecurity</td>
                    </tr>

                </table>

            </td>
        </tr>
    </table>

    <br>

    <!-- SKILLS SECTION -->

    <table width="85%" bgcolor="#E5F1EF" cellpadding="20">
        <tr>
            <td>

                <h2>
                    <font color="#477D73">02. Technical Skills</font>
                </h2>

                <h3>Programming Languages</h3>

                Python
                <br>
                <progress value="80" max="100"></progress>

                <br><br>

                Java
                <br>
                <progress value="65" max="100"></progress>

                <br><br>

                C Programming
                <br>
                <progress value="75" max="100"></progress>

                <br><br>

                JavaScript
                <br>
                <progress value="60" max="100"></progress>

                <hr color="#B9DAD2">

                <h3>Web Development</h3>

                <table width="100%" cellpadding="8">
                    <tr>
                        <td>HTML</td>
                        <td>CSS</td>
                        <td>React.js</td>
                    </tr>

                    <tr>
                        <td>Flask</td>
                        <td>Django</td>
                        <td>FastAPI</td>
                    </tr>
                </table>

                <h3>Tools & Technologies</h3>

                <p>
                    Git | GitHub | VS Code | Firebase |
                    Vercel | Render | PostgreSQL
                </p>

                <h3>Areas of Interest</h3>

                <p>
                    Artificial Intelligence |
                    Machine Learning |
                    Cybersecurity |
                    Data Science
                </p>

            </td>
        </tr>
    </table>

    <br>

    <!-- PROJECTS SECTION -->

    <table width="85%" bgcolor="#FFFFFF" cellpadding="20">
        <tr>
            <td>

                <h2>
                    <font color="#526D9B">03. Featured Projects</font>
                </h2>

                <p>
                    <font color="#7189B5">
                        Some of the projects I've worked on.
                        Click each project to explore.
                    </font>
                </p>

                <details>
                    <summary>
                        <b>RESQVISION – AI Disaster Response System</b>
                    </summary>

                    <p><b>Domain:</b> AI & Disaster Management</p>

                    <p>
                        An AI-assisted disaster response and
                        survivor-triage system that analyzes drone
                        footage to identify survivors and help
                        emergency teams prioritize rescue operations.
                    </p>

                    <p>
                        <b>Technologies:</b>
                        React, TypeScript, YOLO11, Python, AI
                    </p>

                </details>

                <hr color="#E0E7F1">

                <details>
                    <summary>
                        <b>APAAR Guardian – Academic Verification Platform</b>
                    </summary>

                    <p><b>Domain:</b> AI & Education Technology</p>

                    <p>
                        A secure academic record management platform
                        featuring automated validation, anomaly
                        detection and tamper-evident audit logs.
                    </p>

                    <p>
                        <b>Technologies:</b>
                        React, FastAPI, Python, PostgreSQL
                    </p>

                </details>

                <hr color="#E0E7F1">

                <details>
                    <summary>
                        <b>ZEUS AI – Intelligent AI Chatbot</b>
                    </summary>

                    <p><b>Domain:</b> Artificial Intelligence</p>

                    <p>
                        An AI-powered chatbot designed to provide
                        intelligent conversational assistance using
                        modern language models.
                    </p>

                    <p>
                        <b>Technologies:</b>
                        React, Flask, Python, Groq API
                    </p>

                </details>

                <hr color="#E0E7F1">

                <details>
                    <summary>
                        <b>Restaurant Management System</b>
                    </summary>

                    <p>
                        A software application designed to simplify
                        restaurant operations and management.
                    </p>

                    <p>
                        <b>Domain:</b> Web Development
                    </p>

                </details>

            </td>
        </tr>
    </table>

    <br>

    <!-- CERTIFICATIONS SECTION -->

    <table width="85%" bgcolor="#F0EAF8" cellpadding="20">
        <tr>
            <td>

                <h2>
                    <font color="#79649C">04. Certifications</font>
                </h2>

                <ul>
                    <li>IBM Data Science Professional Certificate</li>
                    <li>NPTEL – Data Science for Engineers</li>
                    <li>NPTEL – Internet of Things</li>
                    <li>CISCO – Ethical Hacking</li>
                </ul>

            </td>
        </tr>
    </table>

    <br>

    <!-- EDUCATION SECTION -->

    <table width="85%" bgcolor="#FFFFFF" cellpadding="20">
        <tr>
            <td>

                <h2>
                    <font color="#526D9B">05. Education</font>
                </h2>

                <font color="#526D9B" size="4">
                    <b>Bachelor of Engineering (B.E.)</b>
                </font>

                <p>Computer Science and Engineering</p>

                <p>Saveetha Engineering College</p>

                <p>CGPA: 8.4</p>

            </td>
        </tr>
    </table>

    <br>

    <!-- CONTACT SECTION -->

    <table width="85%" bgcolor="#DCE6F8" cellpadding="20">
        <tr>
            <td align="center">

                <h2>
                    <font color="#34466D">06. Let's Connect!</font>
                </h2>

                <p>
                    I'm always interested in connecting with developers,
                    collaborating on projects and exploring new
                    opportunities.
                </p>

                <br>

                <a href="mailto:yourmail@gmail.com">
                    <b>Email Me</b>
                </a>

                &nbsp; | &nbsp;

                <a href="https://github.com/RABI-7" target="_blank">
                    <b>GitHub</b>
                </a>

                &nbsp; | &nbsp;

                <a href="https://www.linkedin.com/" target="_blank">
                    <b>LinkedIn</b>
                </a>

            </td>
        </tr>
    </table>

    <br><br>

    <!-- FOOTER -->

    <table width="85%" bgcolor="#34466D" cellpadding="15">
        <tr>
            <td align="center">

                <font color="#FFFFFF">

                    <b>RABI BASKAR PRABURAJAN</b>

                    <br><br>

                    © 2026 All Rights Reserved.

                    <br><br>

                    Designed with HTML | Built with Passion.

                    <br><br>

                    <a href="#top">
                        <font color="#FFFFFF">
                            Back to Top ↑
                        </font>
                    </a>

                </font>

            </td>
        </tr>
    </table>

    <br>

</center>

</body>
</html>

```

## OUTPUT
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/bf0abb05-8c21-48f9-8ede-3ad3f1ffce20" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
