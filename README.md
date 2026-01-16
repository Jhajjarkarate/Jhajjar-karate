<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Jhajjar District Karate Association</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header class="header">
    <img src="images/logo.png" alt="Jhajjar District Karate Association Logo" class="logo">
    <h1>Jhajjar District Karate Association</h1>
    <h3>झज्जर जिला कराटे एसोसिएशन</h3>
</header>

<nav class="navbar">
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#office">Office Bearers</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<section id="home" class="section home">
    <h2>Welcome / स्वागत है</h2>
    <p>
        Promoting Karate in Jhajjar district with discipline, fitness and self-defence training.
    </p>
    <p>
        झज्जर जिले में अनुशासन, फिटनेस और आत्मरक्षा के साथ कराटे को बढ़ावा देना।
    </p>
</section>

<section id="about" class="section about">
    <h2>About Us / हमारे बारे में</h2>
    <p>
        We organize district & state level championships, training camps and seminars.
    </p>
    <p>
        हम जिला एवं राज्य स्तरीय प्रतियोगिताएं, प्रशिक्षण शिविर और सेमिनार आयोजित करते हैं।
    </p>
</section>

<!-- OFFICE BEARERS SECTION -->
<section id="office" class="section office">
    <h2>Office Bearers / पदाधिकारी</h2>

    <p><strong>President:</strong> Sagar Rathee</p>
    <p><strong>General Secretary:</strong> Abhay Singh</p>

    <p>
        Our office bearers work with dedication to promote karate and sports culture in Jhajjar district.
    </p>
</section>

<section id="contact" class="section contact">
    <h2>Contact Us / संपर्क करें</h2>
    <p><strong>Phone:</strong> 7355813291, 8708361023</p>
    <p>
        <strong>WhatsApp:</strong>
        <a href="https://wa.me/8708361023" target="_blank">8708361023</a>
    </p>
    <p><strong>Location:</strong> Jhajjar, Haryana</p>
</section>

<footer class="footer">
    <p>© 2026 Jhajjar District Karate Association</p>
</footer>

</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: #f2f2f2;
    color: #333;
}

/* HEADER */
.header {
    background: linear-gradient(90deg, #000000, #b71c1c);
    color: white;
    text-align: center;
    padding: 20px 10px;
}

.logo {
    width: 100px;
    margin-bottom: 10px;
}

.header h1 {
    font-size: 24px;
}

.header h3 {
    font-size: 16px;
    font-weight: normal;
}

/* NAVBAR */
.navbar {
    background: #d32f2f;
}

.navbar ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

.navbar ul li a {
    color: white;
    text-decoration: none;
    padding: 12px 18px;
    display: block;
    font-weight: bold;
}

.navbar ul li a:hover {
    background: #9a0007;
}

/* SECTIONS */
.section {
    background: white;
    margin: 20px;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

.section h2 {
    color: #b71c1c;
    margin-bottom: 10px;
}

/* CONTACT LINK */
.contact a {
    color: #d32f2f;
    text-decoration: none;
    font-weight: bold;
}

/* FOOTER */
.footer {
    background: #000;
    color: white;
    text-align: center;
    padding: 12px;
    margin-top: 20px;
}
