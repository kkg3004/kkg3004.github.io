# kkg3004.github.io
this is where i make my projects :)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>school</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f8f5e1 url("https://upload.wikimedia.org/wikipedia/commons/4/47/Potato.png") repeat;
            margin: 0;
            padding: 0;
        }
        header {
            background: #bfa76f url("https://upload.wikimedia.org/wikipedia/commons/4/47/Potato.png") center/cover;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            border-bottom: 8px solid #d2b48c;
            box-shadow: 0 4px 16px rgba(191,167,111,0.2);
        }
        nav {
            background: #d2b48c url("https://upload.wikimedia.org/wikipedia/commons/4/47/Potato.png") repeat-x;
            padding: 10px 0;
            text-align: center;
            border-bottom: 4px solid #bfa76f;
        }
        nav a {
            color: #7c5c1e;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            background: #fffbe6;
            padding: 6px 14px;
            border-radius: 20px;
            border: 2px solid #bfa76f;
            transition: background 0.2s;
        }
        nav a:hover {
            background: #f5e2b8;
        }
        main {
            max-width: 900px;
            margin: 40px auto 80px auto;
            background: #fffbe6 url("https://upload.wikimedia.org/wikipedia/commons/4/47/Potato.png") repeat;
            padding: 40px;
            border-radius: 18px;
            box-shadow: 0 2px 16px rgba(191,167,111,0.15);
            border: 6px solid #d2b48c;
        }
        h2, h3 {
            color: #7c5c1e;
        }
        .card {
            background: #f5e2b8 url("https://upload.wikimedia.org/wikipedia/commons/4/47/Potato.png") repeat-x;
            padding: 18px;
            border-radius: 12px;
            margin-bottom: 28px;
            border: 2px solid #bfa76f;
            box-shadow: 0 1px 8px rgba(191,167,111,0.08);
            position: relative;
        }
        .card img, .potato-img {
            max-width: 100px;
            display: block;
            margin: 10px auto;
            border-radius: 50%;
            border: 3px solid #d2b48c;
            background: #fffbe6;
        }
        .potato-row {
            display: flex;
            justify-content: center;
            gap: 18px;
            margin: 10px 0;
        }
        .websites {
            margin-top: 40px;
        }
        .websites h2 {
            margin-bottom: 14px;
        }
        .website-list {
            display: flex;
            flex-wrap: wrap;
            gap: 24px;
            justify-content: center;
        }
        .website-card {
            background: #f5e2b8 url("https://upload.wikimedia.org/wikipedia/commons/4/47/Potato.png") repeat;
            padding: 18px;
            border-radius: 12px;
            width: 240px;
            text-align: center;
            box-shadow: 0 1px 8px rgba(191,167,111,0.08);
            border: 2px solid #bfa76f;
            position: relative;
        }
        .website-card a {
            color: #7c5c1e;
            text-decoration: underline;
            background: #fffbe6;
            padding: 4px 10px;
            border-radius: 10px;
            border: 1px solid #d2b48c;
        }
        .website-card .potato-img {
            margin-bottom: 8px;
        }
        footer {
            background: #bfa76f url('https://upload.wikimedia.org/wikipedia/commons/4/47/Potato.png') center/cover;
            color: #fff;
            text-align: center;
            padding: 18px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
            border-top: 6px solid #d2b48c;
            font-size: 1.1em;
            letter-spacing: 1px;
        }
        /* Potato confetti */
        .potato-confetti {
            position: fixed;
            pointer-events: none;
            z-index: 9999;
            top: 0; left: 0; width: 100vw; height: 100vh;
        }
        .potato-confetti img {
            position: absolute;
            width: 40px;
            opacity: 0.7;
            animation: potato-fall 5s linear infinite;
        }
        @keyframes potato-fall {
            0% { transform: translateY(-60px) rotate(0deg);}
            100% { transform: translateY(110vh) rotate(360deg);}
        }
    </style>
</head>
<body>
    <div class="potato-confetti">
        <!-- Potatoes will be added by JS -->
    </div>
    <header>
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img" style="max-width:60px;" onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=100&q=80';">
        <h1>DC</h1>
        <p>im a subtitle</p>
        <div class="potato-row">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img" onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=100&q=80';">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
        </div>
    </header>
    <nav>
        <a href="https://www.give.org/"><img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" style="width:18px;vertical-align:middle;"> give</a>
        <a href="https://www.usa.gov/"><img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" style="width:18px;vertical-align:middle;"> us</a>
        <a href="https://yourmoney.fdic.gov/"><img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" style="width:18px;vertical-align:middle;"> your</a>
        <a href="https://www.paypal.com/"><img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" style="width:18px;vertical-align:middle;"> money</a>
        <a href="https://nowthenmagazine.com/"><img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" style="width:18px;vertical-align:middle;"> now</a>
        <a href="https://www.pleasefund.us/"><img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" style="width:18px;vertical-align:middle;"> pls</a>
    </nav>
    <main>
        <h2>ts is school</h2>
        <div class="card">
            <h3>our mission</h3>
            <p>To take ur money ngl</p>
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato bag" onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=100&q=80';">
            <div class="potato-row">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
            </div>
        </div>
        <div class="card">
            <h3>events</h3>
            <p><strong>nothing useful:</strong> August 12 2026 the heat death of the universe</p>
            <p><strong>pizza day:</strong> Every day except when you want it</p>
            <p><strong>bring your pet rock:</strong> April 1st, 2099</p>
            <div class="potato-row">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
            </div>
        </div>
        <div class="card">
            <h3>add me</h3>
            <p>email: hornet@skong.ong<br>phone: (800) 420-4167</p>
            <p>discord: @rizzlord#9999</p>
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
        </div>
        <div class="card">
            <h3>random facts</h3>
            <ul>
                <li>Our mascot is a potato. <img src="https://upload.wikimedia.org/wikipedia/commons/4/47/Potato.png" alt="Potato" style="width:24px;vertical-align:middle;"></li>
                <li>We have a pool on the roof (not really). <img src="https://upload.wikimedia.org/wikipedia/commons/4/47/Potato.png" alt="Potato" style="width:24px;vertical-align:middle;"></li>
                <li>Every Friday is opposite day, except when it isn't. <img src="https://upload.wikimedia.org/wikipedia/commons/4/47/Potato.png" alt="Potato" style="width:24px;vertical-align:middle;"></li>
            </ul>
            <div class="potato-row">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
            </div>
        </div>
        <section class="websites">
            <h2>Other Websites</h2>
            <div class="website-list">
                <div class="website-card">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
                    <h3>Fake University</h3>
                    <p>Where learning is optional.</p>
                    <a href="https://www.fakeuniversity.com/">Visit Fake University</a>
                </div>
                <div class="website-card">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
                    <h3>Money Grabbers Inc.</h3>
                    <p>We take your money, you get... something?</p>
                    <a href="https://www.moneygrabbers.com/">Visit Money Grabbers</a>
                </div>
                <div class="website-card">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
                    <h3>Potato Club</h3>
                    <p>All hail the potato.</p>
                    <a href="https://www.potatoclub.com/">Join Potato Club</a>
                </div>
                <div class="website-card">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
                    <h3>Opposite Day HQ</h3>
                    <p>Today is not opposite day. Or is it?</p>
                    <a href="https://www.oppositeday.com/">Go to Opposite Day HQ</a>
                </div>
            </div>
        </section>
        <div class="card">
            <h3>Potato Gallery</h3>
            <div class="potato-row">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" class="potato-img">
            </div>
        </div>
        <div class="card">
            <h3>Potato Counter</h3>
            <p>There are <span id="potato-count">0</span> potatoes on this page!</p>
        </div>
    </main>
    <footer>
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" style="width:28px;vertical-align:middle;" onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=28&q=80';">
        &copy; 67 rizz. no rights reserved here.
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Patates.jpg" alt="Potato" style="width:28px;vertical-align:middle;">
    </footer>
    <script>
        // Potato confetti
        const confetti = document.querySelector('.potato-confetti');
        for(let i=0;i<18;i++){
            const img = document.createElement('img');
            img.src = 'https://upload.wikimedia.org/wikipedia/commons/4/47/Potato.png';
            img.onerror = function() {
                this.onerror = null;
                this.src = 'https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=40&q=80';
            };
            img.style.left = Math.random()*100 + 'vw';
            img.style.top = (-Math.random()*100) + 'px';
            img.style.animationDelay = (Math.random()*5) + 's';
            confetti.appendChild(img);
        }
        // Potato counter
        function countPotatoes() {
            const imgs = document.querySelectorAll('img[src="https://upload.wikimedia.org/wikipedia/commons/4/47/Potato.png"]');
            document.getElementById('potato-count').textContent = imgs.length;
        }
        window.addEventListener('DOMContentLoaded', countPotatoes);
        const footer = document.querySelector('footer');
        const secretLink = document.createElement('a');
        secretLink.href = 'https://en.wikipedia.org/wiki/Potato#Diseases_and_pests';
        secretLink.textContent = 'secret potato hell';
        secretLink.style.position = 'absolute';
        secretLink.style.right = '18px';
        secretLink.style.bottom = '8px';
        secretLink.style.color = '#fff';
        secretLink.style.background = 'rgba(124,92,30,0.7)';
        secretLink.style.padding = '4px 12px';
        secretLink.style.borderRadius = '10px';
        secretLink.style.fontSize = '0.95em';
        secretLink.style.textDecoration = 'none';
        secretLink.style.zIndex = '10001';
        secretLink.style.opacity = '0.5';
        secretLink.onmouseover = () => secretLink.style.opacity = '1';
        secretLink.onmouseout = () => secretLink.style.opacity = '0.5';
        footer.style.position = 'relative';
        footer.appendChild(secretLink);
    </script>
</body>
</html>
