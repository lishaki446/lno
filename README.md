<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cutie - Cute Delight</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Cute Delight!</h1>
        <p>🌸 Discover Adorable Treasures 🌸</p>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Home</h2>
            <div id="homepage-content">
                <!-- Homepage content goes here -->
            </div>
        </section>
        <section id="about">
            <h2>About Us</h2>
            <div id="about-content">
                <!-- About section content goes here -->
            </div>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <div id="contact-info">
                <!-- Contact information goes here -->
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Cute Delight</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #FFC0CB; /* Soft Pink */
}

header {
    background: #FF69B4; /* Hot Pink */
    color: #fff;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    background: #FFFACD; /* Light Yellow */
    text-align: center;
}

nav ul li {
    display: inline;
    margin-right: 10px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    padding: 10px 15px;
    display: inline-block;
}

nav ul li a:hover {
    background: #98FF98; /* Mint Green */
}

main {
    padding: 20px;
    margin: 10px;
}

section {
    margin-bottom: 20px;
    background: #fff;
    padding: 20px;
    border-radius: 5px;
}

footer {
    text-align: center;
    background: #E6E6FA; /* Pastel Purple */
    color: #fff;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
document.addEventListener('DOMContentLoaded', () => {
    // Homepage content
    document.getElementById('homepage-content').innerHTML = `
        <p><strong>Welcome to Cute Delight!</strong></p>
        <p>🌸 <strong>Discover Adorable Treasures</strong> 🌸</p>
        <p>At Cute Delight, we believe in the magic of cuteness! Our carefully curated collection of adorable and whimsical items is designed to bring joy to girls of all ages...</p>
        <!-- Add more homepage content here -->
    `;

    // About section content
    document.getElementById('about-content').innerHTML = `
        <p><strong>About Us</strong></p>
        <p>🌸 <strong>Welcome to Cute Delight!</strong> 🌸</p>
        <p>At Cute Delight, we are passionate about bringing a touch of whimsy and happiness into the lives of girls everywhere. Our mission is to create a magical shopping experience...</p>
        <!-- Add more about section content here -->
    `;

    // Contact information
    document.getElementById('contact-info').innerHTML = `
        <p><strong>Contact Us</strong></p>
        <p>We’d love to hear from you! Whether you have a question, need assistance, or just want to share your love for all things cute, our team at Cute Delight is here to help...</p>
        <p>📧 <strong>Email:</strong> support-cutedelight@gmail.com</p>
    `;
});
