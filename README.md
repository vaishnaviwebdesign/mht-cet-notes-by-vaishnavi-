<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Vaishnavi Notes | MHT-CET PCB Notes</title>

<meta name="description" content="Vaishnavi Notes - MHT-CET PCB handwritten notes for students.">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:Arial, sans-serif;
    background:#f7f8fc;
    color:#172033;
    line-height:1.6;
}

header{
    background:#ffffff;
    padding:15px 7%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
    z-index:1000;
    box-shadow:0 2px 15px rgba(0,0,0,.08);
}

.logo{
    display:flex;
    align-items:center;
    gap:10px;
    font-weight:800;
    font-size:20px;
    color:#172033;
}

.logo svg{
    width:48px;
    height:48px;
}

nav a{
    text-decoration:none;
    color:#172033;
    margin-left:18px;
    font-weight:600;
}

nav a:hover{
    color:#5b4bdb;
}

.hero{
    padding:65px 7%;
    background:linear-gradient(135deg,#eef0ff,#ffffff);
    text-align:center;
}

.hero .big-logo{
    width:110px;
    height:110px;
    margin:auto;
    margin-bottom:15px;
}

.hero h1{
    font-size:42px;
    margin-bottom:10px;
}

.hero h1 span{
    color:#5b4bdb;
}

.hero p{
    max-width:650px;
    margin:10px auto;
    color:#596174;
    font-size:18px;
}

.badges{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:10px;
    margin:25px 0;
}

.badge{
    background:white;
    padding:8px 15px;
    border-radius:30px;
    box-shadow:0 3px 12px rgba(0,0,0,.08);
    font-weight:600;
}

.btn{
    display:inline-block;
    background:#5b4bdb;
    color:white;
    text-decoration:none;
    padding:13px 25px;
    border-radius:10px;
    font-weight:bold;
    margin:8px;
}

.btn:hover{
    background:#4434bd;
}

.btn.secondary{
    background:white;
    color:#5b4bdb;
    border:2px solid #5b4bdb;
}

section{
    padding:55px 7%;
}

.section-title{
    text-align:center;
    font-size:30px;
    margin-bottom:30px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.card{
    background:white;
    padding:25px;
    border-radius:16px;
    box-shadow:0 5px 20px rgba(0,0,0,.07);
    text-align:center;
}

.card .icon{
    font-size:40px;
    margin-bottom:10px;
}

.card h3{
    margin-bottom:8px;
}

.about{
    background:white;
}

.score-box{
    max-width:700px;
    margin:auto;
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:15px;
}

.score{
    background:#f5f3ff;
    padding:22px 10px;
    text-align:center;
    border-radius:15px;
}

.score strong{
    display:block;
    font-size:28px;
    color:#5b4bdb;
}

.notes-card{
    max-width:750px;
    margin:auto;
}

.notes-card ul{
    list-style:none;
    text-align:left;
    margin:20px 0;
}

.notes-card li{
    background:#f7f8fc;
    padding:12px;
    margin:8px 0;
    border-radius:8px;
}

.price{
    font-size:32px;
    color:#5b4bdb;
    font-weight:bold;
    margin:15px;
}

.contact{
    background:linear-gradient(135deg,#5b4bdb,#7768e8);
    color:white;
    text-align:center;
}

.contact p{
    margin:10px auto;
    max-width:600px;
}

.contact .btn{
    background:white;
    color:#5b4bdb;
}

footer{
    background:#151927;
    color:#cbd0dc;
    text-align:center;
    padding:25px 10px;
}

footer strong{
    color:white;
}

.small{
    font-size:14px;
    opacity:.8;
    margin-top:8px;
}

@media(max-width:700px){

    header{
        padding:12px 4%;
    }

    .logo{
        font-size:17px;
    }

    .logo svg{
        width:40px;
        height:40px;
    }

    nav a{
        margin-left:8px;
        font-size:13px;
    }

    .hero{
        padding:45px 5%;
    }

    .hero h1{
        font-size:32px;
    }

    section{
        padding:45px 5%;
    }

    .score-box{
        grid-template-columns:1fr;
    }
}
</style>
</head>

<body>

<header>

<div class="logo">

<!-- CLEAR SVG LOGO -->
<svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
    <rect x="5" y="5" width="90" height="90" rx="22" fill="#5b4bdb"/>
    <path d="M25 25h35c8 0 15 7 15 15v35H40c-8 0-15-7-15-15V25z"
          fill="white"/>
    <path d="M40 25v35c0 8 7 15 15 15h20"
          fill="none"
          stroke="#5b4bdb"
          stroke-width="5"/>
    <line x1="35" y1="40" x2="60" y2="40"
          stroke="#5b4bdb" stroke-width="4"/>
    <line x1="35" y1="50" x2="60" y2="50"
          stroke="#5b4bdb" stroke-width="4"/>
</svg>

<span>Vaishnavi Notes</span>

</div>

<nav>
<a href="#home">Home</a>
<a href="#notes">Notes</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>

</header>


<!-- HERO -->

<section class="hero" id="home">

<svg class="big-logo" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">

<rect x="5" y="5" width="90" height="90" rx="22" fill="#5b4bdb"/>

<path d="M25 25h35c8 0 15 7 15 15v35H40c-8 0-15-7-15-15V25z"
      fill="white"/>

<path d="M40 25v35c0 8 7 15 15 15h20"
      fill="none"
      stroke="#5b4bdb"
      stroke-width="5"/>

<line x1="35" y1="40" x2="60" y2="40"
      stroke="#5b4bdb" stroke-width="4"/>

<line x1="35" y1="50" x2="60" y2="50"
      stroke="#5b4bdb" stroke-width="4"/>

</svg>

<h1>Welcome to <span>Vaishnavi Notes</span></h1>

<p>
MHT-CET PCB students ke liye useful,
easy-to-understand aur exam-focused notes.
</p>

<div class="badges">
<div class="badge">📚 Handwritten Notes</div>
<div class="badge">🎯 MHT-CET PCB</div>
<div class="badge">📝 Exam Focused</div>
</div>

<a href="#notes" class="btn">View Notes</a>
<a href="#contact" class="btn secondary">Contact Me</a>

</section>


<!-- WHY NOTES -->

<section>

<h2 class="section-title">Why Vaishnavi Notes?</h2>

<div class="cards">

<div class="card">
<div class="icon">📖</div>
<h3>Easy to Understand</h3>
<p>Simple language aur clear explanation ke saath notes.</p>
</div>

<div class="card">
<div class="icon">🎯</div>
<h3>Exam Focused</h3>
<p>Important concepts aur revision ke liye useful material.</p>
</div>

<div class="card">
<div class="icon">✍️</div>
<h3>Handwritten</h3>
<p>Personally prepared handwritten study notes.</p>
</div>

<div class="card">
<div class="icon">📱</div>
<h3>Digital Access</h3>
<p>Notes ko phone par easily access kar sakte ho.</p>
</div>

</div>

</section>


<!-- NOTES -->

<section id="notes" class="about">

<h2 class="section-title">Available Notes</h2>

<div class="card notes-card">

<h3>🧪 Chemistry Notes</h3>

<ul>
<li>✅ Important concepts</li>
<li>✅ Formula & reactions</li>
<li>✅ Quick revision material</li>
<li>✅ MHT-CET focused preparation</li>
</ul>

<div class="price">₹99</div>

<!-- APNA COSMOFEED LINK YAHAN DALO -->
<a href="YOUR_COSMOFEED_LINK_HERE"
   class="btn"
   target="_blank">
   Buy Chemistry Notes
</a>

<p class="small">
Payment ke baad notes access details milengi.
</p>

</div>

</section>


<!-- SCORE -->

<section id="about">

<h2 class="section-title">About Vaishnavi Notes</h2>

<p style="text-align:center;max-width:700px;margin:0 auto 30px;">
These notes are prepared for students who want simple,
organized and exam-oriented study material.
</p>

<div class="score-box">

<div class="score">
<strong>84.08</strong>
MHT-CET PCB Percentile
</div>

<div class="score">
<strong>93.69</strong>
Chemistry Percentile
</div>

<div class="score">
<strong>86.54</strong>
Physics Percentile
</div>

</div>

</section>


<!-- CONTACT -->

<section class="contact" id="contact">

<h2 class="section-title">Want Notes? 📚</h2>

<p>
For notes, questions or updates, contact me through Instagram.
</p>

<!-- APNA INSTAGRAM LINK YAHAN DALO -->

<a href="YOUR_INSTAGRAM_LINK_HERE"
   target="_blank"
   class="btn">
   📸 Instagram
</a>

</section>


<footer>

<p>
<strong>Vaishnavi Notes</strong>
</p>

<p class="small">
MHT-CET PCB Study Notes • Made for Students
</p>

<p class="small">
© 2026 Vaishnavi Notes. All Rights Reserved.
</p>

</footer>

</body>
</html>
