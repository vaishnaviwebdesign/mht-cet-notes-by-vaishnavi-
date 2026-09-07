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
    background:#f7f7ff;
    color:#182033;
    line-height:1.6;
}

/* HEADER */

header{
    position:sticky;
    top:0;
    z-index:1000;
    background:white;
    box-shadow:0 3px 15px rgba(0,0,0,0.08);
}

.navbar{
    max-width:1100px;
    margin:auto;
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:15px 20px;
}

.logo-area{
    display:flex;
    align-items:center;
    gap:12px;
}

.logo{
    width:55px;
    height:55px;
    border-radius:14px;
    object-fit:cover;
}

.logo-text{
    font-size:22px;
    font-weight:800;
    color:#222;
}

nav{
    display:flex;
    gap:25px;
}

nav a{
    text-decoration:none;
    color:#202534;
    font-weight:600;
}

nav a:hover{
    color:#5b4bd8;
}

/* HERO */

.hero{
    min-height:650px;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:60px 20px;
    background:linear-gradient(135deg,#f1efff,#ffffff);
}

.hero-content{
    max-width:800px;
}

.hero-logo{
    width:170px;
    height:170px;
    object-fit:cover;
    border-radius:35px;
    margin-bottom:25px;
    box-shadow:0 15px 40px rgba(82,68,200,0.2);
}

.hero h1{
    font-size:48px;
    margin-bottom:10px;
}

.hero h1 span{
    color:#5948d5;
}

.hero p{
    font-size:20px;
    color:#626979;
    margin:20px auto;
    max-width:650px;
}

.buttons{
    display:flex;
    justify-content:center;
    gap:15px;
    flex-wrap:wrap;
    margin-top:30px;
}

.btn{
    display:inline-block;
    padding:14px 25px;
    border-radius:30px;
    text-decoration:none;
    font-weight:bold;
    transition:0.3s;
}

.primary{
    background:#5b49d6;
    color:white;
}

.primary:hover{
    background:#4434b8;
    transform:translateY(-2px);
}

.secondary{
    background:white;
    color:#4d3cc7;
    border:2px solid #5b49d6;
}

.secondary:hover{
    background:#eeeaff;
}

/* SECTION */

section{
    padding:75px 20px;
}

.container{
    max-width:1050px;
    margin:auto;
}

.section-title{
    text-align:center;
    font-size:36px;
    margin-bottom:45px;
}

.section-title span{
    color:#5b49d6;
}

/* NOTES */

.notes-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.note-card{
    background:white;
    padding:30px;
    border-radius:20px;
    text-align:center;
    box-shadow:0 8px 25px rgba(0,0,0,0.08);
    transition:0.3s;
}

.note-card:hover{
    transform:translateY(-6px);
}

.note-icon{
    font-size:45px;
    margin-bottom:15px;
}

.note-card h3{
    font-size:23px;
    margin-bottom:10px;
}

.note-card p{
    color:#687080;
    margin-bottom:20px;
}

.price{
    font-size:25px;
    font-weight:bold;
    color:#5b49d6;
    margin-bottom:15px;
}

.buy-btn{
    display:inline-block;
    background:#5b49d6;
    color:white;
    text-decoration:none;
    padding:12px 22px;
    border-radius:25px;
    font-weight:bold;
}

/* ABOUT */

.about{
    background:white;
}

.about-box{
    max-width:800px;
    margin:auto;
    text-align:center;
}

.about-box p{
    color:#626979;
    font-size:18px;
    margin-bottom:20px;
}

/* CONTACT */

.contact-box{
    max-width:700px;
    margin:auto;
    background:white;
    padding:40px;
    border-radius:25px;
    text-align:center;
    box-shadow:0 8px 30px rgba(0,0,0,0.08);
}

.contact-links{
    display:flex;
    flex-direction:column;
    gap:15px;
    margin-top:25px;
}

.contact-links a{
    display:block;
    padding:15px;
    border-radius:12px;
    background:#f1efff;
    color:#4738bb;
    text-decoration:none;
    font-weight:bold;
}

.contact-links a:hover{
    background:#e4e0ff;
}

/* FOOTER */

footer{
    background:#171827;
    color:white;
    text-align:center;
    padding:30px 20px;
}

footer p{
    color:#c8c9d3;
    margin-top:8px;
}

/* MOBILE */

@media(max-width:700px){

    .navbar{
        flex-direction:column;
        gap:12px;
    }

    nav{
        gap:15px;
        flex-wrap:wrap;
        justify-content:center;
    }

    nav a{
        font-size:14px;
    }

    .hero{
        min-height:600px;
    }

    .hero-logo{
        width:135px;
        height:135px;
    }

    .hero h1{
        font-size:36px;
    }

    .hero p{
        font-size:17px;
    }

    .section-title{
        font-size:30px;
    }

}

</style>
</head>

<body>


<!-- HEADER -->

<header>

<div class="navbar">

<div class="logo-area">

<!-- LOGO -->
<img src="logo.png"
     alt="Vaishnavi Notes Logo"
     class="logo">

<div class="
   
