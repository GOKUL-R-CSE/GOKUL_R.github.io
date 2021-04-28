<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Rock Resume</title>
    <style>
      *{
        box-sizing: border-box;
      }
      body{
        margin: 0px;
        padding: 0px;
        font: poppins;
      }
      #main{
        width: 100%;
        height: 50vh;
        position: relative;
      }
      nav{
        display: flex;
        justify-content: space-around;
        align-items: center;
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        background-color: white;
        box-shadow: 5px 10px 30px rgba(0,0,0,0.03);
        z-index: 1;
      }
      logo img{
        margin-top: 20;
        
        height: 45px;
        border-image-slice: fill;
      }
      .menu{
        list-style: none;
        display: flex;
      }
      .menu li a{
        height: 40px;
        line-height: 43px;
        margin: 3px;
        padding: 0px 22px;
        display: flex;
        font-size: 0.8em;
        text-transform: uppercase;
        font-weight: 500;
        letter-spacing: 1px;
        color: grey;
      }
      .hey{
        color: #39bfbd;
        font-weight: 500;
        font-size: 0.9em;
        border-bottom: 2px solid #39bfbd;
      }
      a{
        text-decoration: none;
      }
      .image{
        width: 500px;
        height: 500px;
      }
      .image img{
        width: 100%;
        height: 100%;
        object-fit: contain;
      }
      .Content{
        top: 0px;
        margin: 0px;
        display: flex;
        width: 90%;
        justify-content: space-around;
        align-items: center;
        position: absolute;
        left: 50%;
        right: 50%;
        transform: translate(-50%,50%);
      }
      .main-text{
        width: 500px;
      }
      .main-text h1{
        font-size: 3.5em;
        color: #1c3548;
        margin: 0px 0px 10px 0px;
        line-height: 60px;
      }
      .main-text p{
        color: grey;
      }
      .resume-btn{
        width: 190px;
        height: 44px;
        display: flex;
        justify-content: center;
        align-items: center;
        color: white;
        background-color: #1db096;
        border-radius: 20px;
        box-shadow: 5px 10px 30px rgba(24,139,119,0.2);

      }
      .menu li a:hover{
        background-color: #23cdaf;
        color: white;
        box-shadow: 5px 10px 30px rgba(24,139,119,0.2);
        transition: all ease 0.2s;
      }
      .resume-btn:hover{
        background-color: #23cdaf;
        transition: all ease 0.2s;
      }

    </style>
  </head>
  <body>
    <section id="main">
      <nav>
        <a href="" class="logo">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQeX1ehlzdcQqtNGXkSodyCEiis1tkgC-4VYg&usqp=CAU" alt="The Logo of Project Rock">
        </a>
        <span class="menu-space"></span>
        <ul class="menu">
          <li><a href="#">Home</a></li>
          <li><a href="https://skillcrush.com/blog/front-end-developer-skills/">Skills</a></li>
          <li><a href="https://www.coredna.com/blogs/web-development-trends">Recent</a></li>
          <li><a href="https://marketbusinessnews.com/financial-glossary/client-definition-meaning/#:~:text=A%20client%20is%20somebody%20who,a%20relationship%20with%20the%.20seller">Clients</a></li>
          <li><a href="https://nicepage.com/d/89492/contact-our-stylist-web-design">Contacts</a></li>
        </ul>
        <a href="http://www.easyroid.com/index_en.htm" class="hey"><strong> Say Hi! </strong></a>
      </nav>
    </section>
    <section class="Content">
      <div class="image">
        <img src="http://4.bp.blogspot.com/-DbHKjwOHhbc/VMFqkvzTBhI/AAAAAAAAxLo/jn15-xoG0lc/s1600/Dwayne%2BJohnson%2B(The%2BRock)%2BHd%2BFree%2BWallpapers%2B6.png" alt="Rock">
      </div>
      <div class="main-text">
        <h1>Hello, I am The <br> Rock</h1>
        <p>Hey in this Video I will be showing you guys how to build a websit using only HTML and CSS</p>
        <a href="https://en.wikipedia.org/wiki/Dwayne_Johnson" class="resume-btn">See My Resume</a>
      </div>
    </section>
  </body>

</html>
