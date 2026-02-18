<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Adrian Edits</title>

<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: #0f0f0f;
        color: white;
        text-align: center;
    }

    header {
        background: linear-gradient(90deg, #ff0000, #9900ff);
        padding: 40px 20px;
    }

    h1 {
        margin: 0;
        font-size: 3rem;
    }

    .section {
        padding: 40px 20px;
    }

    .videos {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 20px;
        max-width: 900px;
        margin: auto;
    }

    .card {
        background: #1a1a1a;
        padding: 20px;
        border-radius: 15px;
        transition: 0.3s;
    }

    .card:hover {
        transform: scale(1.05);
        background: #222;
    }

    button {
        background: #ff0000;
        border: none;
        padding: 12px 25px;
        color: white;
        font-size: 16px;
        border-radius: 10px;
        cursor: pointer;
        transition: 0.3s;
    }

    button:hover {
        background: #cc0000;
    }

    footer {
        padding: 20px;
        background: #111;
        font-size: 14px;
        color: gray;
    }
</style>
</head>

<body>

<header>
    <h1>Adrian Edits</h1>
    <p>Anime • Edits • Creative Videos</p>
</header>

<section class="section">
    <h2>🔥 Featured Videos</h2>
    <div class="videos">
        <div class="card">
            <h3>Demon Slayer Edit</h3>
            <p>High energy anime edit</p>
        </div>
        <div class="card">
            <h3>Gear 5 Luffy</h3>
            <p>Epic transformation edit</p>
        </div>
        <div class="card">
            <h3>Comment Your Anime</h3>
            <p>I turn comments into edits</p>
        </div>
    </div>
</section>

<section class="section">
    <h2>📩 Contact Me</h2>
    <p>Want a custom edit?</p>
    <button onclick="alert('DM me on YouTube!')">Message Me</button>
</section>

<footer>
    © 2026 Adrian Edits | Built by Me
</footer>

</body>
</html>
