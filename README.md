Celestial Gist — index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Celestial Gist</title>

    <meta name="description" content="Celestial Gist - News, entertainment, media and updates.">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f5f5f5;
            color: #222;
            line-height: 1.6;
        }

        header {
            background: #111;
            color: white;
            padding: 15px 5%;
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .logo img {
            width: 55px;
            height: 55px;
            object-fit: contain;
            border-radius: 50%;
        }

        .logo h1 {
            font-size: 24px;
        }

        nav {
            display: flex;
            gap: 18px;
            margin-top: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #ffd700;
        }

        .hero {
            background: linear-gradient(135deg, #111, #333);
            color: white;
            text-align: center;
            padding: 80px 20px;
        }

        .hero h2 {
            font-size: 42px;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 18px;
            max-width: 650px;
            margin: auto;
        }

        .button {
            display: inline-block;
            margin-top: 25px;
            padding: 12px 25px;
            background: #ffd700;
            color: #111;
            text-decoration: none;
            border-radius: 6px;
            font-weight: bold;
        }

        .section {
            padding: 50px 5%;
            max-width: 1100px;
            margin: auto;
        }

        .section h2 {
            text-align: center;
            margin-bottom: 30px;
            font-size: 30px;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 3px 12px rgba(0,0,0,0.08);
        }

        .card h3 {
            margin-bottom: 10px;
        }

        .about {
            text-align: center;
            background: white;
        }

        .social {
            text-align: center;
        }

        .social a {
            display: inline-block;
            margin: 8px;
            padding: 12px 18px;
            background: #111;
            color: white;
            text-decoration: none;
            border-radius: 6px;
        }

        footer {
            background: #111;
            color: white;
            text-align: center;
            padding: 25px;
            margin-top: 30px;
        }

        @media (max-width: 600px) {
            header {
                justify-content: center;
                text-align: center;
            }

            nav {
                justify-content: center;
                flex-wrap: wrap;
            }

            .hero h2 {
                font-size: 32px;
            }
        }
    </style>
</head>

<body>

    <header>
        <div class="logo">
            <img src="logo.png" alt="Celestial Gist Logo">
            <h1>Celestial Gist</h1>
        </div>

        <nav>
            <a href="#home">Home</a>
            <a href="#news">News</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero" id="home">
        <h2>Welcome to Celestial Gist</h2>

        <p>
            Your source for the latest news, entertainment,
            trending stories and exciting updates.
        </p>

        <a href="#news" class="button">Explore Latest Gist</a>
    </section>

    <section class="section" id="news">
        <h2>Latest Updates</h2>

        <div class="cards">

            <div class="card">
                <h3>📰 Latest News</h3>
                <p>
                    Stay updated with important news and trending
                    stories from around the world.
                </p>
            </div>

            <div class="card">
                <h3>🎬 Entertainment</h3>
                <p>
                    Get the latest entertainment news, celebrity
                    updates, videos and exciting stories.
                </p>
            </div>

            <div class="card">
                <h3>🔥 Trending Gist</h3>
                <p>
                    Discover what's trending and join the conversation
                    with Celestial Gist.
                </p>
            </div>

        </div>
    </section>

    <section class="section about" id="about">
        <h2>About Celestial Gist</h2>

        <p>
            Celestial Gist is a media and entertainment platform
            bringing you news, entertainment, trending stories
            and interesting updates.
        </p>
    </section>

    <section class="section social" id="contact">
        <h2>Follow Celestial Gist</h2>

        <p>Connect with us on social media.</p>

        <!-- Replace the links below with your real profile links -->

        <a href="https://www.tiktok.com/" target="_blank">
            TikTok
        </a>

        <a href="https://www.facebook.com/" target="_blank">
            Facebook
        </a>

        <a href="https://www.youtube.com/" target="_blank">
            YouTube
        </a>
    </section>

    <footer>
        <p>©️ 2026 Celestial Gist. All Rights Reserved.</p>
    </footer>

</body>
</html>
