# Nai-website
Nai
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Support Channel Naii!</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(135deg,#0f2027,#203a43,#2c5364);
    color: white;
    text-align: center;
}

/* HEADER */
header {
    padding: 60px 20px;
}

header h1 {
    font-size: 42px;
    color: #00eaff;
    text-shadow: 0 0 20px #00eaff;
}

/* CARD */
.card {
    margin: auto;
    margin-top: 40px;
    width: 90%;
    max-width: 420px;
    padding: 30px;
    border-radius: 15px;
    background: rgba(255,255,255,0.05);
    backdrop-filter: blur(10px);
    box-shadow: 0 0 25px rgba(0,234,255,0.3);
    animation: fadeIn 1.2s ease;
}

.card h2 {
    margin-bottom: 10px;
}

.card p {
    opacity: 0.8;
}

/* BUTTON */
.btn {
    display: inline-block;
    margin-top: 25px;
    padding: 15px 35px;
    font-size: 18px;
    border-radius: 10px;
    background: linear-gradient(45deg,#ff0000,#ff7300);
    color: white;
    text-decoration: none;
    transition: 0.3s;
    box-shadow: 0 0 20px rgba(255,0,0,0.6);
}

.btn:hover {
    transform: scale(1.1);
    box-shadow: 0 0 40px rgba(255,0,0,1);
}

/* SUBSCRIBE TEXT */
#thanks {
    margin-top: 25px;
    font-size: 20px;
    color: gold;
    opacity: 0;
    transition: 0.5s;
}

.show {
    opacity: 1 !important;
}

/* FOOTER */
footer {
    margin-top: 80px;
    padding: 20px;
    font-size: 14px;
    opacity: 0.6;
}

/* ANIMATION */
@keyframes fadeIn {
    from {opacity:0; transform: translateY(30px);}
    to {opacity:1; transform: translateY(0);}
}
</style>
</head>

<body>

<header>
    <h1>🔥 SUPPORT CHANNEL NAI! 🔥</h1>
    <p>Channel gaming & seru-seruan! Jangan lupa subscribe ya!</p>
</header>

<div class="card">
    <h2>🎮 Naii Channel</h2>
    <p>
        Konten gaming, mabar, dan hiburan.<br>
        Klik tombol di bawah buat langsung ke YouTube!
    </p>

    <a class="btn"
       href="https://youtube.com/@naii12345?si=ZuOgJUKnTBHpAOrN"
       target="_blank"
       onclick="showThanks()">
       ▶ KUNJUNGI CHANNEL
    </a>

    <div id="thanks">🔥 Makasih udah support bang! 🔥</div>
</div>

<footer>
    © 2026 Naii Squad — Gas Terus Upload!
</footer>

<script>
function showThanks(){
    document.getElementById("thanks").classList.add("show");
}
</script>

</body>
</html>
