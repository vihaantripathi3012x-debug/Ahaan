<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pelé - King of Football</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f4f4f4;
    color:#222;
}

header{
    background:linear-gradient(to right,#0a7d34,#f7d117);
    color:white;
    text-align:center;
    padding:60px 20px;
}

header h1{
    font-size:4rem;
}

header p{
    font-size:1.2rem;
    margin-top:10px;
}

nav{
    background:#111;
    padding:15px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-weight:bold;
}

section{
    padding:50px 10%;
}

.about{
    display:flex;
    gap:30px;
    flex-wrap:wrap;
    align-items:center;
}

.about img{
    width:350px;
    border-radius:15px;
}

.about-text{
    flex:1;
}

.stats{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:20px;
}

.card{
    background:white;
    padding:25px;
    text-align:center;
    border-radius:12px;
    box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

.card h2{
    color:#0a7d34;
    margin-bottom:10px;
}

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.gallery img{
    width:100%;
    border-radius:10px;
}

footer{
    background:#111;
    color:white;
    text-align:center;
    padding:20px;
}
</style>
</head>

<body>

<header>
    <h1>PELÉ</h1>
    <p>The King of Football</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#records">Records</a>
    <a href="#gallery">Gallery</a>
</nav>

<section id="about">
    <div class="about">
        <img src="pele.jpg" alt="Pelé">
        <div class="about-text">
            <h2>About Pelé</h2>
            <br>
            <p>
                Pelé was a Brazilian football legend widely regarded as one of
                the greatest players in history. He won three FIFA World Cups
                with Brazil and scored more than 1,000 goals during his career.
            </p>
        </div>
    </div>
</section>

<section id="records">
    <h2 style="text-align:center;margin-bottom:30px;">Career Highlights</h2>

    <div class="stats">
        <div class="card">
            <h2>3</h2>
            <p>World Cups</p>
        </div>

        <div class="card">
            <h2>1000+</h2>
            <p>Career Goals</p>
        </div>

        <div class="card">
            <h2>1958</h2>
            <p>Youngest World Cup Winner</p>
        </div>

        <div class="card">
            <h2>Brazil</h2>
            <p>National Team Legend</p>
        </div>
    </div>
</section>

<section id="gallery">
    <h2 style="text-align:center;margin-bottom:30px;">Gallery</h2>

    <div class="gallery">
        <img src="pele1.jpg" alt="Pelé">
        <img src="pele2.jpg" alt="Pelé">
        <img src="pele3.jpg" alt="Pelé">
        <img src="pele4.jpg" alt="Pelé">
    </div>
</section>

<footer>
    <p>Created in tribute to Pelé - The King of Football</p>
</footer>

</body>
</html>
