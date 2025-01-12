<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Creative Designer & Illustrator Portfolio</title>
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            background: linear-gradient(135deg, #f4ebe1 50%, #b22234 50%);
            color: #333;
        }
        a {
            text-decoration: none;
            color: inherit;
        }
        img {
            max-width: 100%;
            display: block;
        }

        /* Header */
        header {
            background: #b22234;
            color: #f4ebe1;
            text-align: center;
            padding: 2.5rem 1rem;
        }
        header h1 {
            font-size: 3.5rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }
        header p {
            font-size: 1.3rem;
            opacity: 0.9;
            margin-bottom: 1rem;
        }
        header button {
            padding: 0.8rem 1.5rem;
            background: #f4ebe1;
            color: #b22234;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            font-weight: bold;
            cursor: pointer;
            transition: background 0.3s ease;
        }
        header button:hover {
            background: #e6d5c6;
        }

        /* Container */
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 3rem auto;
        }

        /* About Section */
        .about {
            text-align: center;
            margin-bottom: 4rem;
        }
        .about h2 {
            font-size: 2.8rem;
            margin-bottom: 1rem;
            color: #b22234;
        }
        .about p {
            font-size: 1.2rem;
            color: #555;
            max-width: 700px;
            margin: 0 auto;
        }

        /* Projects Section */
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        .project-card {
            background: #f4ebe1;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .project-card:hover {
            transform: scale(1.05);
            box-shadow: 0 12px 24px rgba(0, 0, 0, 0.2);
        }
        .project-card img {
            height: 220px;
            object-fit: cover;
        }
        .project-card h3 {
            padding: 1rem;
            font-size: 1.6rem;
            background: #b22234;
            color: #f4ebe1;
            margin: 0;
        }
        .project-card p {
            padding: 1rem;
            font-size: 1rem;
            color: #666;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 1.5rem 0;
            background: #b22234;
            color: #f4ebe1;
            margin-top: 2rem;
        }
        footer p {
            font-size: 1rem;
            opacity: 0.9;
        }
        footer a {
            color: #f4ebe1;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Creative Designer & Illustrator</h1>
        <p>Transforming ideas into stunning visuals and vibrant illustrations.</p>
        <button>Contact Me</button>
    </header>

    <!-- About Section -->
    <div class="container">
        <section class="about">
            <h2>About Me</h2>
            <p>Hi! I’m a passionate designer and illustrator with a love for creating unique, bold, and colorful artwork. From branding to bespoke illustrations, I aim to deliver designs that captivate and inspire.</p>
        </section>

        <!-- Projects Section -->
        <section class="projects">
            <div class="project-card">
                <img src="https://via.placeholder.com/300x200" alt="Project 1">
                <h3>Custom Illustrations</h3>
                <p>A collection of vibrant, hand-drawn illustrations inspired by modern culture and storytelling.</p>
            </div>
            <div class="project-card">
                <img src="https://via.placeholder.com/300x200" alt="Project 2">
                <h3>Brand Identity</h3>
                <p>Crafted a cohesive branding package, including logos, typography, and visual elements.</p>
            </div>
            <div class="project-card">
                <img src="https://via.placeholder.com/300x200" alt="Project 3">
                <h3>Digital Artwork</h3>
                <p>Digital paintings and concepts for marketing campaigns and product launches.</p>
            </div>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>© 2025 Creative Designer & Illustrator | Contact: <a href="mailto:email@example.com">email@example.com</a></p>
    </footer>
</body>
</html>
