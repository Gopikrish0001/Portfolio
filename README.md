# Ex01 Portfolio
## Date:13.08.2025

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
  <title>My Portfolio - Gopikrishnan</title>
  <link rel="stylesheet" href="ex1.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Me</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="section"><br>
    <br>
    <h1>Welcome to My Portfolio</h1>
    <h1>Gopikrishnan M</h1>
    <h3>B.E. CSE,III Year</h3><br>
    <img src="GOPI.jpg" alt="My Photo" style="width: 160px;" class="profile-photo"><br><br><br>
    <h4>
      <p>
        I am Gopikrishnan, a third-year Computer Science and Engineering student pursuing a BE degree. I am passionate about web development and have a keen interest in machine learning. I enjoy building innovative projects and enhancing my skills in technology.
      </p>
    </h4>
    
  </section>

  <section id="about" class="section">
    <br><br>
    <h2>About Me</h2><br>
    <p>I am a Computer Science and Engineering student passionate about web development and machine learning.</p>
    <p>I specialize in building responsive and interactive web applications using modern frameworks like React.js and Node.js.</p>
    <p>My interests include full-stack development, AI integration in web apps, and developing user-centric designs.</p>
    <p>Currently, I am working on a Cancer Detection System using machine learning as part of my academic project.</p>
    <p>I also actively participate in coding competitions and contribute to open-source projects to enhance my coding skills.</p>
    <p>My goal is to become a proficient full-stack developer and leverage technology to solve real-world problems.</p>
  </section>

  <section id="education" class="section">
    <br><br>
    <h2>Education</h2>
    <center>
      <table style="padding: 30px; border: #333;">
        <tr>
            <th>Batch</th>
            <th>Institution</th>
            <th>Course</th>
            <th>Percentage</th>
        </tr>
        <tr>
            <td>2023-2027</td>
            <td>Saveetha Engineering College</td>
            <td>BE Computer Science and Engineering</td>
            <td>72.46%</td>
        </tr>
        <tr>
            <td>2021-2023</td>
            <td>nelloerpet Goverment Higher Secondary School</td>
            <td>11th, 12th - Higher Secondary Education</td>
            <td>88.50%</td>
        </tr>
        <tr>
            <td>2020-2021</td>
            <td>Government High secondry School</td>
            <td>10th </td>
            <td>65.00%</td>
        </tr>
    </table>
    </center>
  </section>

  <section id="skills" class="section">
    <br><br>
    <h2>Skills</h2><br>
    <h2>Technical Skills</h2><br>
<h4>
  I) Programming:   C, Java, Python, SQL
</h4>
<h4>
 II) Web Development:   HTML, CSS, JavaScript
</h4>
<h4>
 III) Machine Learning:   Data Science, Algorithms
</h4>
<br>
    
    <h2>Soft Skills</h2><br>
    <h4>I) Communication</h4>
    <h4>II) Project management</h4>
    <h4>III) Probelm-Solving</h4>
    
</section>

  

  <section id="contact" class="section">
    <br><br>
    <h2>Contact Me</h2><br><br>
    <p>Email: Gopikrishnan M</p>
    <p>LinkedIn: <a href="#">https://www.linkedin.com/in/gopikrishnan-m-648b46329/</a></p>
    <p>GitHub: <a href="#">https://github.com/Gopikrish0001</a></p><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
  

  <footer>
    <p>&copy; 2025 My Portfolio. All rights reserved.</p>
  </footer>
</section>
  
</body>
</html>

```
# html.css

```

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    scroll-behavior: smooth;
  }

  table {
          width: 70%;
          margin: auto;
          border-collapse: collapse;
      }
  th, td {
          border: 1px solid black;
          padding: 10px;
          text-align: center;
      }
  th {
          background-color: #f2f2f2;
      }

  nav {
    background-color: #333;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 100;
  }

  nav ul {
    list-style-type: none;
    text-align: center;
  }

  nav ul li {
    display: inline;
    margin: 0 20px;
  }

  nav a {
    text-decoration: none;
    color: white;
    font-weight: bold;
  }

  nav a:hover {
    color: #00bcd4;
  }

  .section {
    padding: 50px 20px;
    min-height: 100vh;
    text-align: center;
  }

  #home {
    background-color: sandybrown;
  }

  #about {
    background-color: #e6f7ff;
  }

  #education {
    background-color: #d9f7be;
  }

  #skills {
    background-color: #d9f7be;
  }

  #projects {
    background-color: #fff1b8;
  }

  #contact {
    background-color: #ffe7ba;
  }

  footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
  }

  .profile-photo {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-top: 20px;
  }

```


## OUTPUT

<img width="1882" height="884" alt="image" src="https://github.com/user-attachments/assets/b2f5b688-7eb8-41de-8fc1-734be0c823dd" />
<img width="1609" height="669" alt="image" src="https://github.com/user-attachments/assets/0614df21-8416-4376-b598-fce5ab4c2948" />
<img width="1550" height="571" alt="image" src="https://github.com/user-attachments/assets/4096e019-a05c-41bd-aac6-b3cb79174b82" />
<img width="1228" height="761" alt="image" src="https://github.com/user-attachments/assets/e849a747-73b5-4044-bc98-49e8acfe710a" />
<img width="968" height="594" alt="image" src="https://github.com/user-attachments/assets/7d85e415-5327-4e02-bbd7-9c050dfad175" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
