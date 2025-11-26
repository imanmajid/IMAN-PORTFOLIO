<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IMAN Portfolio</title>

    <style>
        body { 
            margin: 0;
            font-family: Arial, sans-serif;
            background: #ffffff;
            color: #111;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background: white;
            position: sticky;
            top: 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        header a {
            text-decoration: none;
            margin-left: 20px;
            color: #333;
            font-weight: bold;
        }
        .hero {
            height: 70vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 40px;
        }
        .hero h1 {
            font-size: 55px;
            margin: 0;
        }
        .hero p {
            font-size: 22px;
            margin-top: 10px;
        }
        .projects {
            padding: 50px;
            background: #f4f4f4;
        }
        .projects h2 {
            font-size: 32px;
        }
        .project-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            margin-top: 20px;
        }
        .project-box img {
            width: 100%;
            height: 200px;
            border-radius: 10px;
            object-fit: cover;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #222;
            color: white;
            margin-top: 40px;
        }
    </style>
</head>

<body>

    <header>
        <h2>IMAN Portfolio</h2>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
        </nav>
    </header>

    <section class="hero">
        <h1>Hello, I'm IMAN</h1>
        <p>Aspiring Web Developer • Designer • Creative Thinker</p>
    </section>

    <section class="projects">
        <h2>My Projects</h2>

        <div class="project-grid">
            <div class="project-box"><img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d" /></div>
            <div class="project-box"><img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085" /></div>
            <div class="project-box"><img src="https://images.unsplash.com/photo-1506765515384-028b60a970df" /></div>
            <div class="project-box"><img src="https://images.unsplash.com/photo-1481277542470-605612bd2d61" /></div>
            <div class="project-box"><img src="https://images.unsplash.com/photo-1492724441997-5dc865305da7" /></div>
            <div class="project-box"><img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085" /></div>
        </div>

    </section>

    <footer>
        © 2025 IMAN Portfolio — All Rights Reserved
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About IMAN</title>

    <style>
        body { 
            margin: 0;
            font-family: Arial, sans-serif;
            background: #ffffff;
            color: #111;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background: white;
            position: sticky;
            top: 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        header a {
            text-decoration: none;
            margin-left: 20px;
            color: #333;
            font-weight: bold;
        }
        .container {
            padding: 60px;
            text-align: left;
            max-width: 900px;
            margin: auto;
        }
        .container h1 {
            font-size: 45px;
        }
        .container p {
            font-size: 20px;
            line-height: 1.7;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #222;
            color: white;
            margin-top: 40px;
        }
    </style>
</head>

<body>

    <header>
        <h2>IMAN Portfolio</h2>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
        </nav>
    </header>

    <section class="container">
        <h1>About IMAN</h1>
        <p>
            Hi! I'm IMAN — a passionate learner and an aspiring web developer.
            I enjoy designing clean, minimal, and modern websites.  
            I love learning new skills, solving problems, and creating simple 
            yet beautiful digital experiences.  
            This minimalist 2-page portfolio is part of my growing journey in web development.
        </p>
    </section>

    <footer>
        © 2025 IMAN Portfolio — All Rights Reserved
    </footer>

</body>
</html>
