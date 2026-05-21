<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Judy Ann Portfolio 🌸</title>

<!-- GOOGLE FONTS -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&family=Pacifico&display=swap" rel="stylesheet">

<!-- FONT AWESOME -->
<link rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css"/>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:'Poppins',sans-serif;
    background:linear-gradient(to bottom,#ffe6f2,#e6f2ff);
    overflow-x:hidden;
    color:#5c4a5d;
}

/* NAVIGATION */

nav{
    position:fixed;
    width:100%;
    top:0;
    left:0;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:15px 8%;
    background:rgba(255,255,255,0.5);
    backdrop-filter:blur(10px);
    z-index:1000;
}

.logo{
    font-family:'Pacifico',cursive;
    font-size:28px;
    color:#ff69b4;
}

nav ul{
    display:flex;
    gap:25px;
    list-style:none;
}

nav ul li a{
    text-decoration:none;
    color:#5c4a5d;
    font-weight:500;
    transition:0.3s;
}

nav ul li a:hover{
    color:#ff69b4;
}

/* HERO */

.hero{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    flex-wrap:wrap;
    padding:120px 10%;
    gap:50px;
    position:relative;
}

.hero img{
    width:320px;
    height:320px;
    object-fit:cover;
    border-radius:50%;
    border:8px solid white;
    box-shadow:0 0 30px rgba(255,105,180,0.4);
    animation:float 4s ease-in-out infinite;
}

@keyframes float{
    0%{transform:translateY(0);}
    50%{transform:translateY(-15px);}
    100%{transform:translateY(0);}
}

.hero-text{
    max-width:550px;
}

.hero-text h1{
    font-size:60px;
    color:#ff69b4;
    font-family:'Pacifico',cursive;
}

.hero-text h2{
    margin:20px 0;
    color:#6b5b6b;
}

.hero-text p{
    line-height:1.9;
}

.btn{
    display:inline-block;
    margin-top:25px;
    padding:12px 25px;
    background:#ff69b4;
    color:white;
    border-radius:30px;
    text-decoration:none;
    transition:0.3s;
}

.btn:hover{
    background:#ff85c1;
    transform:scale(1.05);
}

/* SECTIONS */

section{
    padding:100px 10%;
}

.section-title{
    text-align:center;
    margin-bottom:50px;
}

.section-title h2{
    font-size:42px;
    color:#ff69b4;
    font-family:'Pacifico',cursive;
}

/* CARD */

.card{
    background:white;
    padding:35px;
    border-radius:25px;
    box-shadow:0 10px 25px rgba(0,0,0,0.08);
    line-height:2;
}

/* GRID */

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

/* INTEREST CARDS */

.interest{
    background:white;
    border-radius:25px;
    padding:30px;
    text-align:center;
    transition:0.4s;
    box-shadow:0 10px 25px rgba(0,0,0,0.08);
}

.interest:hover{
    transform:translateY(-10px);
}

.interest i{
    font-size:45px;
    color:#ff69b4;
    margin-bottom:15px;
}

/* GALLERY */

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.gallery img{
    width:100%;
    height:260px;
    object-fit:cover;
    border-radius:20px;
    transition:0.4s;
}

.gallery img:hover{
    transform:scale(1.04);
}

/* CONTACT */

.contact{
    text-align:center;
}

.contact a{
    color:#ff69b4;
    text-decoration:none;
    font-weight:500;
}

.contact a:hover{
    text-decoration:underline;
}

.socials{
    margin-top:20px;
}

.socials a{
    font-size:30px;
    margin:0 12px;
    color:#ff69b4;
    transition:0.3s;
}

.socials a:hover{
    transform:scale(1.2);
}

/* FLOATING HEARTS */

.hearts{
    position:fixed;
    width:100%;
    height:100%;
    top:0;
    left:0;
    pointer-events:none;
    z-index:-1;
}

.heart{
    position:absolute;
    font-size:20px;
    animation:floatUp linear infinite;
}

@keyframes floatUp{
    from{
        transform:translateY(100vh);
        opacity:1;
    }
    to{
        transform:translateY(-10vh);
        opacity:0;
    }
}

/* FOOTER */

footer{
    text-align:center;
    padding:30px;
    color:#777;
}

/* MOBILE */

@media(max-width:768px){

.hero{
    text-align:center;
}

.hero-text h1{
    font-size:45px;
}

nav{
    flex-direction:column;
    gap:15px;
}

}

</style>
</head>

<body>

<!-- FLOATING HEARTS -->
<div class="hearts"></div>

<!-- NAVIGATION -->

<nav>

<div class="logo">Juday 🌸</div>

<ul>
<li><a href="#about">About</a></li>
<li><a href="#education">Education</a></li>
<li><a href="#interests">Interests</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>

<!-- HERO -->

<section class="hero">

<!-- REPLACE WITH YOUR PHOTO -->
<img src="yourphoto.jpg" alt="Profile Picture">

<div class="hero-text">

<h1>Welcome 🌸</h1>

<h2 id="typing"></h2>

<p>
Hi! I am Judy Ann Maranan. I am a college student who loves learning new things,
spending time with family, friends, and especially with my dogs while exploring creative ideas.
My dream is to become successful and inspire others through hard work and kindness.
</p>

<a href="#about" class="btn">Explore More</a>

</div>

</section>

<!-- ABOUT -->

<section id="about">

<div class="section-title">
<h2>About Me</h2>
</div>

<div class="card">

<p><strong>Full Name:</strong> Judy Ann B. Maranan</p>
<p><strong>Nickname:</strong> Juday</p>
<p><strong>Age:</strong> 28 years old</p>
<p><strong>Birthday:</strong> April 09, 1998</p>
<p><strong>Address:</strong> Lot5 Blk6 Carmona St. Corn Agueda VVEV, Cainta Rizal</p>
<p><strong>School:</strong> Lyceum of the Philippines - Manila</p>
<p><strong>Course:</strong> BS Customs Administration</p>

<br>

<p>
🌸 Soft • Funny • Sweet • Introvert • Creative • Calm • Friendly
</p>

</div>

</section>

<!-- EDUCATION -->

<section id="education">

<div class="section-title">
<h2>Educational Background</h2>
</div>

<div class="grid">

<div class="interest">
<i class="fa-solid fa-school"></i>
<h3>Grade School</h3>
<p>
Studied at Urdaneta Elementary School where I learned the importance of education, discipline, and friendship.
</p>
</div>

<div class="interest">
<i class="fa-solid fa-book"></i>
<h3>High School</h3>
<p>
Studied at Bendita National High School where I discovered my strengths and built confidence.
</p>
</div>

<div class="interest">
<i class="fa-solid fa-graduation-cap"></i>
<h3>College</h3>
<p>
Studied BS Accountancy at AMA University Quezon City and currently studying Customs Administration at LPU Manila.
</p>
</div>

</div>

</section>

<!-- ACHIEVEMENTS -->

<section>

<div class="section-title">
<h2>Achievements</h2>
</div>

<div class="card">

<p>🏆 Passed NCIII Bookkeeping in 2018</p>
<p>🏆 Passed the IC3 Assessment</p>

</div>

</section>

<!-- INTERESTS -->

<section id="interests">

<div class="section-title">
<h2>My Interests</h2>
</div>

<div class="grid">

<div class="interest">
<i class="fa-solid fa-mug-hot"></i>
<h3>Coffee Hopping</h3>
<p>
I enjoy exploring different cafés, drinks, and unique cozy ambiances.
</p>
</div>

<div class="interest">
<i class="fa-solid fa-briefcase"></i>
<h3>Business</h3>
<p>
I am passionate about business, entrepreneurship, branding, and customer experience.
</p>
</div>

<div class="interest">
<i class="fa-solid fa-heart"></i>
<h3>Personal Growth</h3>
<p>
I value continuous learning, creativity, and self-improvement.
</p>
</div>

<div class="interest">
<i class="fa-solid fa-paw"></i>
<h3>Snoopy Collection</h3>
<p>
I love collecting Snoopy items because they remind me of childhood memories.
</p>
</div>

</div>

</section>

<!-- HOBBIES -->

<section>

<div class="section-title">
<h2>My Hobbies</h2>
</div>

<div class="card">

<p>🍰 Baking</p>
<p>🏀 Watching PBA Basketball</p>
<p>🐶 Playing with my dogs</p>

</div>

</section>

<!-- FAVORITES -->

<section>

<div class="section-title">
<h2>Favorites</h2>
</div>

<div class="card">

<p><strong>Favorite Food:</strong> Pain Au Chocolat & Spaghetti</p>
<p><strong>Favorite Drink:</strong> Ice Coffee & Matcha Latte</p>
<p><strong>Favorite Color:</strong> Pink</p>

</div>

</section>

<!-- ADVOCACY -->

<section>

<div class="section-title">
<h2>Mental Health Awareness</h2>
</div>

<div class="card">

<p>
Mental health awareness is important because many people silently struggle with stress,
anxiety, and emotional challenges.
</p>

<br>

<p><strong>Issues:</strong> Lack of awareness and emotional support.</p>

<p><strong>Causes:</strong> Stress, pressure, family problems, and social media.</p>

<p><strong>Effects:</strong> Depression, anxiety, and emotional struggles.</p>

<p><strong>Process of Change:</strong> Spread kindness, encourage communication, and support mental health programs.</p>

</div>

</section>

<!-- GALLERY -->

<section id="gallery">

<div class="section-title">
<h2>Gallery</h2>
</div>

<div class="gallery">

<!-- REPLACE THESE WITH YOUR OWN PHOTOS -->

<img src="coffee.jpg">
<img src="friends.jpg">
<img src="dogs.jpg">
<img src="snoopy.jpg">
<img src="floral.jpg">
<img src="selfie.jpg">

</div>

</section>

<!-- CONTACT -->

<section id="contact">

<div class="section-title">
<h2>Contact Me</h2>
</div>

<div class="card contact">

<p>
📧 Email:
<a href="mailto:jmaranan0409@yahoo.com">
jmaranan0409@yahoo.com
</a>
</p>

<p>
📱 Contact Number:
0915 289 6007
</p>

<div class="socials">

<!-- FACEBOOK -->

<a href="https://www.facebook.com/share/1KPvi4ufrd/?mibextid=wwXIfr" target="_blank">

<i class="fab fa-facebook"></i>

</a>

<!-- INSTAGRAM -->

<a href="https://www.instagram.com/nphabmi_09?igsh=MWZhdHU3bGNrNzAxMQ%3D%3D&utm_source=qr" target="_blank">

<i class="fab fa-instagram"></i>

</a>

</div>

<br>

<p>
Thank you for visiting my website 🌸
</p>

</div>

</section>

<!-- FOOTER -->

<footer>
© 2026 Judy Ann Portfolio ✨
</footer>

<script>

/* TYPING EFFECT */

const text = "Coffee Lover ☕ | Dog Lover 🐶 | Floral Soul 🌷";

let i = 0;

function typing(){

    if(i < text.length){

        document.getElementById("typing").innerHTML += text.charAt(i);

        i++;

        setTimeout(typing,80);

    }

}

typing();

/* FLOATING HEARTS */

function createHeart(){

    const heart = document.createElement("div");

    heart.classList.add("heart");

    heart.innerHTML = "💖";

    heart.style.left = Math.random() * 100 + "vw";

    heart.style.animationDuration = Math.random() * 5 + 5 + "s";

    heart.style.fontSize = Math.random() * 20 + 15 + "px";

    document.querySelector(".hearts").appendChild(heart);

    setTimeout(()=>{
        heart.remove();
    },10000);

}

setInterval(createHeart,500);

</script>

</body>
</html>
    
