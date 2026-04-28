# Ex01 Portfolio
## Date: 27-04-2026

## NAME: ESWANTHKUMAR K
## REG NO: 212223040046

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
    <title>ESWANTH KUMAR K</title>
    <style>
        :root {
            --bg: #f0f8ff;
            --primary: #002b36;
            --secondary: #268bd2;
            --highlight: olive;
            --text: #073642;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-color: var(--bg);
            color: var(--text);
            line-height: 1.5;
        }

        header {
            background-color: var(--primary);
            color: white;
            padding: 1rem 0;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 2rem;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        

        .hero {
            display: -webkit-flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 3rem 1rem;
            background-color: skyblue;
            color: white;
            text-align: center;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
        }

        .section {
            padding: 4rem 2rem;
            max-width: 1000px;
            margin: auto;
        }

        h2 {
            color: var(--primary);
            margin-bottom: 2rem;
            border-bottom: 3px solid var(--highlight);
            display: inline-block;
        }

        .skills ul,
        .projects ul {
            list-style: none;
            padding: 0;
        }

        .skills li,
        .projects li {
            background-color: #ffffff;
            padding: 1rem;
            margin-bottom: 1rem;
            box-shadow: 0 0 5px rgba(0,0,0,0.1);
        }

        .contact {
            background-color: var(--primary);
            color: white;
            padding: 3rem 2rem;
            text-align: center;
        }

        .contact a {
            color: var(--highlight);
            text-decoration: none;
        }

        footer {
            text-align: center;
            padding: 1rem;
            background-color: var(--text);
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h1>ESWANTH KUMAR K</h1>
        <p>A passionate web developer and problem solver always looking for new challenges to grow and build impactful digital solutions.</p>
    </section>

    <section class="section" id="about">
        <h2>About Me</h2>
        <p>I’m ESWANTH KUMAR K, a coding expert in Java and Python, skilled at building efficient programs, solving complex problems, and explaining concepts clearly..</p>
    </section>

    <section class="section" id="skills">
        <h2>Skills</h2>
        <div class="skills">
            <ul>
                <li>HTML5 / CSS3 / JavaScript</li>
                <li>Java programming</li>
                <li>Python3</li>
                <li>Git / GitHub</li>
            </ul>
        </div>
    </section>

    <section class="section" id="projects">
        <h2>Projects</h2>
        <div class="projects">
            <ul>
                <li>
                    <h3>Personal Portfolio</h3>
                    <p>A responsive portfolio website showcasing my work, skills, and contact details.</p>
                </li>
                <li>
                    <h3>Blood Bank Management System</h3>
                    <p>A real time blood bank website to track matching donors and identify their place of donation(hospitals).</p>
                </li>
                <li>
                    <h3>Design System Template</h3>
                    <p>A design system with reusable UI components built with HTML/CSS and documented for scalability.</p>
                </li>
            </ul>
        </div>
    </section>

    <section class="contact" id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:eswanthkumar@gmail.com">eswanthkumar@gmail.com</a></p>
    </section>

    <footer>
        <p>&copy; Eswanth Kumar K. All rights reserved.</p>
    </footer>
</body>
</html>

```

## OUTPUT
<img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/97174843-122a-4c9e-a48e-3dd5c51bd819" />

<img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/458b4859-8d40-40ac-8508-f519cfe123c0" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
