<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Merry Christmas, Claire ko! ❤️</title>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Montserrat:wght@300;400&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-red: #d63031;
            --soft-pink: #ffefef;
            --gold: #f1c40f;
            --dark-red: #a32626;
        }

        body {
            margin: 0;
            padding: 0;
            font-family: 'Montserrat', sans-serif;
            background-color: var(--soft-pink);
            color: #2d3436;
            overflow-x: hidden;
            text-align: center;
        }

        .snowflakes {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1000;
        }

        header {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)), 
                        url('https://images.unsplash.com/photo-1543589077-47d81606c1bf?q=80&w=2070&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
            color: white;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.5);
        }

        h1 {
            font-family: 'Dancing Script', cursive;
            font-size: 5rem;
            margin-bottom: 10px;
            animation: float 3s ease-in-out infinite;
        }

        .container {
            max-width: 800px;
            margin: -50px auto 50px;
            background: white;
            padding: 50px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            position: relative;
            z-index: 10;
        }

        .letter-text {
            line-height: 1.8;
            font-size: 1.1rem;
            color: #444;
            white-space: pre-line;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
            max-width: 1000px;
            margin: 0 auto;
        }

        .photo-card {
            background: white;
            padding: 10px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transform: rotate(var(--r));
            transition: transform 0.3s;
        }

        .photo-card:hover {
            transform: rotate(0deg) scale(1.05);
            z-index: 20;
        }

        .photo-card img {
            width: 100%;
            height: 300px;
            object-fit: cover;
            border-radius: 5px;
        }

        .cherish-banner {
            background: var(--primary-red);
            color: white;
            padding: 60px 20px;
            margin: 60px 0;
            font-family: 'Dancing Script', cursive;
            font-size: 2.5rem;
        }

        .second-letter {
            margin-top: 20px;
            margin-bottom: 100px;
            border: 2px dashed var(--primary-red);
            background-color: #fff9f9;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }

        footer {
            padding: 50px;
            background: var(--primary-red);
            color: white;
            font-family: 'Dancing Script', cursive;
            font-size: 2rem;
        }

        .snowflake {
            position: absolute;
            color: white;
            user-select: none;
            top: -20px;
            animation: fall linear infinite;
        }

        @keyframes fall {
            to { transform: translateY(100vh); }
        }
    </style>
</head>
<body>

    <div class="snowflakes" id="snow"></div>

    <header>
        <h1>Merry Christmas, Claire ❤️</h1>
        <p style="font-size: 1.5rem;">To my favorite person in the world</p>
    </header>

    <div class="container">
        <h2 style="font-family: 'Dancing Script', cursive; font-size: 3rem; color: var(--primary-red);">My Dearest Claire,</h2>
        <div class="letter-text">
            <p>I wanted to make something special for you this Christmas para kahit papaano mapasaya kita sa pasko mo. You make every day feel like a holiday just by being in it. Thank you for your love, your presence, and for being the beautiful person you are.</p>
            <p>This is just a small digital corner to remind you how much I Love you. I can't wait to spend many more Christmases with you.</p>
            <p><strong>Love, Baby matmat mo.</strong></p>
        </div>
    </div>

    <h2 style="font-family: 'Dancing Script', cursive; font-size: 3rem; color: var(--primary-red);">Our Best Moments</h2>
    
    <div class="gallery">
        <div class="photo-card" style="--r: -3deg">
            <img src="pic1.jpg" alt="Us"> 
            <p>Roblox natin 🎮</p>
        </div>
        <div class="photo-card" style="--r: 2deg">
            <img src="pic2.jpg" alt="Us">
            <p>Our favorite date ☕</p>
        </div>
        <div class="photo-card" style="--r: -1deg">
            <img src="pic3.jpg" alt="Us">
            <p>Happy Times ✨</p>
        </div>
    </div>

    <div class="cherish-banner">
        Every single memory we've shared is a treasure I will cherish forever.
    </div>

    <div class="container second-letter">
        <h2 style="font-family: 'Dancing Script', cursive; font-size: 2.5rem; color: var(--primary-red);">One More Thing...</h2>
        <div class="letter-text">
            <p>Looking at these photos and thinking about our time together makes me realize how much you mean to me. Beyond the gifts and the Christmas lights, the best part of my year has always been you.</p>
            <p>Kahit anong mangyari, I want you to know that I appreciate every little thing you do. Your smile is my favorite Christmas gift.</p>
            <p>You are my home, Claire. Hinding-hindi magbabago yun.</p>
            <p><strong>Always yours,<br>Matmat</strong></p>
        </div>
    </div>

    <footer>
        Merry Christmas, Claire ko! 🎄
    </footer>

    <script>
        function createSnowflake() {
            const snow = document.getElementById('snow');
            const flake = document.createElement('div');
            flake.classList.add('snowflake');
            flake.innerHTML = '❄';
            flake.style.left = Math.random() * 100 + 'vw';
            flake.style.animationDuration = Math.random() * 3 + 2 + 's';
            flake.style.opacity = Math.random();
            flake.style.fontSize = Math.random() * 10 + 10 + 'px';
            snow.appendChild(flake);
            setTimeout(() => { flake.remove(); }, 5000);
        }
        setInterval(createSnowflake, 100);
    </script>
</body>
</html>
