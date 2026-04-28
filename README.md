# Ex01 Portfolio
## Date: 27-04-2026
## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
## STEP 1
Create an HTML file (index.html)

## STEP 2
Create a CSS file (style.css)

## STEP 3
Include a navigation bar with links to different sections.

## STEP 4
Add structured sections for introduction, about, projects, and contact details.

## STEP 5
Define global styles for fonts, colors, and layout.

## STEP 6
Style the header, navigation bar, and sections.

## STEP 7
Use Flexbox or CSS Grid for layout design.

## STEP 8
Add hover effects and transitions for interactivity.

## STEP 9
Add Images and Media.

## STEP 10
Use optimized images for a professional look.

## STEP 11
Open the HTML file in a browser to check layout and functionality.

## STEP 12
Fix styling issues and refine content placement.

## STEP 13
Deploy the Portfolio.

## STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM

### index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio - Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>My Portfolio</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<div class="container">
    <h2>Welcome</h2>
    <p><strong>Name:</strong> RAJASHRI I</p>
    <p><strong>Department:</strong> Computer Science Engineering</p>
    <p><strong>ID:</strong> 212224040261</p>
</div>

</body>
</html>
```

### about.html
```
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio - About</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>About Me</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<div class="container">
    <h2>Achievements</h2>
    <ul>
        <li>Participated Hackathons and built 10+ Projects.</li>
        <li>Completed internship in Full Stack Development in a tech company.</li>
        <li>Scores above 80% in academics</li>
        <li>Completed many workshops and training programs.</li>
    </ul>

    <h2>Hobbies</h2>
    <p>Playing games, coding, watching movies</p>
</div>

</body>
</html>
```

### contact.html
```
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio - Contact</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Contact Me</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<div class="container">
    <h2>Contact Details</h2>
    <p><strong>Phone:</strong> 1234567890</p>
    <p><strong>Email:</strong> rajashri56131@gmail.com</p>

    <h2>Address</h2>
    <p>59E/2, Colachel,Kalimar,<br>KanyaKumari, India</p>
</div>

</body>
</html>
```

### style.css
```

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


body {
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(135deg, #1e1e2f, #2c3e50);
    color: #fff;
    min-height: 100vh;
}


header {
    background: rgba(0, 0, 0, 0.6);
    padding: 20px;
    text-align: center;
    position: sticky;
    top: 0;
}

header h1 {
    font-size: 28px;
    letter-spacing: 1px;
}


nav {
    margin-top: 10px;
}

nav a {
    color: #ddd;
    margin: 0 15px;
    text-decoration: none;
    font-size: 16px;
    position: relative;
    transition: 0.3s;
}


nav a:hover {
    color: #00c6ff;
}


.container {
    width: 85%;
    max-width: 900px;
    margin: 40px auto;
    padding: 30px;
    border-radius: 15px;
    background: rgba(255, 255, 255, 0.08);
    box-shadow: 0 8px 25px rgba(0,0,0,0.4);
    animation: fadeIn 1s ease-in;
}


h2 {
    margin-bottom: 15px;
    color: #00c6ff;
}


ul {
    padding-left: 20px;
    margin-bottom: 20px;
}

ul li {
    margin: 8px 0;
}


p {
    line-height: 1.6;
    margin-bottom: 10px;
}


.container:hover {
    transform: scale(1.02);
    transition: 0.3s;
}


```
## OUTPUT

<img width="1919" height="1079" alt="Screenshot 2026-04-27 131404" src="https://github.com/user-attachments/assets/66f5dd9c-30fc-4245-9c51-2b88eaa8f7cb" />

<img width="1919" height="1079" alt="Screenshot 2026-04-27 131418" src="https://github.com/user-attachments/assets/6bc0ceaf-5dc8-4399-8bbe-c3be01cd6514" />

<img width="1919" height="1079" alt="Screenshot 2026-04-27 131427" src="https://github.com/user-attachments/assets/08df5045-43d7-4f0d-a3b5-1834ed96a936" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
