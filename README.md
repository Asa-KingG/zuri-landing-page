<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZURI LANDING PAGE</title>
    <link rel="stylesheet" href="stylesheet1.css">
</head>
<body>
    <section class="flex">
    <div class="main">
            <nav>
                <a href="index.html"><img src="https://zuri.team/img/zuri-logo-full.svg" class="logo"></a>
          
            <h1>Learn, Build, Grow.</h1>
            <p>
                Unlock your Brillance with our hands-on beginner and expert training. Zuri Team has been immensely successful in creating a global network of a highly adapt intelligent workforce that can help your company achieve their mission-critical projects and goals.
            </p>

            <div class="nav-links">
                <ul>
                    <li><a href=""><button class="btn1">I'm new to the industry</button></a></li>
                    <li><a href=""><button class="btn2">I need industry experience</button></a></li>
                </ul>
                </div>
                </nav>
            </div>
        </section>



                                      <!------secondpage------>
    <section class="flex2">
        <div class="programs">
<h3>BY ZURI TEAM</h3>
        </div>
    </section>

</body>
</head>
</html>



{
    margin: 0;
    padding: 0;
}
section.flex {
    background-image: url(https://zuri.team/img/hero-bg.svg);
    min-height: 100vh;
    width: 100%;
    margin: auto;
}
    div.main {
        width: 100%;
        height: 100%;
        padding: 10% 10%;
        background-image: url(https://zuri.team/img/hero-bg.svg);
        position: relative;
        background-position: center;
        background-size: cover;
        height:800vh;  
    }
div.nav {
    display: inline-block;
    padding: 2% 6%;
    justify-content: space-between;
    align-items: center;
    text-align: left;
}
img.logo {
    width: 100px;
    align-items: center;
    margin: 300px;
}
h1 {
    font-size: 280%;
    padding-left: 300px;
    margin: auto;
    color: black;
    letter-spacing: 2px;
    align-items: center;
    font-weight: bold;
}
btn:focus {
    outline: 1;
}
p {
    margin: auto;
    display: flex;
    font-size: 100%;
    text-align: center;
    box-sizing: border-box;
    color: rgb(81, 73, 73);
    align-items: center;
    text-decoration: none;
    width: 1000px;
}
nav-links {
    text-align: right;
}
    nav-links ul li {
    list-style: none;
    padding: 8px 12px;
    position: relative;
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
}

ul li a {
    text-decoration: none;
    font-size: 80%;
    display: inline-block;
    margin-left: 300%;
}
li {
    display: flex;
    width: 100px;
}
button.btn1 {
    width: 280%;
    padding: 8px 10px;
    margin: auto;
    background-color: red;
    color: white;
    border-color: red;
    box-sizing: border-box;
    margin-bottom: 10px;
    margin-left: 20px;
    border-radius: 3%;
    cursor: pointer;
    position: relative;
    transition: 0.4s ease;
}
    button.btn1:hover {
        background-color: white;
        border-radius: 3%;
        color: red;
        border-color: red;
    }
button.btn2 {
    width: 230%;
    padding: 8px 10px;
    margin: auto;
    background-color: white;
    color: red;
    border-color: red;
    box-sizing: border-box;
    margin-bottom: 10px;
    margin-left: 20px;
    border-radius: 3%;
    cursor: pointer;
    position: relative;
    transition: 0.4s ease;
}
button.btn2:hover {
    background-color: red;
    border-radius: 3%;
    color: white;
    border-color: red;
}



                             /*------secondpage------*/
div.programs {
    background-color: white;
    background-position: center;
    background-size: cover;
    position: relative;
    width: 100vh;
    height: 100%;
}
h3 {
    font-family: Averta, sans-serif;
    font-size: 280%;
    padding-left: 300px;
    margin-top: 800%;
}
