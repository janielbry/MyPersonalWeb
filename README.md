<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" media="screen and (max-width:800px)" href="tablet.css">
</head>

<body>
    <nav class="navbar">
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Me</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#contact">Contact Me</a></li>
        </ul>
    </nav>

    <section id="home">
        <div class="main">
            <h1 class="headings">I AM <br> Brynna Janiel Potenciano</h1>

        </div>
    </section>

    <section id="about">
        <h1 class="headings">ABOUT ME</h1>
        <div id="pic">
            <img src="img1.jpg" alt="">
            <div id="intro">
                <h2>Brynna Janiel Potenciano</h2>
                <p>A plate can never be fully restored once it has a crack, but if it is usable,what we have now will suffice.</p>
                <p>I do take my work seriously and the way to do that is not to take yourself seriously.</p>
                <p>Those of you who are not aware of my brilliant career as a stand up comic, </p>
                <p>I'm not aware of it either so we might well wonder what we're doing here.</p>
            </div>
        </div>
    </section>

    <section id="portfolio">
        <h1 class="headings">PORTFOLIO</h1>
        <div class="gallery">
            <img src="Portfolio/img1.jpg" alt="">
            <img src="Portfolio/img2.jpg" alt="">
            <img src="Portfolio/img3.jpg" alt="">
            <img src="Portfolio/img4.jpg" alt="">
            <img src="Portfolio/img5.jpg" alt="">
            <img src="Portfolio/img6.jpg" alt="">
            <img src="Portfolio/img7.jpg" alt="">
            <img src="Portfolio/img8.jpg" alt="">
            <img src="Portfolio/img9.jpg" alt="">
            <img src="Portfolio/img10.jpg" alt="">
            <img src="Portfolio/img11.jpg" alt="">
            <img src="Portfolio/img12.jpg" alt="">
        </div>
    </section>

    <section id="contact">
        <h1 class="headings">CONTACT ME</h1>
        <form action="" class="form">
            <input type="text" name="name" class="input" placeholder="Enter Your Name">
            <input type="email" name="email" class="input" placeholder="Enter Your Email">
            <textarea name="msg" id="msg" cols="30" rows="10" placeholder="Enter Your Email"></textarea>
            <input type="submit" value="SEND" id="send">
        </form>
    </section>
</body>

</html>
