<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Riziki Foundation</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#programs">Programs</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Welcome to Riziki Foundation</h1>
        <p>Empowering Communities, Transforming Lives</p>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Riziki Foundation is dedicated to empowering communities through sustainable programs and initiatives.</p>
    </section>

    <section id="programs">
        <h2>Our Programs</h2>
        <div class="program">
            <h3>Education</h3>
            <p>Providing access to quality education for underprivileged children.</p>
        </div>
        <div class="program">
            <h3>Healthcare</h3>
            <p>Improving healthcare services in rural areas.</p>
        </div>
        <div class="program">
            <h3>Community Development</h3>
            <p>Supporting community development projects and initiatives.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Riziki Foundation. All rights reserved.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
