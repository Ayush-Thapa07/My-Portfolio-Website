# My-Portfolio-Website
I created a portfolio website where I show my technical skills where i have covered HTML, CSS and JavaScript,
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Developer Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;

        }

        body {
            background-color: rgb(2, 2, 75);
            color: rgb(251, 250, 250);
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
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
            color: rgb(161, 161, 232);
            font-size: 1.01rem;
        }

        .main .hr {
            border: 0;
            background: red;
            height: 1.2px;
            margin: 60px 84px;
        }

        .left {
            font-size: 1.5rem;
        }

        .firstSection {
            display: flex;
            justify-content: space-around;
            margin: 80px 0;
            align-items: center;
            margin: 140px 0;
        }

        .firstSection>div {
            width: 30%;
        }

        .leftSection {
            font-size: 2.5rem;


        }

        .rightSection img {
            width: 80%;
            margin: 50px 0;
        }

        .purple {
            color: rgb(120, 45, 189);
        }

        .text-gray {
            color: gray
        }

        #element {
            color: aqua;
        }

        .secondSection {
            max-width: 90vw;
            margin: auto;
            padding: 27px 0;
            color: white;
            text-align: start;
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
            margin: 0 100px;

        }

        .image-top {
            position: relative;
            width: 23px;
            top: 4px;
            left: 5px;
        }



        .vertical-title {
            position: relative;
            top: 75px;
            width: 150px;



        }

        .vertical-desc {
            position: relative;
            top: 86px;
            color: gray;
            width: 150px;
            font-size: 9px;


        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Ayush's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/">About</a></li>
                    <li><a href="/">Services</a></li>
                    <li><a href="/">Projects</a></li>
                    <li><a href="/">Contact Me</a></li>

                </ul>
            </div>
        </nav>
    </header>

    <main>
        <section class="firstSection">
            <div class="leftSection">
                Hi, My name is <span class="purple">Ayush</span>

                <div>and I am a Passionate</div>
                <span id="element"></span>

            </div>
            <div class="rightSection">

                <img src="bg.png.jpg" alt="">
            </div>
        </section>
        <hr>
        <section class="secondSection">
            <span class="text-gray"> What I have done so far</span>
            <h1>Work Experience</h1>

            <div class="secondSection">

                <div class="box">

                    <div class="vertical">
                        <img class="image-top" src="developer.png.png" alt="developer icon">
                        <div class="vertical-title">HTML (2022–2024) </div>
                        <div class="vertical-desc">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis, aperiam odit a quas
                            cupiditate animi totam eligendi provident necessitatibus accusamus corrupti repellat error
                            et, ipsam voluptate

                        </div>
                    </div>

                    <div class="vertical">
                        <img class="image-top" src="developer.png.png" alt="developer icon">
                        <div class="vertical-title"> CSS  (2024–2025)</div>
                        <div class="vertical-desc">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis, aperiam odit a quas
                            totam eligendi provident necessitatibus accusamus corrupti repellat error et, ipsam

                        </div>
                    </div>

                    <div class="vertical">
                        <img class="image-top" src="developer.png.png" alt="developer icon">
                        <div class="vertical-title">JavaScript (2024-2025)</div>
                        <div class="vertical-desc">

                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis, aperiam odit a quas
                            totam eligendi provident necessitatibus accusamus corrupti repellat error et, ipsam


                        </div>
                    </div>

                    <div class="vertical">
                        <img class="image-top" src="developer.png.png" alt="developer icon">
                        <div class="vertical-title"> SQL (2024-25) </div>
                        <div class="vertical-desc">
                            Lorem ipsum dolor sit amet
                            consectetur adipisicing
                            elit. Quis, aperiam odit a
                            quas
                            totam eligendi provident
                            necessitatibus accusamus
                            corrupti repellat error et,
                            ipsam
                        </div>




        </section>
    </main>

    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>

    <script>
        var typed = new Typed('#element', {
            strings: ['Web Developer', 'Graphic Designer', 'Web Designer', 'Video Editor'],
            typeSpeed: 50,
        });
    </script>
</body>

</html>
