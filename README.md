<!DOCTYPE html>
<html lang="en">
    <head> 
        <meta charset="UTF-8"> 
        <title>Portfolio Landing Page</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css">
</head>
    <body>
    <div class="hero"> 
        <nav> 
    <img src="student.jpg" />
    
            
            <ul> 
                <li><a href="#">Home</a></li> 
                <li><a href="#">Portfolio</a></li> 
                <li><a href="#">Services</a></li>
                 <li><a href="#">Contact Us</a></li> 
                 <li><a href="#">About Us</a></li> 
                </ul> 
                <a href="#" class="btn">Hire Me</a> 
                <p style="color: #25D366;">CLICK HERE TO CHAT</p>
                <div class="chatbox"><img src="whatsapp.jpg" alt=""</div>
            </nav> 
            <div class="info"> 
                <h1>I am <span> Poulami Mondal</span></h1> 
                <h1>I'm a BCA graduate and <br> now pursuing MCA</h1> 
                <p>I want to work as a front end developer</p>
                <p>Welcome to my officail Portfolio Website Where I put all<br> my work related to my designs and many more.</p> 
                <a href="#" class="btn">Download CV</a> 
            </div> 
    <div class="social"> 
        <a href="#"><i class="fab fa-facebook-square"></i></a>
         <a href="#"><i class="fab fa-dribbble"></i></a> 
         <a href="#"><i class="fab fa-linkedin-in"></i></a> 
        </div> </div>
    </body>
        </html>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap');* 
{ 
    margin: 0;
     padding: 0;
      box-sizing: border-box;
    }
.hero { 
    width: 100%; 
    height: 100vh;
     background: #fff; 
    font-family: 'Poppins', sans-serif; 
    position: relative;
}
nav {
     width: 84%; 
     margin: auto;
      padding: 20px 0; 
      display: flex;
       align-items: center;
        justify-content: space-between;
    }
.logo { 
    width: 150px; 
    cursor: pointer; 
    background: transparent
}
nav ul li { 
    display: inline-block;
     list-style: none; 
     margin: 10px 20px;
    }
nav ul li a { 
    text-decoration: none; 
    color: #606163;
}
nav ul li a:hover { 
    color: #ff4321;
}
.btn { 
    background: #ff4321;
    border-radius: 5px; 
    padding: 10px 18px;
     text-decoration: none; 
     color: #fff; 
     display: inline-block; 
     border: 1px solid transparent;
    }
..btn:hover { 
    background: transparent; 
    color: #ff4321; 
    border: 1px solid #ff4321;
}
.info {
     margin-left: 8%; 
     margin-top: 10%;
    }
.info h1 { 
    font-size: 40px; 
    color: #444242;

}
.info p { 
    color: #606163; 
    line-height: 22px; 
    margin-top: 10px;
     margin-bottom: 30px;}
.img-box { 
    width: 45%;
    height: 80%;
     position: absolute;
      bottom: 0; 
      right: 100px;
    }
.img-box img { 
    height: 100%; 
    position: absolute;
     left: 50%;
      bottom: 0; 
      transform: translateX(-50%);
    }
.img-box:hover .back-img {
     bottom: 40px;
    }
.img-box:hover .man-img {
     left: 54%;
    }
.social {
     margin-left: 8%; 
     margin-top: 25px;
    }
.social a {
     font-size: 28px; 
     color: #606163; 
     margin-right: 20px;
    }
.social a:hover { 
    color: #ff4321;
}
    </html>
    
