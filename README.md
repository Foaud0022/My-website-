# My-website-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Freelance Services</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Freelance Services</h1>
        <nav>
            <ul>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="services">
            <h2>My Services</h2>
            <div class="service">
                <h3>Accounting</h3>
                <p>Providing comprehensive accounting services for small businesses.</p>
            </div>
            <div class="service">
                <h3>Graphic Design</h3>
                <p>Creating stunning graphics for your branding and marketing needs.</p>
            </div>
            <div class="service">
                <h3>Web Development</h3>
                <p>Building responsive and user-friendly websites.</p>
            </div>
            <div class="service">
                <h3>Content Writing</h3>
                <p>Crafting engaging content tailored to your audience.</p>
            </div>
        </section>

        <section id="portfolio">
            <h2>Portfolio</h2>
            <p>Check out some of my previous work:</p>
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/300x200?text=Project+1" alt="Project 1">
                <p>Project 1 Description</p>
            </div>
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/300x200?text=Project+2" alt="Project 2">
                <p>Project 2 Description</p>
            </div>
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/300x200?text=Project+3" alt="Project 3">
                <p>Project 3 Description</p>
            </div>
        </section>

        <section id="testimonials">
            <h2>Testimonials</h2>
            <blockquote>
                "Fantastic service! Highly recommend!" - Client A
            </blockquote>
            <blockquote>
                "Professional and efficient. Will hire again!" - Client B
            </blockquote>
        </section>

        <section id="contact">
            <h2>Contact Me</h2>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 My Freelance Services. All rights reserved.</p>
    </footer>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    padding: 10px 20px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 15px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 20px;
}

section {
    margin: 20px 0;
}

.service, .portfolio-item {
    border: 1px solid #ddd;
    padding: 10px;
    margin: 10px 0;
}

.portfolio-item img {
    max-width: 100%;
    height: auto;
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #333;
    color: #fff;
    position: relative;
    bottom: 0;
    width: 100%;
}

form {
    display: flex;
    flex-direction: column;
}

form label {
    margin: 10px 0 5px;
}

form input, form textarea {
    padding: 8px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
}

form button {
    padding: 10px;
    background-color: #333;
    color: #fff;
    border: none;
    cursor: pointer;
}

form button:hover {
    background-color: #555;
}
