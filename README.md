# portfolio_web
hey there, this is my project under my internship at Bharat Intern. In this project, I have made my own portfolio website.
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio website</title>
    <style>
    *{
    margin: 0;
    padding: 0;
    font-family: sans-serif;
}

.hero{
    position: relative;
    width: 100%;
    height: 100%;
    background: #f9fafb;
}

nav{
    display: flex;
    width: 84%;
    margin: auto;
    padding: 20px 0;
    align-items: center;
    justify-content: space-between;
}

.logo{
    height: 10%;
    width: 10%;
}

nav ul li{
    display: inline-block;
    list-style: none;
    margin: 10px 20px;
}

nav ul li a{
    text-decoration: none;
    color: black;
    font-weight: bold;
}

nav ul li a:hover{
    color: rgb(248, 132, 151);
}

.detail{
    margin: 8%;
    margin-top: 15%;
}

.detail h1{
    font-size: 50px;
    color: #212121;
    margin-bottom: 20px;
}

span{
    color: orangered;
}
.detail p{
    color: #555;
    line-height: 22px; 
}

.detail a{
    background: #212121;
    padding: 10px 18px;
    text-decoration: none;
    font-weight: bold;
    color: #fff;
    display: inline-block;
    margin: 30px 0;
    border-radius: 5px;
}

.images{
    width: 45%;
    height: 80%;
    position: absolute;
    bottom: 0;
    right: 100px;
}

.images img{
    height: 100%;
    position: absolute;
    left: 50%;
    bottom: 0;
    transform: translateX(-50%);
    transition: bottom 2s left 2s;
}

.images:hover .shape{
    bottom: 40px;
    border-radius: 60px;
}

.images:hover .photo{
    left: 45%;
}
</style>
</head>
<body>

    <div class="hero">
        <nav>
            <img src="IshaLogo.png" class="logo">
            <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">ABOUT</a></li>
                <li><a href="#">PORTFOLIO</a></li>
                <li><a href="#">SERVICES</a></li>
                <li><a href="#">HIRE ME</a></li>
            </ul>
        </nav>
        <div class="detail">
            <h1>I'm Isha <span>Khare</span></h1>
            <p>This is my official Portfolio website to show all
                <br> Details and Work Experience in Web Development
            </p>
        <a href="#">DOWNLOAD CV</a>    
        </div>
        <div class="images">
            <img src="pink.png" class="shape">
            <img src="IshaPhoto3-removebg-preview.png" class="photo">
        </div>
    </div>
    
</body>
</html>
