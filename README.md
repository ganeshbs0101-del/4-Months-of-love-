
<html lang="en">
<head>
<meta charset="UTF-8">
<title>4 Months of Love ❤️</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: url('https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif') no-repeat center center fixed;
    background-size: cover;
    overflow-x: hidden;
    color: #880e4f;
}

/* Hide YouTube iframe */
iframe {
    display: none;
}

/* Sections */
.section {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

/* Cards */
.card, .letter {
    background: rgba(255, 182, 193, 0.92);
    padding: 40px;
    border-radius: 20px;
    text-align: center;
    max-width: 520px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.3);
}

/* Text */
h1, h2 {
    color: #c2185b;
}

p {
    font-size: 18px;
    line-height: 1.7;
}

/* Heart animation */
.heart {
    font-size: 45px;
    animation: beat 1s infinite;
}

@keyframes beat {
    0% { transform: scale(1); }
    50% { transform: scale(1.2); }
    100% { transform: scale(1); }
}

/* Buttons */
button {
    margin-top: 20px;
    padding: 12px 25px;
    background: #d81b60;
    color: white;
    border: none;
    border-radius: 25px;
    font-size: 16px;
    cursor: pointer;
}

button:hover {
    background: #ad1457;
}

/* Rose petals */
.petal {
    position: fixed;
    top: -50px;
    font-size: 24px;
    animation: fall linear infinite;
    pointer-events: none;
}

@keyframes fall {
    0% {
        transform: translateY(0) rotate(0deg);
        opacity: 1;
    }
    100% {
        transform: translateY(110vh) rotate(360deg);
        opacity: 0;
    }
}
</style>
</head>

<body>

<!-- 🎵 Auto-Playing Background Music (Muted for autoplay compliance) -->
<iframe
src="https://www.youtube.com/embed/v_g2tIGeZN4?autoplay=1&loop=1&playlist=v_g2tIGeZN4&mute=1"
allow="autoplay">
</iframe>

<!-- 🌹 Falling Rose Petals -->
<script>
const petalsCount = 30;
for (let i = 0; i < petalsCount; i++) {
    const petal = document.createElement("div");
    petal.className = "petal";
    petal.innerHTML = "🌹";
    petal.style.left = Math.random() * 100 + "vw";
    petal.style.animationDuration = (5 + Math.random() * 5) + "s";
    petal.style.fontSize = (16 + Math.random() * 20) + "px";
    document.body.appendChild(petal);
}
</script>

<!-- ❤️ SECTION 1 -->
<div class="section">
    <div class="card">
        <div class="heart">❤️</div>
        <h1>Happy 4 Months</h1>
        <h2>Ruchitha 💖</h2>

        <p>
            Since <strong>October 4, 2025</strong>,<br>
            every moment with you<br>
            has been filled with love and happiness.
        </p>

        <p>🌹 Forever & Always 🌹</p>

        <button onclick="document.getElementById('letter').scrollIntoView({behavior:'smooth'})">
            Read My Love Letter 💌
        </button>
    </div>
</div>

<!-- 💌 SECTION 2 -->
<div class="section" id="letter">
    <div class="letter">
        <h1>My Dearest Ruchitha 💖</h1>

        <p>
            Just like two playful cats sharing joy,  
            our love is gentle, warm, and full of laughter.  
            These four months have been the most beautiful  
            chapter of my life.
        </p>

        <p>
            I promise to walk beside you,  
            support you,  
            laugh with you,  
            and love you more every single day.
        </p>

        <p style="text-align:right; font-style:italic;">
            Forever yours,<br>
            ❤️ With endless love
        </p>

        <button onclick="window.scrollTo({top:0, behavior:'smooth'})">
            Back to Top ⬆️
        </button>
    </div>
</div>

</body>
</html>
