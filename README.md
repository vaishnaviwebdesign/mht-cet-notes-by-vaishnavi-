<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Vaishnavi Notes | MHT-CET PCB</title>

<meta name="description"
content="Vaishnavi Notes - MHT-CET PCB handwritten notes for students.">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:Arial, sans-serif;
    background:#f5f6ff;
    color:#182033;
}

header{
    background:white;
    padding:15px 7%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
    z-index:1000;
    box-shadow:0 2px 15px rgba(0,0,0,0.08);
}

.logo{
    display:flex;
    align-items:center;
    gap:12px;
    font-size:24px;
    font-weight:bold;
}

.logo-icon{
    width:48px;
    height:48px;
    border-radius:12px;
    background:linear-gradient(135deg,#6547e5,#4932c7);
    display:flex;
    align-items:center;
    justify-content:center;
    color:white;
    font-size:25px;
}

nav{
    display:flex;
    gap:25px;
}

nav a{
    text-decoration:none;
    color:#182033;
    font-weight:600;
}

nav a:hover{
    color:#5b43d6;
}

section{
    padding:70px 7%;
}

.hero{
    min-height:90vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    background:linear-gradient(135deg,#f4f2ff,#ffffff);
}

.hero-content{
    max-width:750px;
}

.hero-logo{
    width:150px;
    height:150px;
    margin:0 auto 25px;
    border-radius:35px;
    background:linear-gradient(135deg,#6547e5,#4932c7);
    display:flex;
    align-items:center;
    justify-content:center;
    color:white;
    font-size:70px;
    box-shadow:0 15px 35px rgba(82,61,210,.25);
}

h1{
    font-size:48px;
    margin-bottom:15px;
}

.highlight{
    color:#5b43d6;
}

.hero p{
    font-size:20px;
    color:#687083;
    line-height:1.7;
}

.btn{
    display:inline-block;
    margin-top:30px;
    padding:15px 28px;
    background:#5b43d6;
    color:white;
    text-decoration:none;
    border-radius:30px;
    font-weight:bold;
    box-shadow:0 8px 20px rgba(91,67,214,.25);
}

.btn:hover{
    background:#4932c7;
    transform:translateY(-2px);
}

.cards{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:25px;
    margin-top:35px;
}

.card{
    background:white;
    padding:30px;
    border-radius:20px;
    box-shadow:0 5px 20px rgba(0,0,0,.07);
    text-align:center;
}

.card h3{
    margin:15px 0;
    font-size:22px;
}

.card p{
    color:#687083;
    line-height:1.6;
}

.notes-box{
    max-width:900px;
    margin:auto;
}

.note{
    background:white;
    padding:22px;
    margin:15px 0;
    border-radius:15px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    gap:15px;
    box-shadow:0 4px 15px rgba(0,0,0,.06);
}

.note h3{
    margin-bottom:6px;
}

.note p{
    color:#687083;
}

.small-btn{
    background:#5b43d6;
    color:white;
    text-decoration:none;
    padding:10px 18px;
    border-radius:20px;
    white-space:nowrap;
}

.payment{
    text-align:center;
    background:white;
}

.qr{
    width:280px;
    max-width:90%;
    margin:25px auto;
    padding:12px;
    background:white;
    border-radius:20px;
    box-shadow:0 5px 25px rgba(0,0,0,.12);
}

.qr img{
    width:100%;
    display:block;
    border-radius:10px;
}

.payment p{
    color:#687083;
    margin:10px;
}

.contact{
    text-align:center;
}

.contact-box{
    max-width:650px;
    margin:30px auto;
    background:white;
    padding:35px;
    border-radius:22px;
    box-shadow:0 5px 20px rgba(0,0,0,.07);
}

.contact-item{
    margin:18px 0;
    font-size:18px;
}

.contact-item a{
    color:#5b43d6;
    text-decoration:none;
    font-weight:bold;
}

footer{
    background:#171827;
    color:white;
    text-align:center;
    padding:30px 15px;
}

footer p{
    margin:8px;
    color:#c8c9d4;
}

@media(max-width:700px){

    header{
        padding:12px 5%;
    }

    .logo{
        font-size:19px;
    }

    .logo-icon{
        width:40px;
        height:40px;
        font-size:20px;
    }

    nav{
        gap:10px;
    }

    nav a{
        font-size:13px;
    }

    section{
        padding:55px 5%;
    }

    h1{
        font-size:38px;
    }

    .hero p{
        font-size:17px;
    }

    .cards{
        grid-template-columns:1fr;
    }

    .note{
        flex-direction:column;
        text-align:center;
    }

    .hero-logo{
        width:120px;
        height:120px;
        font-size:55px;
    }
}
</style>
</head>

<body>

<!-- HEADER -->
<header>

<div class="logo">
    <div class="logo-icon">₦</div>
    <span>Vaishnavi Notes</span>
</div>

<nav>
    <a href="#home">Home</a>
    <a href="#notes">Notes</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

</header>


<!-- HOME -->
<section class="hero" id="home">

<div class="hero-content">

<div class="hero-logo">₦</div>

<h1>
Welcome to <span class="highlight">Vaishnavi Notes</span>
</h1>

<p>
MHT-CET PCB students ke liye useful,
easy-to-understand aur exam-focused
handwritten notes.
</p>

<a href="#notes" class="btn">
📚 View Notes
</a>

</div>

</section>


<!-- ABOUT -->
<section id="about">

<h2 style="text-align:center;font-size:35px;">
Why Vaishnavi Notes?
</h2>

<div class="cards">

<div class="card">
<div style="font-size:40px;">📚</div>
<h3>Handwritten Notes</h3>
<p>
Simple aur easy-to-understand handwritten notes.
</p>
</div>

<div class="card">
<div style="font-size:40px;">🎯</div>
<h3>MHT-CET PCB</h3>
<p>
MHT-CET PCB preparation ke liye exam-focused material.
</p>
</div>

<div class="card">
<div style="font-size:40px;">📝</div>
<h3>Student Friendly</h3>
<p>
Important concepts ko simple way me cover kiya gaya hai.
</p>
</div>

</div>

</section>


<!-- NOTES -->
<section id="notes">

<div class="notes-box">

<h2 style="text-align:center;font-size:35px;">
📚 Available Notes
</h2>

<p style="text-align:center;color:#687083;margin:15px;">
Apne required notes select karein.
</p>


<div class="note">

<div>
<h3>🧪 Chemistry Notes</h3>
<p>MHT-CET PCB Chemistry handwritten notes</p>
</div>

<a href="#" class="small-btn">
View Notes
</a>

</div>


<div class="note">

<div>
<h3>⚡ Physics Notes</h3>
<p>MHT-CET PCB Physics handwritten notes</p>
</div>

<a href="#" class="small-btn">
View Notes
</a>

</div>


<div class="note">

<div>
<h3>🧬 Biology Notes</h3>
<p>MHT-CET PCB Biology handwritten notes</p>
</div>

<a href="#" class="small-btn">
View Notes
</a>

</div>

</div>

</section>


<!-- PAYMENT -->
<section class="payment" id="payment">

<h2 style="font-size:35px;">
💳 Pay for Notes
</h2>

<p>
Notes purchase karne ke liye QR code scan karein.
</p>

<div class="qr">

<img src="payment-qr.png"
alt="Vaishnavi Notes Payment QR Code">

</div>

<p>
📱 Scan & Pay using PhonePe / UPI
</p>

<p>
Payment ke baad screenshot bhejkar
notes receive karein.
</p>

<a href="tel:9561261968" class="btn">
📞 Contact After Payment
</a>

</section>


<!-- CONTACT -->
<section class="contact" id="contact">

<h2 style="font-size:35px;">
📩 Contact Me
</h2>

<div class="contact-box">

<div class="contact-item">
📞 Phone:
<br>
<a href="tel:9561261968">
9561261968
</a>
</div>


<div class="contact-item">
📧 Email:
<br>
<a href="mailto:vaishnavisalunke031@gmail.com">
vaishnavisalunke031@gmail.com
</a>
</div>


<div class="contact-item">
📸 Instagram:
<br>
<a href="https://instagram.com/Mht_cet_notes_by_vaishnavi"
target="_blank">
@Mht_cet_notes_by_vaishnavi
</a>
</div>

</div>

</section>


<!-- FOOTER -->
<footer>

<h3>Vaishnavi Notes</h3>

<p>
MHT-CET PCB Handwritten Notes
</p>

<p>
© 2026 Vaishnavi Notes. All Rights Reserved.
</p>

</footer>

</body>
</html>
