# Ex01 Portfolio
## Date: 23.04.2026

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
  <title>Shasmithaa | Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1 class="logo">Shasmithaa</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#tech">Tech</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <img src="photo.jpeg" alt="Profile Image">
    <h2>Hello, I am <span>Shasmithaa</span></h2>
    <p>Designer | Full Stack Developer</p>
    <p>2nd Year CSE Student</p>
  </section>

  <section id="about" class="section">
    <h2>About Me</h2>
    <p>
  I am a 2nd-year Computer Science and Engineering (CSE) student with a strong interest in full-stack development. 
  I enjoy learning modern technologies and building clean, user-friendly web applications. 
  I am also passionate about problem solving and continuously improving my technical skills.
  </p>
      
    
  </section>

  <section id="skills" class="section">
    <h2>Skills</h2>

    <div class="box">
      <h3>Design</h3>
      <div class="items">
        <span>UI/UX</span>
        <span>Canva</span>
        <span>Figma</span>
      </div>
    </div>

    <div class="box">
      <h3>Frontend</h3>
      <div class="items">
        <span>HTML</span>
        <span>CSS</span>
        <span>JavaScript</span>
        <span>React</span>
      </div>
    </div>

    <div class="box">
      <h3>Backend</h3>
      <div class="items">
        <span>Node.js</span>
        <span>Express</span>
        <span>REST API</span>
      </div>
    </div>
  </section>

  <section id="tech" class="section">
    <h2>Tech Stack</h2>
    <div class="items">
      <span>MongoDB</span>
      <span>SQL</span>
      <span>Git & GitHub</span>
      <span>DSA</span>
      <span>Cloud Basics</span>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contact</h2>
    <p>Email: shasmithaasankar@gmail.com</p>
    <p>Location: Chennai, India</p>
  </section>

  <footer>
    <p>© 2026 Shasmithaa | Built with HTML & CSS</p>
  </footer>

</body>
</html>
```
## CSS
```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", "Segoe UI", sans-serif;
}

body {
  background: linear-gradient(135deg, #a1c4fd, #c2e9fb);
  color: #2b2b2b;
  scroll-behavior: smooth;
}

/* HEADER */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 10%;
  background: rgba(255, 255, 255, 0.3);
  backdrop-filter: blur(10px);
  position: sticky;
  top: 0;
}

.logo {
  font-size: 1.6rem;
  font-weight: bold;
  color: #1e90ff;
}

nav a {
  margin-left: 18px;
  text-decoration: none;
  color: #333;
  font-weight: 500;
}

nav a:hover {
  color: #1e90ff;
}

/* HERO */
.hero {
  height: 90vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.hero img {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  object-fit: cover;
  border: 5px solid white;
  margin-bottom: 20px;
}

.hero h2 span {
  color: #1e90ff;
}

/* SECTIONS */
.section {
  padding: 70px 10%;
  text-align: center;
}

.section h2 {
  color: #1e90ff;
  margin-bottom: 20px;
}

.box {
  background: rgba(255,255,255,0.35);
  backdrop-filter: blur(10px);
  padding: 20px;
  border-radius: 20px;
  margin-bottom: 20px;
}

.items {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 10px;
}

.items span {
  background: white;
  padding: 8px 16px;
  border-radius: 50px;
}

footer {
  text-align: center;
  padding: 15px;
  background: rgba(255,255,255,0.3);
}
```



## OUTPUT
<img width="1919" height="1022" alt="image" src="https://github.com/user-attachments/assets/7d78ec08-b457-43e5-99dd-5c285597a609" />
<img width="1919" height="1009" alt="image" src="https://github.com/user-attachments/assets/604e0b49-f64d-4ac7-a97c-27ae8d11b50d" />
<img width="1916" height="1024" alt="image" src="https://github.com/user-attachments/assets/de263a8e-8711-4d32-b193-df5f3da48dc7" />





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
