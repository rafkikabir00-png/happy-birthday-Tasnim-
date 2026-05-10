<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Tasnim ❤️</title>

<style>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: linear-gradient(to bottom, #000000, #1a1a1a);
  color: white;
  scroll-behavior: smooth;
}

/* LOCK SCREEN */
#lock {
  position: fixed;
  width: 100%;
  height: 100vh;
  background: black;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  z-index: 999;
}

button {
  padding: 15px 30px;
  font-size: 18px;
  background: linear-gradient(45deg,#ff4d6d,#ff758f);
  border: none;
  color: white;
  border-radius: 30px;
}

/* SLIDES */
.slide {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  text-align: center;
  padding: 30px;
}

h1,h2 {
  color: #ff4d6d;
}

p {
  max-width: 700px;
  line-height: 1.8;
}

img {
  width: 80%;
  max-width: 300px;
  border-radius: 20px;
  margin: 10px;
  box-shadow: 0 0 20px rgba(255,77,109,0.5);
}

video {
  width: 90%;
  max-width: 400px;
  border-radius: 20px;
}

/* FADE ANIMATION */
.fade {
  opacity: 0;
  transform: translateY(40px);
  transition: 1s;
}

.show {
  opacity: 1;
  transform: translateY(0);
}
</style>
</head>

<body>

<!-- LOCK -->
<div id="lock">
  <h1>💎 Premium Surprise</h1>
  <p>Only For Tasnim ❤️</p>
  <button onclick="start()">Unlock 🎁</button>
</div>

<div id="main" style="display:none;">

<!-- SLIDE 1 -->
<div class="slide fade">
  <h1>🎂 Happy Birthday Tasnim ❤️</h1>
  <p>10 May 💖</p>
</div>

<!-- SLIDE 2 -->
<div class="slide fade">
  <h2>💌 তোমার জন্য</h2>
  <p>
  তাসনিম... 💖  
  তুমি আমার জীবনের সবচেয়ে সুন্দর অনুভূতি।  
  তোমাকে ছাড়া আমার দিনগুলো ফাঁকা লাগে।  
  </p>
</div>

<!-- SLIDE 3 -->
<div class="slide fade">
  <h2>✨ তুমি আমার...</h2>
  <p>
  তুমি আমার শান্তি  
  তুমি আমার স্বপ্ন  
  তুমি আমার পৃথিবী ❤️  
  </p>
</div>

<!-- SLIDE 4 -->
<div class="slide fade">
  <h2>📸 Memories</h2>
  <img src="IMAGE1">
  <img src="IMAGE2">
</div>

<!-- SLIDE 5 -->
<div class="slide fade">
  <h2>📸 More Moments</h2>
  <img src="IMAGE3">
  <img src="IMAGE4">
</div>

<!-- SLIDE 6 -->
<div class="slide fade">
  <h2>🎥 Our Video</h2>
  <video controls>
    <source src="VIDEO1">
  </video>
</div>

<!-- SLIDE 7 -->
<div class="slide fade">
  <h2>💔 Special Memory</h2>
  <video controls>
    <source src="VIDEO2">
  </video>
</div>

<!-- SLIDE 8 -->
<div class="slide fade">
  <h2>❤️ কথা গুলো...</h2>
  <p>
  আমি জানি না ভবিষ্যতে কী হবে,  
  কিন্তু আমি শুধু এটা জানি—  
  আমি তোমাকে অনেক ভালোবাসি 💖  
  </p>
</div>

<!-- SLIDE 9 -->
<div class="slide fade">
  <h2>💫 Promise</h2>
  <p>
  আমি সবসময় তোমার পাশে থাকবো ❤️  
  যতদিন বাঁচবো ততদিন ভালোবাসবো 💖  
  </p>
</div>

<!-- SLIDE 10 -->
<div class="slide fade">
  <h2>🎉 Final</h2>
  <p>
  Happy Birthday My Love 🎂✨  
  I Love You Forever ❤️  
  </p>
</div>

</div>

<script>

// unlock
function start() {
  document.getElementById("lock").style.display="none";
  document.getElementById("main").style.display="block";
}

// fade animation
let slides = document.querySelectorAll(".fade");

window.addEventListener("scroll", () => {
  slides.forEach(slide => {
    let top = slide.getBoundingClientRect().top;
    if(top < window.innerHeight - 100){
      slide.classList.add("show");
    }
  });
});

</script>

</body>
</html>
