<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Vaishnavi Notes | MHT-CET PCB Notes</title>

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
    background:#f5f5ff;
    color:#172033;
    line-height:1.6;
}

/* HEADER */
header{
    background:white;
    position:sticky;
    top:0;
    z-index:1000;
    box-shadow:0 2px 15px rgba(0,0,0,0.08);
}

.navbar{
    max-width:1100px;
    margin:auto;
    padding:15px 20px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    display:flex;
    align-items:center;
    gap:12px;
    font-size:22px;
    font-weight:bold;
    color:#5338d8;
}

/* CLEAR LOGO */
.logo-icon{
    width:48px;
    height:48px;
    background:linear-gradient(135deg,#684ee8,#4a32c7);
    border-radius:14px;
    display:flex;
    align-items:center;
    justify-content:center;
    color:white;
    font-size:27px;
    font-weight:bold;
    box-shadow:0 5px 15px rgba(83,56,216,0.25);
}

nav a{
    text-decoration:none;
    color:#202638;
    margin-left:22px;
    font-weight:600;
}

nav a:hover{
    color:#5b43d6;
}

/* HERO */
.hero{
    min-height:620px;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:70px 20px;
    background:linear-gradient(135deg,#f1efff,#ffffff);
}

.hero-content{
    max-width:800px;
}

.big-logo{
    width:125px;
    height:125px;
    margin:0 auto 30px;
    background:linear-gradient(135deg,#684ee8,#4930c7);
    border-radius:32px;
    display:flex;
    justify-content:center;
    align-items:center;
    color:white;
    font-size:70px;
    font-weight:bold;
    box-shadow:0 15px 35px rgba(83,56,216,0.25);
}

.hero h1{
    font-size:48px;
    margin-bottom:10px;
}

.hero h1 span{
    color:#5940d4;
}

.hero p{
    font-size:20px;
    color:#667085;
    max-width:650px;
    margin:15px auto 30px;
}

.btn{
    display:inline-block;
    text-decoration:none;
    padding:14px 28px;
    border-radius:30px;
    font-weight:bold;
    margin:7px;
    transition:0.2s;
}

.primary{
    background:#5940d4;
    color:white;
    box-shadow:0 8px 20px rgba(89,64,212,0.25);
}

.secondary{
    background:white;
    color:#5940d4;
    border:2px solid #5940d4;
}

.btn:hover{
    transform:translateY(-2px);
}

/* SECTIONS */
section{
    max-width:1100px;
    margin:auto;
    padding:75px 20px;
}

.section-title{
    text-align:center;
    font-size:34px;
    margin-bottom:12px;
    color:#1d2538;
}

.section-subtitle{
    text-align:center;
    color:#70798b;
    margin-bottom:40px;
}

/* NOTES */
.notes-grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:22px;
}

.card{
    background:white;
    padding:28px;
    border-radius:20px;
    box-shadow:0 8px 25px rgba(30,30,60,0.08);
    text-align:center;
}

.card-icon{
    font-size:42px;
    margin-bottom:12px;
}

.card h3{
    margin-bottom:10px;
}

.card p{
    color:#687184;
    margin-bottom:20px;
}

.view-btn{
    display:inline-block;
    text-decoration:none;
    background:#5940d4;
    color:white;
    padding:11px 22px;
    border-radius:25px;
    font-weight:bold;
}

/* ABOUT */
.about{
    background:white;
    border-radius:25px;
    box-shadow:0 8px 25px rgba(30,30,60,0.06);
    text-align:center;
}

.about p{
    max-width:750px;
    margin:15px auto;
    color:#687184;
    font-size:17px;
}

/* CONTACT */
.contact-box{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:20px;
}

.contact-card{
    background:white;
    padding:28px 15px;
    text-align:center;
    border-radius:20px;
    box-shadow:0 8px 25px rgba(30,30,60,0.08);
}

.contact-card .icon{
    font-size:38px;
    margin-bottom:10px;
}

.contact-card a{
    color:#5940d4;
    text-decoration:none;
    font-weight:bold;
    word-break:break-word;
}

/* FOOTER */
footer{
    background:#17152b;
    color:white;
    text-align:center;
    padding:30px 20px;
}

footer p{
    opacity:0.8;
    margin:5px;
}

/* MOBILE */
@media(max-width:750px){

    .navbar{
        flex-direction:column;
        gap:12px;
    }

    nav a{
        margin:0 7px;
        font-size:14px;
    }

    .hero h1{
        font-size:36px;
    }

    .hero p{
        font-size:17px;
    }

    .notes-grid{
        grid-template-columns:1fr;
    }

    .contact-box{
        grid-template-columns:1fr;
    }

    .big-logo{
        width:105px;
        height:105px;
        font-size:58px;
    }
}
</style>
</head>

<body>

<!-- HEADER -->
<header>
    <div class="navbar">

        <div class="logo">
            <div class="logo-icon">₹</div>
            <div>Vaishnavi<br>Notes</div>
        </div>

        <nav>
            <a href="#home">Home</a>
            <a href="#notes">Notes</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>

    </div>
</header>


<!-- HOME -->
<section class="hero" id="home">

    <div class="hero-content">

        <div class="big-logo">₹</div>

        <h1>
            Welcome to<br>
            <span>Vaishnavi Notes</span>
        </h1>

        <p>
            MHT-CET PCB students ke liye useful,
            easy-to-understand aur exam-focused
            handwritten notes.
        </p>

        <a href="#notes" class="btn primary">
            📚 View Notes
        </a>

        <a href="#contact" class="btn secondary">
            📞 Contact Me
        </a>

    </div>

</section>


<!-- NOTES -->
<section id="notes">

    <h2 class="section-title">📚 My Notes</h2>

    <p class="section-subtitle">
        MHT-CET PCB preparation ke liye notes
    </p>

    <div class="notes-grid">

        <div class="card">
            <div class="card-icon">🧪</div>
            <h3>Chemistry Notes</h3>
            <p>
                Handwritten Chemistry notes
                for MHT-CET PCB preparation.
            </p>

            <a href="#contact" class="view-btn">
                View Notes
            </a>
        </div>


        <div class="card">
            <div class="card-icon">⚡</div>
            <h3>Physics Notes</h3>
            <p>
                Easy-to-understand handwritten
                Physics notes.
            </p>

            <a href="#contact" class="view-btn">
                View Notes
            </a>
        </div>


        <div class="card">
            <div class="card-icon">🧬</div>
            <h3>Biology Notes</h3>
            <p>
                Important Biology notes for
                MHT-CET PCB students.
            </p>

            <a href="#contact" class="view-btn">
                View Notes
            </a>
        </div>

    </div>

</section>


<!-- ABOUT -->
<section id="about">

    <div class="about">

        <h2 class="section-title">
            ✨ About Vaishnavi Notes
        </h2>

        <p>
            Vaishnavi Notes ka aim hai students ko
            simple aur useful study material provide karna.
        </p>

        <p>
            Notes specially MHT-CET PCB preparation
            ko dhyan me rakhkar banaye gaye hain.
        </p>

    </div>

</section>


<!-- CONTACT -->
<section id="contact">

    <h2 class="section-title">📞 Contact Me</h2>

    <p class="section-subtitle">
        Notes ke liye mujhse contact karein
    </p>


    <div class="contact-box">

        <!-- PHONE -->
        <div class="contact-card">

            <div class="icon">📱</div>

            <h3>Phone</h3>

            <a href="tel:+919561261968">
                9561261968
            </a>

        </div>


        <!-- EMAIL -->
        <div class="contact-card">

            <div class="icon">📧</div>

            <h3>Email</h3>

            <a href="mailto:vaishnavisalunke031@gmail.com">
                vaishnavisalunke031@gmail.com
            </a>

        </div>


        <!-- INSTAGRAM -->
        <div class="contact-card">

            <div class="icon">📸</div>

            <h3>Instagram</h3>

            <a
              href="https://instagram.com/Mht_cet_notes_by_vaishnavi"
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
        © 2026 Vaishnavi Notes
    </p>

</footer>

</body>
</html>
