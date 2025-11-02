<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Happy Birthday Sthitilragna 💋</title>

<style>
  /* 🌸 Basic Styling and Theme Colors */
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');
  :root {
    --bg:#fef6f8;
    --accent:#ff6b9a; /* 💖 Change this color if you want a new theme */
    --soft:#fff0f3;
  }
  * {box-sizing:border-box;font-family:'Poppins',sans-serif;}
  body {margin:0;background:linear-gradient(180deg,#fff 0%,#fff7fb 100%);color:#222;}
  .container {max-width:980px;margin:30px auto;padding:20px;}
  .card {background:#fff;border-radius:18px;box-shadow:0 10px 30px rgba(0,0,0,0.08);overflow:hidden;}
  .hero {position:relative;height:500px;background:#000;}
  .hero img {width:100%;height:100%;object-fit:cover;}
  .overlay {position:absolute;inset:0;display:flex;flex-direction:column;justify-content:flex-end;padding:28px;background:linear-gradient(180deg,transparent,rgba(0,0,0,0.45));color:#fff;}
  h1 {margin:0;font-size:36px;text-shadow:0 4px 18px rgba(0,0,0,0.45);}
  .sub {font-size:18px;opacity:0.9;margin-top:6px;}
  .message {padding:30px;display:flex;gap:20px;align-items:center;}
  .message img {width:140px;height:140px;border-radius:12px;object-fit:cover;box-shadow:0 8px 20px rgba(0,0,0,0.06);}
  .message p {font-size:18px;line-height:1.5;color:#333;}
  .gallery {display:grid;grid-template-columns:1fr 1fr;gap:14px;padding:22px;}
  .gallery img {width:100%;height:220px;object-fit:cover;border-radius:12px;transition:transform .3s;}
  .gallery img:hover {transform:scale(1.03);}
  .footer {padding:20px;border-top:1px dashed rgba(0,0,0,0.06);text-align:center;font-weight:600;color:#444;}
  /* Floating hearts animation */
  .hearts {position:fixed;inset:0;pointer-events:none;}
  .hearts i {position:absolute;opacity:0.9;font-size:20px;animation:floatUp linear infinite;}
  @keyframes floatUp {
    from {transform:translateY(30vh) scale(0.6);opacity:0;}
    10% {opacity:1;}
    to {transform:translateY(-20vh) scale(1.1);opacity:0;}
  }
</style>
</head>

<body>
<div class="hearts" id="hearts"></div>

<div class="container">
  <div class="card">
    <!-- 🌸 Main Hero Section -->
    <div class="hero">
      <img src="main.jpg" alt="Sthitilragna" /> <!-- 📸 Replace main.jpg with her best photo -->
      <div class="overlay">
        <h1>Happy Birthday, <span style="color:var(--accent)">Sthitilragna 💋</span></h1>
        <div class="sub">3 November 2005 — My favourite person</div>
      </div>
    </div>

    <!-- 💌 Birthday Message Section -->
    <div class="message">
      <img src="main.jpg" alt="Sthitilragna" />
      <p>
        <!-- 💌 Edit your personal message below -->
        <strong>To mo dhana 💋, Happy Birthday💋!</strong><br><br>
        Thank you for being my partner, my best friend, and my greatest adventure. 
        I cherish every moment we've shared and I'm so excited for all the ones to come. 
        God bless you!<br><br>
        <em style="color:var(--accent)">— From Sachin 💖</em>
      </p>
    </div>

    <!-- 📸 Funny / Cute Photos Section -->
    <h3 style="text-align:center;color:#ff6b9a;">Cute & Funny Moments 😄</h3>
    <div class="gallery">
      <!-- 📸 Add or replace photos here -->
      <img src="fun1.jpg" alt="funny photo 1" />
      <img src="fun2.jpg" alt="funny photo 2" />
    </div>

    <!-- 🎶 Optional Background Music -->
    <!-- Add a file named instrumental.mp3 in same folder -->
    <audio id="bgMusic" loop>
      <source src="instrumental.mp3" type="audio/mpeg">
    </audio>

    <div class="footer">
      Made with ❤️ by Sachin for Sthitilragna 💋
    </div>
  </div>
</div>

<script>
  // 💖 Floating hearts effect
  const hearts = document.getElementById('hearts');
  function makeHeart() {
    const i = document.createElement('i');
    i.textContent = '💖';
    i.style.left = Math.random()*100 + '%';
    i.style.animationDuration = (6 + Math.random()*6) + 's';
    hearts.appendChild(i);
    setTimeout(()=>i.remove(),12000);
  }
  setInterval(makeHeart,700);
</script>

</body>
</html>