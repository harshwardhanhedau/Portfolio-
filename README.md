# Portfolio-
<!DOCTYPE html>
<html lang="en">
    
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Harshwardhan - My Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;

        }

        body {
            background-color: rgb(0, 0, 33);
            color: white;
            font-family: 'Poppins', sans-serif;
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 55px;
            background-color: rgb(18, 18, 62);
        }

        nav ul {
            display: flex;
            justify-content: center;
        }

        nav ul li {
            list-style: none;
            margin: 0 23px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            color: rgb(134, 134, 239);
            font-size: 1.02rem;
        }

        main hr {
            border: 0;
            background: #9c97f1;
            height: 1.2px;
            margin: 40px 84px;
        }

        .left {
            font-size: 1.5rem;
        }

        .firstSection {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 130px 0;
        }

        .firstSection>div {
            width: 30%;
        }

        .leftSection {
            font-size: 2.5rem;
            margin: 2px 0;
        }

        .leftSection .button{
            padding: 50px 0;
        }

        .leftSection .btn {
            padding: 10px;
            background: #1e2167;
            color: white;
            border: 3px solid white;
            font-size: 17px;
            cursor: pointer;
        }

        .rightSection img {
            width: 90%;

        }

        .purple {
            color: blueviolet;
        }

        .text-gray {
            color: gray;
        }

        #element {
            color: blueviolet;
        }

        .secondSection {
            max-width: 80vw;
            margin: auto;
            height: 80vh;
        }

        .secondSection h1 {
            font-size: 1.9rem;
        }

        .secondSection .box {
            background: white;
            width: 80vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
        }

        .secondSection .vertical {
            height: 93px;
            width: 1px;
            background-color: white;
            margin: 0 104px;
        }

        .thirdSection h1 {

            margin: 0 50px;

            height: 80vh;
            position: relative;
            top: 23px;
            left: 500px;
            font-family: "Dancing Script", cursive;
            font-weight: bolder;
        }


        .image-top {
            width: 30px;
            position: relative;
            top: -43px;
            left: -14px;
        }

        .vertical-title {
            position: relative;
            top: 75px;
            left: -2px;
        }

        .vertical-desc {
            position: relative;
            top: 86px;
            left: -1px;
            color: gray;
            width: 150px;
            font-size: 9px;
        }

        footer {
            background-color: #0e0e1a;
           

        }

        .footer {
            display: flex;
            padding: 23px 122px;
            justify-content: space-evenly;
        }
        .footer ul{
            list-style: none;
        }

        .footer > div{
            width: 223px;
        }
        footer .footer-rights{
            text-align: center;
            color: gray;
            padding: 12px 0;
        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left"> Harshwardhan's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/">About</a></li>
                    <li><a href="/">Services</a></li>
                    <li><a href="/">Projects</a></li>
                    <li><a href="/">Contact us</a></li>
                </ul>

            </div></a>
        </nav>
    </header>

    <main>
        <section class="firstSection">
            <div class="leftSection">
                Hey, My name is <span class="purple">Harshwardhan Hedau</span>

                <div>and I am a </div>
                <span id="element"></span>
                <div class="buttons">
                    <button class="btn">Download Resume</button>
                    <button class="btn">Visit Github</button>
                   
                </div>
            </div>
            <div class="rightSection">
                <img src="bg2.png" alt="">
            </div>

        </section>
        <hr>
        <section class="secondSection">
            <span class="text-gray">look at my skills</span>
            <h1>S K I L L S</h1>

            <div class="box">
                <div class="vertical">
                    <img class="image-top" src="html1.png" alt="">
                    <div class="vertical-title">
                        Hypertext Markup Language (HTML)
                    </div>
                    <div class="vertical-desc">
                        Transforming ideas into digital realities, I'm an HTML developer sculpting the web's foundation,
                        crafting immersive experiences, and connecting the dots of the online world.
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="css3.png" alt="">
                    <div class="vertical-title">
                        Cascading Style Sheets (CSS)
                    </div>
                    <div class="vertical-desc">
                        Embarking on a journey through pixels and possibilities – I am a beginner CSS developer,
                        crafting beauty one line at a time.
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="js4.png" alt="">
                    <div class="vertical-title">
                        Javascript (JS)
                    </div>
                    <div class="vertical-desc">
                        Diving into the world of code, I'm a beginner JavaScript developer, scripting my way through the
                        digital landscape, one function at a time.
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="java12.png" alt="">
                    <div class="vertical-title">
                        Java
                    </div>
                    <div class="vertical-desc">
                        Embarking on my Java journey, I'm a beginner developer navigating the syntax seas and debugging
                        dilemmas, driven by curiosity and fueled by determination.
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="ve2.png" alt="">
                    <div class="vertical-title">
                        Video Editor
                    </div>
                    <div class="vertical-desc">
                        Crafting stories one frame at a time, I am a video editor weaving magic into moments, shaping
                        narratives, and painting emotions on the canvas of screens.
                    </div>
                </div>
        </section>
        <section class="thirdSection">
            <h1>Many more skills has yet to come...</h1>
    </main>

    <footer>
        <div class="footer">
            <div class="footer-first">
                <h3>Harshwardhan's Developer Portfolio</h3>
            </div>
            <div class="footer-second">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Services</li>
                    <li>Contact</li>
                    
                </ul>
            </div>
        </div>
        <div class="footer-rights">
            Copyright &#169; harshwardhansportfolio.com | All rights reserved
        </div>

    </footer>

    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
            strings: ['Computer Science student', 'Learner', 'Video Editor', 'Tech enthusiast'],
            typeSpeed: 50,
        });
    </script>


</body>

</html>
