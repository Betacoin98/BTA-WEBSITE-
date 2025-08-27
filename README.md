<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BTA – The Future of Digital Money</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Orbitron', sans-serif;
            background: linear-gradient(135deg, #0d0d0d, #1a1a1a);
            color: #fff;
            scroll-behavior: smooth;
        }
        nav {
            position: fixed;
            width: 100%;
            background: rgba(10,10,10,0.9);
            display: flex;
            justify-content: center;
            padding: 15px 0;
            z-index: 1000;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #00ffff;
        }
        section {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 50px 20px;
        }
        .btn {
            padding: 15px 30px;
            background: linear-gradient(90deg, #00ffff, #00ffcc);
            border: none;
            border-radius: 30px;
            color: #000;
            font-size: 1.2em;
            font-weight: bold;
            cursor: pointer;
            margin-top: 20px;
            text-decoration: none;
            transition: transform 0.3s;
        }
        .btn:hover {
            transform: scale(1.1);
        }
        #home {
            background: url('https://i.ibb.co/7kqGxP1/crypto-background.jpg') center/cover no-repeat;
            color: #fff;
        }
        #home h1 {
            font-size: 3em;
            margin: 20px 0;
        }
        #about, #how, #contact {
            background: rgba(0,0,0,0.7);
            border-radius: 20px;
            padding: 40px;
            max-width: 900px;
        }
        ul.steps {
            list-style: none;
            padding: 0;
            text-align: left;
        }
        ul.steps li {
            margin: 15px 0;
            font-size: 1.2em;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 10px;
            border: none;
        }
        button.send {
            padding: 15px 30px;
            border-radius: 30px;
            border: none;
            background: linear-gradient(90deg, #00ffff, #00ffcc);
            font-weight: bold;
            cursor: pointer;
        }
        footer {
            padding: 20px;
            text-align: center;
            background: #0a0a0a;
        }
    </style>
</head>
<body>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#how">How to Buy</a>
    <a href="#contact">Contact</a>
</nav>

<section id="home">
    <img src="https://i.ibb.co/6Z7Q5Qd/bta-logo.png" alt="BTA Logo" width="200">
    <h1>BTA – The Future of Digital Money</h1>
    <a class="btn" href="https://moonshot.com/9tAgw5Xcpssefh7CjsxPFSeyrWyfwuM8C6ngC4zZmoon?ref=jcFjYg4eLZ" target="_blank">Buy on Moonshot</a>
</section>

<section id="about">
    <h2>About BTA</h2>
    <p>BTA is a next-generation digital currency designed for fast, secure, and borderless transactions. Available exclusively on Moonshot.</p>
    <div>
        <p>🔒 Secure &nbsp; ⚡ Fast &nbsp; 🌐 Decentralized</p>
    </div>
</section>

<section id="how">
    <h2>How to Buy BTA</h2>
    <ul class="steps">
        <li>1. Go to Moonshot.</li>
        <li>2. Create an account or log in.</li>
        <li>3. Buy BTA securely in minutes.</li>
    </ul>
    <a class="btn" href="https://moonshot.com/9tAgw5Xcpssefh7CjsxPFSeyrWyfwuM8C6ngC4zZmoon?ref=jcFjYg4eLZ" target="_blank">Buy Now</a>
</section>

<section id="contact">
    <h2>Contact</h2>
    <form action="mailto:youremail@example.com" method="post" enctype="text/plain">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
        <button class="send" type="submit">Send Message</button>
    </form>
</section>

<footer>
    &copy; 2025 BTA. All rights reserved.
</footer>

</body>
</html>
