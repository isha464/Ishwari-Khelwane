<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Ishwari Khelwane | Creative Resume</title>
    <link rel="stylesheet" href="style.css">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>

<body>

<!-- NAVBAR -->
<nav class="navbar">
    <h2 class="logo">Ishwari ✨</h2>
    <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#journey">Journey</a></li>
        <li><a href="#achievements">Wins</a></li>
        <li><a href="#projects">Experiences</a></li>
        <li><a href="#contact">Connect</a></li>
    </ul>
</nav>

<!-- HERO SECTION -->
<section class="hero">
    <div class="hero-text">
        <h1>Hi, I'm Ishwari Khelwane 👩‍💻</h1>
        <p>
            BBA DBE @ IIM Bangalore | B.Com Student | Future Entrepreneur 🚀
        </p>
        <button onclick="scrollToSection()">Explore My Journey</button>
    </div>
</section>

<!-- ABOUT -->
<section id="about" class="section glass">
    <h2>About Me</h2>
    <p>
        I’m a curious and driven student from Chhatrapati Sambhajinagar, Maharashtra, currently pursuing 
        BBA DBE from IIM Bangalore along with B.Com. I love combining creativity with business thinking.
        
        From scoring perfect marks in Sanskrit to organizing workshops and exploring entrepreneurship,
        I believe in learning by doing and constantly evolving.
    </p>
</section>

<!-- JOURNEY -->
<section id="journey" class="section">
    <h2>My Academic Journey 🎓</h2>

    <div class="cards">
        <div class="card">
            <h3>10th SSC</h3>
            <p>95% | 100/100 in Sanskrit | Marathi Topper (96)</p>
        </div>

        <div class="card">
            <h3>12th HSC</h3>
            <p>78% | 100/100 in Sanskrit</p>
        </div>

        <div class="card">
            <h3>B.Com</h3>
            <p>IBP College | 8.91 CGPA (Term 1)</p>
        </div>

        <div class="card">
            <h3>BBA DBE</h3>
            <p>IIM Bangalore | Business & Digital Focus</p>
        </div>
    </div>
</section>

<!-- ACHIEVEMENTS -->
<section id="achievements" class="section glass">
    <h2>Achievements 🏆</h2>
    <ul>
        <li>Government Merit Scholarship (5th & 8th)</li>
        <li>Homi Bhabha Exam – Selected for Round 2</li>
        <li>Bronze Medal – Sanskrit Olympiad</li>
        <li>Sanskrit Topper (School & College)</li>
        <li>2nd Prize – Junk Art Event (Unmaad)</li>
    </ul>
</section>

<!-- PROJECTS / EXPERIENCE -->
<section id="projects" class="section">
    <h2>Experiences & Experiments 🚀</h2>

    <div class="cards">
        <div class="card highlight">
            <h3>Diwali Venture 🎁</h3>
            <p>Started a corporate gifting venture. Though it didn’t scale, it taught real-world business lessons.</p>
        </div>

        <div class="card highlight">
            <h3>Vision Board Workshop 🎯</h3>
            <p>Conducted a workshop with 22 participants in Sambhajinagar.</p>
        </div>

        <div class="card highlight">
            <h3>Creative Participation 🎨</h3>
            <p>Participated in Canvas Collective and multiple creative events.</p>
        </div>

        <div class="card highlight">
            <h3>AI Startup Internship 🤖</h3>
            <p>Selected for internship + actively working on case competitions.</p>
        </div>
    </div>
</section>

<!-- CONTACT -->
<section id="contact" class="section glass">
    <h2>Let's Connect 💬</h2>

    <p><strong>📍 Location:</strong> Chhatrapati Sambhajinagar, Maharashtra</p>
    <p><strong>📞 Phone:</strong> 9423153829</p>

    <div class="socials">
        <a href="https://www.linkedin.com/in/ishwari-khelwane-b4190b386" target="_blank">LinkedIn</a>
        <a href="https://instagram.com/itsishaactually" target="_blank">Instagram</a>
    </div>
</section>

<!-- FOOTER -->
<footer>
    <p>Built with 💙 by Ishwari</p>
</footer>

<script>
function scrollToSection() {
    document.getElementById("about").scrollIntoView({ behavior: "smooth" });
}
</script>
/* RESET */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* BODY */
body {
    font-family: 'Outfit', sans-serif;
    background: linear-gradient(135deg, #1f1c2c, #928dab);
    color: white;
}

/* NAVBAR */
.navbar {
    display: flex;
    justify-content: space-between;
    padding: 20px 50px;
    position: sticky;
    top: 0;
    background: rgba(0,0,0,0.3);
    backdrop-filter: blur(10px);
}

.navbar ul {
    display: flex;
    gap: 20px;
    list-style: none;
}

.navbar a {
    color: white;
    text-decoration: none;
}

/* HERO */
.hero {
    height: 90vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}

.hero h1 {
    font-size: 48px;
}

.hero button {
    margin-top: 20px;
    padding: 10px 20px;
    border: none;
    background: #ff7eb3;
    color: white;
    border-radius: 20px;
    cursor: pointer;
}

/* SECTIONS */
.section {
    padding: 60px 10%;
}

/* GLASS EFFECT */
.glass {
    background: rgba(255,255,255,0.1);
    backdrop-filter: blur(15px);
    border-radius: 15px;
}

/* CARDS */
.cards {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 20px;
}

.card {
    background: white;
    color: black;
    padding: 20px;
    border-radius: 15px;
    width: 250px;
    transition: transform 0.3s;
}

.card:hover {
    transform: scale(1.05);
}

.highlight {
    background: linear-gradient(135deg, #ff9a9e, #fad0c4);
}

/* CONTACT */
.socials a {
    display: inline-block;
    margin: 10px;
    padding: 10px 15px;
    background: white;
    color: black;
    border-radius: 10px;
    text-decoration: none;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 20px;
}

</body>
</html>
