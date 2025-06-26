
    .welcome-text {
      text-align: center;
      font-size: 48px;
      font-weight: bold;
      margin-top: 50px;
      background: linear-gradient(90deg, #ff6a00, #ee0979, #00c9ff);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: glow 2s infinite alternate;
    }

    @keyframes glow {
      from {
        text-shadow: 0 0 10px #ff6a00, 0 0 20px #ee0979;
      }
      to {
        text-shadow: 0 0 20px #00c9ff, 0 0 30px #00c9ff;
      }
    }
  </style>
</head>
<body>

  <h1 class="welcome-text">Welcome to My Website</h1>

</body>
</html>
<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Love Shayari 💖</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: url('https://images.unsplash.com/photo-1517849845537-4d257902454a?auto=format&fit=crop&w=1600&q=80') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
      margin: 0;
      padding: 30px;
    }

    .shayari-card {
      background: rgba(0, 0, 0, 0.65);
      border-radius: 15px;
      padding: 20px;
      margin-bottom: 25px;
      box-shadow: 0 0 20px rgba(255, 0, 100, 0.3);
    }

    .shayari {
      font-size: 20px;
      margin-bottom: 15px;
    }

    .shayari-actions {
      display: flex;
      gap: 10px;
    }

    .shayari-actions button {
      background: #ff1c78;
      color: white;
      border: none;
      padding: 8px 14px;
      font-size: 16px;
      border-radius: 8px;
      cursor: pointer;
      transition: 0.3s;
    }

    .shayari-actions button:hover {
      background: #ff4c98;
    }

    .like-count {
      margin-left: 5px;
      color: #fff700;
    }

    h1 {
      text-align: center;
      font-size: 36px;
      color: #ffaad4;
      margin-bottom: 40px;
      text-shadow: 2px 2px 4px #000;
    }

    .credit {
      margin-top: 50px;
      text-align: center;
      font-size: 18px;
      font-style: italic;
      color: #ffc7e3;
    }
  </style>
</head>
<body>

  <h1>💖 तेरे इश्क़ में... 💖</h1>

  <!-- Shayari Block -->
  <div class="shayari-card">
    <div class="shayari">तू पास नहीं तो क्या हुआ, तेरा एहसास हर पल मेरे साथ होता है।</div>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>

  <div class="shayari-card">
    <div class="shayari">तेरा नाम लूं तो होंठ मुस्कुरा देते हैं, जैसे मेरी रूह को सुकून मिल गया हो।</div>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>

  <div class="shayari-card">
    <div class="shayari">तुझसे मिलकर जाना की इश्क़ क्या होता है, वरना हमने तो सिर्फ कहानियों में सुना था।</div>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>

  <div class="shayari-card">
    <div class="shayari">तेरे बिना ये जिंदगी अधूरी सी लगती है, जैसे चाँद बिना रात के।</div>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>

  <!-- Add more cards as needed -->

  <div class="credit">✍️ Writer: 𝓓𝓲𝓷𝓾 𝓜𝓮𝓰𝓱𝔀𝓪𝓷𝓼𝓱𝓲</div>

  <script>
    function likeShayari(button) {
      let countSpan = button.querySelector('.like-count');
      let count = parseInt(countSpan.textContent);
      countSpan.textContent = count + 1;
    }

    function commentShayari() {
      alert("💬 कमेंट फीचर जल्द आ रहा है!");
    }

    function shareShayari() {
      alert("🔗 लिंक कॉपी हो गया (Coming Soon)");
    }
  </script>
</body>
</html>
<!-- Shayari Section Start --><section id="shayari" style="padding: 40px; color: white; font-family: 'Poppins', sans-serif;">
  <h2 style="text-align: center; font-size: 2.5rem; color: #ff00ff; text-shadow: 0 0 10px #ff00ff;">🔥 Motivational Shayari</h2>  <!-- Shayari Cards -->  <div class="shayari-card">
    <p>"जो चलते रहे तूफानों में,<br>वही रौशनी बनते हैं ज़माने में।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"सपनों की उड़ान रखो इतनी ऊँची,<br>कि डर भी सोचे, वापसी की राह नहीं।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"कठिन रास्ते ही असली पहचान बनाते हैं,<br>वरना भीड़ तो हर मोड़ पर होती है।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"जो वक्त की चाल समझ गया,<br>वो खुद को जंजीरों से आज़ाद कर गया।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"सिर्फ सोचना काफी नहीं होता,<br>कुछ करके दिखाना पड़ता है।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"चोट खाकर जो ना रुके,<br>वही असली 'JBR' बनते हैं।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"शोर करने वाले भीड़ में खो जाते हैं,<br>और खामोशी से काम करने वाले इतिहास बनाते हैं।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"मत झुको हालातों के सामने,<br>झुकना है तो अपने उसूलों के लिए झुको।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"अंधेरों से लड़ कर ही उजाले मिलते हैं,<br>डर के आगे नहीं, हिम्मत के साथ चलते हैं।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"हर गिरने वाला हारता नहीं,<br>जो उठ गया वो सबसे बड़ा विजेता है।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"तू अकेला है तो क्या हुआ,<br>आसमान भी तो अकेला ही चमकता है।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"जो ठोकरों से ना डरा,<br>वो हर जंग जीत गया।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"नाम कमाना है तो चुप रह कर मेहनत कर,<br>शोर तो हारने वाले मचाते हैं।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"खुद पर भरोसा रखो,<br>दुनिया तब मानेगी जब तुम खुद को मानोगे।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"मुसीबतें आती हैं, ताकि तू निखर सके,<br>वरना जिंदगी तो सब काट लेते हैं।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"वक्त बदलता जरूर है,<br>बस उस वक्त तक डटे रहना ज़रूरी है।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"जो सोचते रह जाते हैं,<br>वो पीछे रह जाते हैं।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"हर रात के बाद सवेरा ज़रूर होता है,<br>बस अंधेरे में हिम्मत मत हारो।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"तू खुद में एक तूफान है,<br>बशर्ते तू खुद को पहचान ले।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div>  <div class="shayari-card">
    <p>"JBR वो हैं जो थकते नहीं,<br>हर बार उठते हैं और खुद को साबित करते हैं।"</p>
    <div class="shayari-actions">
      <button onclick="likeShayari(this)">❤️ <span class="like-count">0</span></button>
      <button onclick="commentShayari()">💬</button>
      <button onclick="shareShayari()">🔗</button>
    </div>
  </div></section><!-- Shayari Styles --><style>
.shayari-card {
  background: rgba(255, 255, 255, 0.05);
  border: 1px solid #ff00ff;
  border-radius: 15px;
  padding: 20px;
  margin: 25px auto;
  max-width: 600px;
  text-align: center;
  box-shadow: 0 0 15px #ff00ff44;
}

.shayari-card p {
  font-size: 1.2rem;
  line-height: 1.8;
  text-shadow: 0 0 5px #fff;
}

.shayari-actions {
  margin-top: 15px;
  font-size: 1.4rem;
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
</style><!-- Shayari Scripts --><script>
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
<head>
  ...
  <style>
    html, body {
      margin: 0;
      padding: 0;
      min-height: 100vh;
      height: auto;
      overflow-x: hidden;
      background-color: #000; /* या जो भी आपकी background color है */
    }

    section#shayari {
      margin-bottom: 100px; /* नीचे scroll हो सके */
    }
  </style>
</head>
<!-- Existing Shayari JavaScript replace करो -->
<script>
function likeShayari(btn) {
  const card = btn.closest('.shayari-card');
  const id = card.innerText.slice(0, 20); // unique ID from text
  let count = parseInt(localStorage.getItem(id) || "0") + 1;
  localStorage.setItem(id, count);
  btn.querySelector(".like-count").innerText = count;
}

window.onload = function () {
  document.querySelectorAll('.shayari-card').forEach(card => {
    const btn = card.querySelector('button');
    const id = card.innerText.slice(0, 20);
    const count = localStorage.getItem(id) || "0";
    btn.querySelector(".like-count").innerText = count;
  });
}
</script>
<h1>𝓓𝓲𝓷𝓾 𝓜𝓮𝓰𝓱𝔀𝓪𝓷𝓼𝓱𝓲</h1>
