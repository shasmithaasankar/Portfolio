# Ex01 Portfolio
## Date: 07.05.2026

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
## HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shasmithaa Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    
    <nav>
        <h2 class="logo">Portfolio</h2>

        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>


    <section id="home" class="home">

        <h1>Hi, I'm <span>SHASMITHAA</span></h1>

        <p class="regno">212224040311</p>

        <p class="dept">CSE Student | Web Developer</p>

        <button>View My Work</button>

    </section>

    
    <section id="about" class="about">

        <h2>About Me</h2>

        <p>
            Hello! I’m <strong>Shasmithaa</strong>, a passionate Computer Science
            Engineering student with a strong interest in web development and
            programming.
        </p>

        <p>
            I enjoy creating modern, responsive, and user-friendly websites
            using HTML, CSS, and JavaScript. I love learning new technologies
            and improving my coding skills through projects.
        </p>

        <p>
            My goal is to become a successful full-stack developer and build
            innovative applications that solve real-world problems.
        </p>

    </section>


    <section id="skills" class="skills">

        <h2>My Skills</h2>

        <ul>
            <li><strong>HTML</strong></li>
            <li><strong>CSS</strong></li>
            <li><strong>JavaScript</strong></li>
            <li><strong>Python</strong></li>
            <li><strong>C Programming</strong></li>
        </ul>

    </section>

    
    <section id="projects" class="projects">

        <h2>Projects</h2>

        <div class="project-box">Portfolio Website</div>

        <div class="project-box">Student Management System</div>

        <div class="project-box">Simple Calculator</div>

    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">

        <h2>Contact Me</h2>

        <p>Email: shasmithaa@gmail.com</p>

        <p>Github: shasmithaa.github.io</p>

        <p>Phone: 9876543210</p>

    </section>

    
    <footer>
        <p>© 2026 Shasmithaa | All Rights Reserved</p>
    </footer>

</body>
</html>
```
## CSS
```

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Times New Roman', Times, serif;
}


body{
    background:#f3e8ff;
    color:#2d033b;
}


nav{
    background:#4b0082;
    color:white;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:15px 50px;
    position:sticky;
    top:0;
}

.logo{
    font-size:28px;
    font-weight:bold;
}

nav ul{
    list-style:none;
    display:flex;
}

nav ul li{
    margin-left:25px;
}

nav ul li a{
    text-decoration:none;
    color:white;
    font-size:18px;
    transition:0.3s;
}

nav ul li a:hover{
    color:#d8b4fe;
}


.home{
    height:90vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    background:linear-gradient(to right,#4b0082,#c084fc);
    color:white;
}

.home h1{
    font-size:50px;
    margin-bottom:15px;
}

.home span{
    color:#ffe066;
}

.regno{
    font-size:22px;
    margin-bottom:10px;
}

.dept{
    font-size:24px;
}

.home button{
    margin-top:25px;
    padding:12px 25px;
    border:none;
    background:white;
    color:#4b0082;
    font-size:18px;
    border-radius:8px;
    cursor:pointer;
    transition:0.3s;
}

.home button:hover{
    background:#e9d5ff;
}


section{
    padding:60px;
    text-align:center;
}

section h2{
    font-size:36px;
    margin-bottom:25px;
    color:#4b0082;
}


.about p{
    font-size:18px;
    line-height:1.8;
    margin-bottom:20px;
}


.skills ul{
    list-style:none;
}

.skills li{
    background:#d8b4fe;
    margin:15px auto;
    padding:15px;
    width:250px;
    border-radius:10px;
    font-size:18px;
    transition:0.3s;
}

.skills li:hover{
    background:#a855f7;
    color:white;
}


.projects{
    background:#faf5ff;
}

.project-box{
    background:#c084fc;
    color:white;
    padding:25px;
    margin:15px;
    display:inline-block;
    border-radius:12px;
    font-size:20px;
    transition:0.3s;
}

.project-box:hover{
    transform:scale(1.05);
    background:#7e22ce;
}

.contact{
    background:#4b0082;
    color:white;
}

.contact p{
    margin:12px;
    font-size:18px;
}


footer{
    background:#2d033b;
    color:white;
    text-align:center;
    padding:15px;
}
```



## OUTPUT
<img width="1917" height="1017" alt="image" src="https://github.com/user-attachments/assets/3b713fd5-e5b7-451c-9f58-d7599e80dd1b" />
<img width="1918" height="1020" alt="image" src="https://github.com/user-attachments/assets/1d3daad2-599c-4fbc-af07-5f8e03c594ba" />
<img width="1918" height="1012" alt="image" src="https://github.com/user-attachments/assets/b883529b-8f62-43d2-a227-9fa767a55fc9" />






## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
