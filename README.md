<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Abhinu Creations</title>

<style>
body{
    margin:0;
    font-family:Arial;
    background:#f5f5f5;
}

header{
    background:linear-gradient(90deg,#ffd700,#1faa00);
    color:white;
    text-align:center;
    padding:30px;
}

header h1{
    margin:0;
    font-size:40px;
}

header p{
    font-size:18px;
}

.gallery{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:20px;
    padding:20px;
}

.gallery img{
    width:300px;
    border-radius:15px;
    box-shadow:0 4px 10px rgba(0,0,0,0.3);
}

.contact{
    text-align:center;
    padding:30px;
}

.btn{
    background:#1faa00;
    color:white;
    padding:15px 25px;
    text-decoration:none;
    border-radius:10px;
    font-size:18px;
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:15px;
}
</style>
</head>

<body>

<header>
    <h1>Abhinu Creations</h1>
    <p>Photography | Editing | Graphic Design</p>
</header>

<section class="gallery">
    <img src="poster1.jpg">
    <img src="poster2.jpg">
    <img src="poster3.jpg">
</section>

<section class="contact">
    <h2>Contact Us</h2>
    <p>0751158089</p>

    <a class="btn" href="https://wa.me/94751158089">
        Chat on WhatsApp
    </a>
</section>

<footer>
    © 2026 Abhinu Creations
</footer>

</body>
</html>
