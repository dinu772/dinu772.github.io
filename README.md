<!-- Shayari Card with Action Buttons -->
<div class="shayari-card">
  <p>"जो चलते रहे तूफानों में,<br>वही रौशनी बनते हैं ज़माने में।"</p>

  <div class="shayari-actions">
    <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
    <button onclick="commentShayari()">💬</button>
    <button onclick="shareShayari()">🔗</button>
  </div>
</div>

<!-- Shayari Style + Button Design -->
<style>
.shayari-card {
  background: rgba(255, 255, 255, 0.05);
  border: 1px solid #ff00ff;
  border-radius: 15px;
  padding: 20px;
  margin: 30px auto;
  max-width: 600px;
  text-align: center;
  box-shadow: 0 0 15px #ff00ff55;
  font-family: 'Poppins', sans-serif;
  color: white;
}

.shayari-card p {
  font-size: 1.2rem;
  text-shadow: 0 0 5px #fff;
}

.shayari-actions {
  margin-top: 15px;
}

.shayari-actions button {
  background: transparent;
  color: #ff00ff;
  border: none;
  font-size: 1.5rem;
  cursor: pointer;
  margin: 0 10px;
  transition: transform 0.2s;
}

.shayari-actions button:hover {
  transform: scale(1.3);
  text-shadow: 0 0 10px #ff00ff;
}
</style>

<!-- Shayari Action Script -->
<script>
  function likeShayari(btn) {
    const countSpan = btn.querySelector(".like-count");
    let current = parseInt(countSpan.innerText);
    countSpan.innerText = current + 1;
  }

  function commentShayari() {
    const userComment = prompt("💬 Apna comment likhiye:");
    if (userComment) {
      alert("✅ Comment received: " + userComment);
    }
  }

  function shareShayari() {
    const link = window.location.href;
    navigator.clipboard.writeText(link);
    alert("🔗 Link copied! Share it with your friends.");
  }
</script>
<!-- Shayari Card -->
<div class="shayari-card">
  <p class="shayari-text">
    🔥 "मंज़िल मिलेगी भटक कर ही सही,<br>
    गुमराह तो वो हैं जो घर से निकले ही नहीं।"
  </p>

  <!-- Action Icons -->
  <div class="shayari-actions">
    <span title="Like">❤️</span>
    <span title="Comment">💬</span>
    <span title="Share">🔗</span>
  </div>
</div>

<!-- CSS Style (add in <style> tag or CSS file) -->
<style>
.shayari-card {
  background: rgba(255, 255, 255, 0.05);
  border: 1px solid #ff00ff;
  border-radius: 15px;
  padding: 20px;
  margin: 40px auto;
  max-width: 600px;
  color: #fff;
  text-align: center;
  font-family: 'Poppins', sans-serif;
  box-shadow: 0 0 20px #ff00ff77;
}

.shayari-text {
  font-size: 1.3rem;
  line-height: 1.8;
  text-shadow: 0 0 5px #fff;
}

.shayari-actions {
  margin-top: 15px;
  font-size: 1.5rem;
}

.shayari-actions span {
  margin: 0 15px;
  cursor: pointer;
  transition: transform 0.2s;
}

.shayari-actions span:hover {
  transform: scale(1.3);
  text-shadow: 0 0 10px #ff00ff;
}
</style>
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Dinu Meghwanshi",
  "alternateName": "JBR KING DINU",
  "url": "https://dinu772.github.io/",
  "sameAs": [
    "https://www.instagram.com/dinu_meghwanshiii"
  ],
  "jobTitle": "Motivational Creator",
  "address": {
    "@type": "PostalAddress",
    "addressLocality": "Bhilwara",
    "addressRegion": "Rajasthan",
    "addressCountry": "India"
  }
}
</script>
<!-- About Me search
<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <title>भारत राजस्थान - Neon Background</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: radial-gradient(circle at center, #1f0036, #000000);
      overflow: hidden;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Arial', sans-serif;
    }

    .neon-text {
      font-size: 5rem;
      color: #fff;
      text-align: center;
      text-transform: uppercase;
      text-shadow:
        0 0 5px #f0f,
        0 0 10px #f0f,
        0 0 20px #f0f,
        0 0 40px #f0f,
        0 0 80px #f0f;
    }
  </style>
</head>
<body>
  <div class="neon-text">
    भारत<br>राजस्थान
  </div>
</body>
</html>
<!-- About Me Section -->
<section style="text-align: center; padding: 50px 20px; color: white;">
  <h2 style="font-size: 2.5rem; text-shadow: 0 0 10px #f0f;">🙋‍♂️ About Me</h2>
  <p style="font-size: 1.2rem; margin-top: 15px;">
    🔹 Name: <strong>Dinu Meghwanshi</strong><br>
    🔹 Location: <strong>Bhilwara, Rajasthan (India)</strong><br><br>
    🔗 Contact me:
  </p>

  <!-- Instagram Icon + Link -->
  <a href="https://www.instagram.com/dinu_meghwanshiii?igsh=cGRvbHd0NmhjYncz" target="_blank" style="text-decoration: none;">
    <img src="https://img.icons8.com/fluency/48/instagram-new.png" alt="Instagram" style="vertical-align: middle; margin-top: 10px;">
    <span style="color: #ff00ff; font-weight: bold; margin-left: 8px;">Follow on Instagram</span>
  </a>
</section>
<h1>𝓓𝓲𝓷𝓾 𝓜𝓮𝓰𝓱𝔀𝓪𝓷𝓼𝓱𝓲</h1>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="title" content="JBR KING DINU MEGHWANSHI | Official Website">
  <meta name="description" content="Official website of Dinu Meghwanshi aka JBR KING DINU from Bhilwara, Rajasthan. Follow on Instagram, YouTube, Discord. Motivational content & more.">
  <meta name="keywords" content="Dinu, JBR, JBR KING DINU, JBR KING, Dinu Meghwanshi, JBR KING DINU MEGHWANSHI, JBR Dinu Meghwansi, Rajasthani Dinu, Meghwansi boy, Bhilwara wala Dinu">
  <meta name="author" content="Dinu Meghwanshi">
  <meta name="robots" content="index, follow">

  <!-- Open Graph for Social Sharing -->
  <meta property="og:title" content="JBR KING DINU MEGHWANSHI">
  <meta property="og:description" content="Official website of Dinu Meghwanshi from Bhilwara, Rajasthan.">
  <meta property="og:url" content="https://dinu772.github.io/">
  <meta property="og:type" content="website">

  <!-- Favicon (optional) -->
  <link rel="icon" href="https://img.icons8.com/fluency/48/instagram-new.png">
  
  <title>JBR KING DINU MEGHWANSHI</title>
</head>
<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <title>भारत राजस्थान - Neon Background</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: radial-gradient(circle at center, #1f0036, #000000);
      overflow: hidden;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Arial', sans-serif;
    }

    .neon-text {
      font-size: 5rem;
      color: #fff;
      text-align: center;
      text-transform: uppercase;
      text-shadow:
        0 0 5px #f0f,
        0 0 10px #f0f,
        0 0 20px #f0f,
        0 0 40px #f0f,
        0 0 80px #f0f;
    }
  </style>
</head>
<body>
  <div class="neon-text">
    भारत<br>राजस्थान
  </div>
</body>
</html>
