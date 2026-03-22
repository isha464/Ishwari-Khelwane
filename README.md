<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Ishwari Khelwane | Resume</title>
    <link rel="stylesheet" href="style.css">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>

    <!-- NAVBAR -->
    <nav>
        <h2>Ishwari Khelwane</h2>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#achievements">Achievements</a></li>
            <li><a href="#experience">Experience</a></li>
        </ul>
    </nav>

    <!-- HEADER -->
    <header>
        <h1>Hello, I'm Ishwari 👋</h1>
        <p>BBA DBE Student at IIM Bangalore | B.Com Student</p>
    </header>

    <!-- ABOUT -->
    <section id="about" class="card">
        <h2>About Me</h2>
        <p>
            I am a motivated student pursuing BBA DBE from IIM Bangalore along with a B.Com degree. 
            I am passionate about learning, creativity, and exploring opportunities in business and innovation.
        </p>
    </section>

    <!-- EDUCATION -->
    <section id="education" class="card">
        <h2>Education</h2>
        <ul>
            <li><strong>BBA DBE</strong> – IIM Bangalore</li>
            <li><strong>B.Com</strong> – IBP College</li>
            <li>12th HSC – 78%</li>
            <li>10th SSC – 95%</li>
            <li>CGPA (B.Com Term 1): 8.91</li>
        </ul>
    </section>

    <!-- ACHIEVEMENTS -->
    <section id="achievements" class="card">
        <h2>Achievements</h2>
        <ul>
            <li>100/100 in Sanskrit (10th & 12th)</li>
            <li>School topper in Marathi (96 marks)</li>
            <li>Sanskrit topper (School & College)</li>
            <li>Government Merit Scholarship (5th & 8th)</li>
            <li>Homi Bhabha Scientist Exam – Round 2</li>
            <li>Bronze Medal – Sanskrit Olympiad</li>
            <li>2nd Prize – Junk Art Event (Unmaad)</li>
        </ul>
    </section>

    <!-- EXPERIENCE -->
    <section id="experience" class="card">
        <h2>Experience & Activities</h2>
        <ul>
            <li>Started Diwali Corporate Gift Venture (entrepreneurial learning)</li>
            <li>Conducted Vision Board Workshop (22 participants)</li>
            <li>Participated in Canvas Collective</li>
            <li>Selected for AI Startup Internship</li>
            <li>Worked on multiple case competitions</li>
        </ul>
    </section>

    <!-- FOOTER -->
    <footer>
        <p>© 2026 Ishwari Khelwane</p>
    </footer>

</body>
</html>  
/* RESET */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* BODY */
body {
    font-family: 'Poppins', sans-serif;
    background: #f5f7fa;
    color: #333;
}

/* NAVBAR */
nav {
    background: #2c3e50;
    color: white;
    display: flex;
    justify-content: space-between;
    padding: 15px 40px;
    align-items: center;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: 500;
}

nav a:hover {
    color: #1abc9c;
}

/* HEADER */
header {
    text-align: center;
    padding: 50px;
    background: linear-gradient(to right, #1abc9c, #16a085);
    color: white;
}

header h1 {
    font-size: 40px;
}

header p {
    margin-top: 10px;
    font-size: 18px;
}

/* CARD SECTIONS */
.card {
    background: white;
    margin: 30px auto;
    padding: 25px;
    width: 80%;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

/* HEADINGS */
.card h2 {
    margin-bottom: 15px;
    color: #2c3e50;
}

/* LIST */
.card ul {
    line-height: 1.8;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 20px;
    background: #2c3e50;
    color: white;
    margin-top: 30px;
}
