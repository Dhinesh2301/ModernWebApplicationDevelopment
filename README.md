# Ex01 Portfolio
## Date:

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
    <title>Portfolio</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background: linear-gradient(to right, #1e3c72, #2a5298);
            color: white;
        }

        /* Container */
        .container {
            width: 80%;
            margin: 50px auto;
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.3);
        }

        /* Header */
        header {
            background: rgba(0, 123, 255, 0.9);
            color: white;
            padding: 20px;
            border-radius: 15px 15px 0 0;
        }

        /* Navigation */
        nav {
            display: flex;
            justify-content: center;
            background: rgba(0, 123, 255, 0.8);
            padding: 10px;
            border-radius: 0 0 15px 15px;
        }

        nav a {
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 16px;
        }

        nav a:hover {
            background: rgba(0, 123, 255, 1);
            border-radius: 5px;
        }

        /* Profile Image */
        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-top: 20px;
            border: 5px solid white;
        }

        /* Sections */
        section {
            padding: 20px;
            margin: 10px;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 10px;
            display: none;
        }

        /* Show section when targeted */
        section:target {
            display: block;
        }

        /* Default visible section */
        #about {
            display: block;
        }

        /* Footer */
        footer {
            margin-top: 20px;
            padding: 10px;
            background: rgba(0, 123, 255, 0.9);
            color: white;
            border-radius: 0 0 15px 15px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>DHINESH R</h1>
            <p>Software Developer</p>
        </header>

        <nav>
            <a href="#about">About</a>
            <a href="#education">Education</a>
            <a href="#experience">Experience</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact</a>
        </nav>
        
        <section id="about">
            <img src="c:\Users\admin\Pictures\Screenshots\dhinesh.jpg" alt="Your Photo" class="profile-pic">
            <h2>DHINESH R</h2>
            <p>Life is very short nanba always be happy.</p>
        </section>
        
        <section id="education">
            <h2>Education</h2>
            <p>BTECH-IT | Saveetha Engineering College -affiliated to Anna University| 2027</p>
        </section>
        
        <section id="experience">
            <h2>Experience</h2>
            <p>Software Developer</p>
            <p>I can understand client or business needs and design software solutions accordingly. I also identify errors and fix bugs in the software to ensure better performance.</p>
        </section>
        
        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li>HTML, CSS, JavaScript</li>
                <li>Python</li>
                <li>DS, JAVA</li>
            </ul>
        </section>
        
        <section id="contact">
            <h2>Contact</h2>
            <p>Email: y23@gmail.com</p>
            <p>Phone: 8531080593</p>
            <p>LinkedIn: <a href="#">Dhinesh R</a></p>
        </section>
        
        <footer>
            <p>&copy; 2025 DHINESH R. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>
```

## OUTPUT
![image](https://github.com/user-attachments/assets/e06819ec-3744-413d-ae53-b22004f98ef6)
![image](https://github.com/user-attachments/assets/e224dda9-059c-4833-9dc5-6691afb0e30c)
![image](https://github.com/user-attachments/assets/9613cc62-1903-4522-95f2-b4c553be3c5d)
![image](https://github.com/user-attachments/assets/a2aa7ea2-2e90-435a-8873-de2b228ee22c)
![image](https://github.com/user-attachments/assets/6397ece1-063b-474e-a56e-f34fcc8301eb)






## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
