# -creative-portfolio-website
26043010087.                                               A modern, responsive personal portfolio website built using HTML and CSS. Features a clean dark theme, interactive hover effects, project cards, smooth navigation, and a mobile-friendly layout. Perfect for beginners learning web development and showcasing creative projects.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Creative Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #101827, #253b60);
            color: white;
            min-height: 100vh;
        }

        header {
            padding: 25px 10%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h2 {
            color: #38bdf8;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }

        .hero {
            min-height: 75vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 30px 20px;
        }

        .hero h1 {
            font-size: clamp(35px, 7vw, 65px);
            margin-bottom: 20px;
        }

        .hero h1 span {
            color: #38bdf8;
        }

        .hero p {
            max-width: 550px;
            line-height: 1.8;
            color: #d1d5db;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            background: #38bdf8;
            color: #101827;
            padding: 14px 28px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn:hover {
            background: white;
            transform: translateY(-4px);
        }

        .projects {
            padding: 40px 10% 70px;
            text-align: center;
        }

        .projects h2 {
            margin-bottom: 30px;
            color: #38bdf8;
        }

        .cards {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .card {
            background: #1e293b;
            padding: 25px;
            border-radius: 15px;
            width: 250px;
            border: 1px solid #334155;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-8px);
            border-color: #38bdf8;
        }

        .card h3 {
            margin-bottom: 12px;
        }

        .card p {
            color: #cbd5e1;
            line-height: 1.6;
        }

        footer {
            text-align: center;
            padding: 25px;
            color: #cbd5e1;
            border-top: 1px solid #334155;
        }

        @media (max-width: 600px) {
            header {
                padding: 20px;
                flex-direction: column;
                gap: 15px;
            }

            nav a {
                margin: 0 8px;
            }
        }
    </style>
</head>

<body>

    <header>
        <h2>MyPortfolio</h2>
        <nav>
            <a href="#home">Home</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero" id="home">
        <h1>Hello, I'm a <span>Creator.</span></h1>

        <p>
            Welcome to my digital space! I enjoy exploring technology,
            building creative projects, and turning ideas into reality.
        </p>

        <a href="#projects" class="btn">Explore My Work</a>
    </section>

    <section class="projects" id="projects">
        <h2>My Projects</h2>

        <div class="cards">
            <div class="card">
                <h3>🌐 Web Design</h3>
                <p>Creating modern, responsive, and user-friendly websites.</p>
            </div>

            <div class="card">
                <h3>🤖 Artificial Intelligence</h3>
                <p>Exploring AI tools and innovative technology solutions.</p>
            </div>

            <div class="card">
                <h3>💡 Creative Ideas</h3>
                <p>Turning simple ideas into interesting digital experiences.</p>
            </div>
        </div>
    </section>

    <footer id="contact">
        <p>Thanks for visiting my portfolio!</p>
        <p>© 2026 MyPortfolio | Built with HTML and CSS</p>
    </footer>

</body>
</html>
