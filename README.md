#PORTFOLIO

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Taufiq Ahamed | Content Creator & Video Editor</title>

<style>
:root{
  --bg:#ffffff;
  --text:#111;
  --muted:#555;
  --card:#f4f4f4;
  --accent:#0066ff;
}
body.dark{
  --bg:#0e0e0e;
  --text:#f5f5f5;
  --muted:#b5b5b5;
  --card:#1a1a1a;
  --accent:#4da3ff;
}
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:Inter,system-ui,sans-serif;
}
body{
  background:var(--bg);
  color:var(--text);
  line-height:1.7;
  transition:0.3s;
}
section{
  max-width:1100px;
  margin:auto;
  padding:80px 20px;
  opacity:0;
  transform:translateY(30px);
  transition:0.8s ease;
}
section.show{
  opacity:1;
  transform:none;
}
h1,h2{
  letter-spacing:-0.5px;
}
h2{
  margin-bottom:25px;
}
p{
  color:var(--muted);
}
header{
  padding:25px 20px;
  display:flex;
  justify-content:space-between;
  align-items:center;
  max-width:1100px;
  margin:auto;
}
header h1{
  font-size:1.5rem;
}
header button{
  padding:8px 14px;
  cursor:pointer;
  border-radius:6px;
  border:none;
}

/* HERO */
.hero{
  text-align:center;
  padding-top:120px;
}
.hero h2{
  font-size:2.4rem;
  max-width:800px;
  margin:0 auto 20px;
}
.hero p{
  max-width:650px;
  margin:0 auto 30px;
}
.cta a{
  display:inline-block;
  margin:8px;
  padding:14px 26px;
  border-radius:8px;
  text-decoration:none;
  font-weight:600;
}
.cta .primary{
  background:var(--accent);
  color:#fff;
}
.cta .secondary{
  border:2px solid var(--accent);
  color:var(--accent);
}

/* ABOUT */
.about ul{
  margin-top:20px;
}
.about li{
  margin:8px 0;
}

/* SKILLS */
.skills .grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:16px;
}
.grid div{
  background:var(--card);
  padding:18px;
  border-radius:12px;
  font-weight:500;
}

/* WORK */
.work-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
  gap:25px;
}
.card{
  background:var(--card);
  padding:18px;
  border-radius:14px;
}
.work-card img{
  width:100%;
  border-radius:12px;
  transition:0.3s;
}
.work-card img:hover{
  transform:scale(1.04);
  box-shadow:0 15px 40px rgba(0,0,0,0.25);
}

/* CONTACT */
.contact p{
  margin:8px 0;
}

/* FOOTER */
footer{
  text-align:center;
  padding:40px 20px;
  color:var(--muted);
}
</style>
</head>

<body>

<script async src="https://www.instagram.com/embed.js"></script>

<header>
<h1>Taufiq Ahamed</h1>
<button onclick="toggleTheme()">🌙</button>
</header>

<section class="hero">
<h2>Content Creator & Video Editor crafting engaging digital stories</h2>
<p>
I create high-quality long-form and short-form videos for tech and lifestyle brands —
from idea to final edit — with a strong focus on storytelling and audience retention.
</p>
<div class="cta">
<a href="#work" class="primary">View My Work</a>
<a href="#contact" class="secondary">Hire Me</a>
</div>
</section>

<section class="about">
<h2>About Me</h2>
<p>
I’m a content creator and video editor with hands-on experience in YouTube videos,
Instagram Reels, and cinematic storytelling. I handle the complete content workflow
and deliver clean, engaging results consistently.
</p>
<ul>
<li>📍 UAE — Ready to join immediately</li>
<li>🎥 Tech & Lifestyle Content</li>
<li>🛠 DaVinci Resolve • Smartphone & Camera</li>
</ul>
</section>

<section class="skills">
<h2>Core Skills</h2>
<div class="grid">
<div>Video Shooting</div>
<div>Video Editing (DaVinci Resolve)</div>
<div>YouTube Content Strategy</div>
<div>Short-form Content (Reels / Shorts)</div>
<div>Script Writing</div>
<div>Cinematic Storytelling</div>
<div>Thumbnail Creation</div>
<div>Time Management</div>
<div>Attention to Detail</div>
</div>
</section>

<section class="work" id="work">
<h2>Instagram Reels</h2>
<div class="work-grid">
<div class="card">
<blockquote class="instagram-media"
data-instgrm-permalink="https://www.instagram.com/reel/Cs1SRlTOVP-/"
data-instgrm-version="14"></blockquote>
<p>Engaging short-form storytelling.</p>
</div>
<div class="card">
<blockquote class="instagram-media"
data-instgrm-permalink="https://www.instagram.com/reel/DNDyb_oyIGo/"
data-instgrm-version="14"></blockquote>
<p>Retention-focused clean edits.</p>
</div>
<div class="card">
<blockquote class="instagram-media"
data-instgrm-permalink="https://www.instagram.com/reel/DEDEsdUT7Fq/"
data-instgrm-version="14"></blockquote>
<p>Cinematic visual flow.</p>
</div>
</div>
</section>

<section class="work">
<h2>YouTube Videos</h2>
<div class="work-grid">
<div class="work-card card">
<a href="https://youtu.be/dkanYsClfqc" target="_blank">
<img src="https://img.youtube.com/vi/dkanYsClfqc/hqdefault.jpg">
</a>
<p>Real-life tech usage and editing flow.</p>
</div>
<div class="work-card card">
<a href="https://youtu.be/-YFw23W2NyM" target="_blank">
<img src="https://img.youtube.com/vi/-YFw23W2NyM/hqdefault.jpg">
</a>
<p>Structured storytelling and transitions.</p>
</div>
<div class="work-card card">
<a href="https://youtu.be/wCDmDkeJXZI" target="_blank">
<img src="https://img.youtube.com/vi/wCDmDkeJXZI/hqdefault.jpg">
</a>
<p>Cinematic visuals and pacing.</p>
</div>
</div>
</section>

<section class="experience">
<h2>Experience</h2>
<p><strong>Independent Content Creator</strong> — 2023 to Present</p>
<ul>
<li>Planned and executed video concepts</li>
<li>Shooting with smartphones & DIY setups</li>
<li>Editing videos using DaVinci Resolve</li>
<li>Photo editing with Lightroom & Photoshop</li>
<li>Maintained consistency and engagement</li>
</ul>
</section>

<section class="contact" id="contact">
<h2>Contact</h2>
<p>Email: taufiqahamed3344@gmail.com</p>
<p>YouTube: youtube.com/@TaufTech</p>
<p>Instagram: @tauf_tech</p>
</section>

<footer>
© 2026 Taufiq Ahamed
</footer>

<script>
function toggleTheme(){
  document.body.classList.toggle("dark");
}
const sections=document.querySelectorAll("section");
const observer=new IntersectionObserver(entries=>{
  entries.forEach(e=>{ if(e.isIntersecting) e.target.classList.add("show"); });
},{threshold:0.15});
sections.forEach(s=>observer.observe(s));
</script>

</body>
</html>
