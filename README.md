
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navbar</title>
    <link rel="stylesheet" href="/css/navbar.css">
</head>
    <style>
        body{
    margin-top: 50px;
    padding: 0;
}
.navbar{
    background-color: rgb(255, 0, 98);
    display: flex;
    justify-content: space-between;
    margin-bottom: -10px;
}

.nav-logo{
    margin-left: 20px;
    display: flex;
}
.nav-logo img{
    width: 100px;
    border-radius: 100%;
    height: 100px;
    
}

.nav-list{
    display: flex;

    gap: 50px;
    margin-right: 30px;
    padding-top: 20px;
    list-style: none;
    font-size: 20px;
    margin: 13px;
}
.nav-list a{
    font-family: Arial, Helvetica, sans-serif;
    color: white;
    text-decoration: none;   
    gap: 50px;
    justify-content: space-between;
}

.search{
    background-color: antiquewhite;
    padding: 5px;
     n   
}

.dropdown{
    width: 100px;
    margin-top: 18px;
    position: absolute;
    background-color: rgb(63, 63, 63);
    list-style: none;
    transition: 0.2s;
    transform: scale(0);
    
}

.dropdown1{
    width: 100px;
    margin-top: 18px;
    position: absolute;
    background-color: rgb(121, 81, 81);
    list-style: none;
    transition: 0.2s;
    transform: scale(0);
    
}

.check:hover .dropdown{
    transform: scale(1) !important;
}

.product:hover .dropdown1{
    transform: scale(1) !important;
}

.hover:hover{
color: blue;      
}

.bg-video{
    width: 100%;
    height: 100vh;
    object-fit: cover;
    position: absolute;
    z-index: -1;

}

.brand-intro{
    color: white;

}

.intro-head{
    font-size: 130px;
    margin: 20px;
    line-height: 110px;
    margin-top: 50px;
    font-family: Arial, Helvetica, sans-serif;
}

.intro-head span{
    color: bisque;
}

.intro-btn{
    margin: 20px;
    font-size: 27px;
    border: solid 1px white;
    border-radius: 15px;
    background-color: transparent;
    padding-left: 10px;
    padding-right: 10px;
}

.intro-btn a{
    color: white;
    text-decoration: none;

}

.intro-p{
    font-size: 25px;
    font-family: monospace;
    margin-left: 20px;
}

.intro-btn a:hover{
    color: blue;
}
.intro-btn:active{
    background-color: green;
    
}

.brand-intro img{
    width: 120px;
    height: 120px;
    border-radius: 50%;
    margin-top: 50px;
    margin-left: 1200px;
}

.our-service{
    margin: 0;
    padding-top: 50px;
    width: 100%;
    height: 500px;
    background-color: rgb(47, 44, 44);
}

.our-service div{
    margin-left: 25px;
    font-size: 30px;
    color: white;
    padding-bottom: 25px;
}

.our-service p{
    text-align: center;
    border-radius: 10px;
    width: 200px;
    margin-left: 70px;
    font-size: 30px;
    border: solid 1px white;
}

.our-service a{
    color: white;
    text-decoration: none;
}
.image-bg{
    width: 100%;
}

.image-bg img{
    width: 100%;
    position: absolute;
    height: 600px;
    z-index: -2;
}
.container{
    margin-left: 200px;
    margin-right: 200px;
    padding-top: 70px;
    display: flex;
    justify-content: space-around;
    transition: 0.5s;

}

.vission{
    border: solid 5px;
    border-color: blue yellow red goldenrod;
    padding: 20px;
    background-color: white;
    width: 400px;
    height: 300px;
    font-size: 23px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    transform: skew(-20deg);
    transition: 0.5s;
}

.about{
    border: solid 5px;
    border-color: blue yellow red goldenrod;
    padding: 20px;
    background-color: white;
    width: 400px;
    height: 300px;
    font-size: 23px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    transform: skew(-20deg);
    transition: 0.5s;
}
  

    </style>
        <body>
    <nav class="navbar">
        <div class="nav-logo">
            <img src="icons/maijamaa.jpg" alt="Brand logo">
            <p>DZAYANS BLOBAL</p>
        </div>
            <ul class="nav-list">
                <li>
                    <a href="#">Home</a>
                </li>
                <li class="check">
                    <a href="#">Services</a>
                    <ul class="dropdown">
                        <li>
                            <a href="#">HTML</a>
                        </li>
                        <li>
                            <a href="#">JS</a>
                        </li>
                        <li>
                            <a href="#">PYTHON</a>
                        </li>
                        <li>
                            <a href="#">CSS</a>
                        </li>
                        <li>
                            <a href="#">PHP</a>
                        </li>
                    </ul>
                </li>
                <li class="product">
                    <a href="#">Services</a>
                    <ul class="dropdown1">
                        <li>
                            <a href="#">PC</a>
                        </li>
                        <li>
                            <a href="#">KEYBOARD</a>
                        </li>
                        <li>
                            <a href="#">MOUSE</a>
                        </li>
                        <li>
                            <a href="#">HDD</a>
                        </li>
                        <li>
                            <a href="#">SDD</a>
                        </li>
                    </ul>
                </li>
                <li>
                    <a href="#">Services</a>
                </li>
                <li>
                    <a href="#">Services</a>
                </li>
                <li>
                    <input class="search" type="search" placeholder="search" >
                </li>
            </ul>
        </div>
    </nav>
    
        <div class="brand-intro">
            <video class="bg-video" autoplay loop muted src="/icons/nft.mp4"></video>
            <p class="intro-head"> We Create Award Winning <span>Sites</span> </p>
            <button class="intro-btn"> <a href="HW.html">Book Us Now</a></button>
            <p class="intro-p">
               <strong>DZAYANS Solutions</strong> is a global branding and digital design agency focus on building product, services and ecommerce
            </p>
            <img src="/icons/home.png" alt="">
        </div>
    <section class="our-service">
        <div>
            <li>
                <a href="ourmission.html">Our mission</a>
            </li>
        </div>
        <div>
            We help passionate founders perfect theirs design and development game. <span>let's aim for the top together</span>
        </div>
        <p>
            <a href="TeamAssignment.html">Learn More</a>
        </p>
    </section>

    <div>
        <div class="image-bg">
            <img src="/icons/ass-coffee1.jpg" alt="">
            <div class="container" >
                <div class="vission">
                    empoowering individuals, businses,and communities through innnnovative digital solutions, fostering growth and briding the technology divide. 
                </div>
                <div class="about">
                    Ddcdehkdkj
                </div>
            </div>
            
        </div>
    </div>
    <section class="footer">
        <img src="icons/ass-coffee1.jpg" alt="">
        <div>


            <ul>
                <li>FOLLOW OUR SOCIAL MEDIA HANDLES</li>
                <P>
            <a href=""> Face Book </a> 
            <a href="">Instagram </a>
            <a href=""> X</a>
            <a href=""> Youtube</a>
                </P>
            </ul>
            <div>
                <u>
                    <li>Office Branches</li>
                    <li>
                        <a href="">Makurdi</a>
                    </li>
                    <li>
                        <a href="">Makurdi</a>
                    </li>
                    <li>
                        <a href="">Makurdi</a>
                    </li>
                    <li>
                        <a href="">Makurdi</a>
                    </li>
                    <li>
                        <a href="">Makurdi</a>
                    </li> 
                </u>
            </div>
              
            <u>
                <li>Team Members</li>
                <li>
                    <a href="">Alli</a>
                </li>
                <li>
                    <a href="">Mark</a>
                </li>
                <li>
                    <a href="">Muhammed</a>
                </li>
                <li>
                    <a href="">Yahaya</a>
                </li>
                <li>
                    <a href="">Hauwa</a>
                </li> 
            </u>

        </div>
        <div></div>
        <div></div>

    </section>
    
</body>
</html>
