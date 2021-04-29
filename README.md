# SHAPEAI WEB DEV BOOTCAMP
Hi I made this project during the 7 Days Free Bootcamp, conducted by <b> SHAPEAI
</b>.
The instructor during the session was Mr. Shaurya Sinha (Data Analyst Intern at Jio). I got to
learn a lot during these 7 days and it was an amazing experience learning with SHAPEAI.
<br><br>Here's the link for you to watch the sessions as well<br>
<a href="https://youtube.com/playlist?list=PL7zl8TDRnbun7K0fECtSMCI2hOCgLBy9a"> <img src="https://github.com/ShapeAI/PYTHON-AND-DATA-ANALYTICS/blob/main/WebD%20poster.png"> </a>
<br>I got to have hands on experience on:
<li>HTML
<li>CSS
<br>during these 7 days, and everything was explained from the very basics so that
anyone with zero experience on programming can learn.
I enjoyed these 7 days, you can as well. To register for next free 7 days bootcamp, visit:
www.shapeai.tech
or follow SHAPEAI on:
<li><a href=
"https://in.linkedin.com/company/shapeai">LinkedIn</a>
<li><a href=
"https://www.instagram.com/shape.ai/?hl=en">Instagram</a>
<li><a
href=
"https://www.youtube.com/channel/UCTUvDLTW9meuDXWcbmISPdA">YouTu
be</a>
<li><a href=
"https://github.com/shapeai">GitHub</a>


# Your_SatshilChalke24_RatanTata_Project.github.io
WEB-DEV BOOTCAMP SHAPEAI  SATSHIL CHALKE RATAN TATA PROJECT 
# index_file
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
   
    <title>RATAN_TATA_Portfolio</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <section id="main">
      <nav>
          <a href="https://satshilchalkebootcamphtmlcssproject.satshilchalke.repl.co/" class="logo">
            <img src="Tata_logo.png" alt="LOGO OF TATA PROJECT">
          </a>
          <span class="menu-space">

          </span>
          <ul class="menu">
              <li><a href="https://www.tata.com/">Home</a></li>
              <li><a href="https://economictimes.indiatimes.com/panache/panache-people-101/ratan-tata/profileshow/79611431.cms">Recent</a></li>
              <li><a href="https://www.thestrategywatch.com/leadership-skills-qualities-styles-ratan-tata/">Skills</a></li>
              <li><a href="https://www.tata.com/business/overview">Business</a></li>
              <li><a href="https://www.youtube.com/results?search_query=ratan+tata%27s+most+viewed+video">Learn More</a></li>
          </ul>
          <p>  
          <a href="https://celebcontactdetails.com/ratan-tata/" class="hey"><strong> Say Hi!</strong>
           </a></p>  

      </nav>

    </section>

    <div class="content">
         <div class="image"><a href="https://www.youtube.com/watch?v=DymFOFnTS-g">
           <img src="RATAN_TATA.jpg" alt="RATAN TATA "></a>

         </div>
         <div class="main-text">
           <h1>Hello, I am The Ratan Tata</h1>
           <p>This website is a small gift from one of the admirer of <a href="https://www.ukessays.com/essays/management/theories-of-leadership-in-tata-group-management-essay.php#:~:text=Emotional%20Stability%3A%20Ratan%20Tata%20has,future%20leadership%20of%20TATA%20Group."  class="hey"><strong>The Ratan Tata</strong></a>       showcasing his skills he learned from SHAPE AI, Basic Web Development Bootcamp. A huge shout-out to Shaurya Sinha and Team. </p>
           <a href="https://en.wikipedia.org/wiki/Ratan_Tata" class="resume-btn">Wikipedia of Ratan Tata</a>

         </div>
    </div>
  </body>
</html>
# style_css_file
* {
  box-sizing: border-box;
}
body {
  margin: 0px;
  padding:  opx;
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
  box-shadow: 5px 10px 30px rgba(0, 0, 0, 0.05);
  z-index: 1;

}
.logo img{
  height: 45px;
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
  color: gray;
  }

a{
  text-decoration: none;
}

.hey{
  color:#39bfbd;
  font-weight: 500;
  font-size: 0.9em;
  border-bottom: 2px solid #39bfbd;
  
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
  .content {
    display: flex;
    width: 90%;
    justify-content: space-around;
    align-items: center;
    position: absolute;
    left: 50%;
    right: 50%;
    transform: translate(-50%,-50%)
  }
.main-text {
  width: 500px;
}
.main-text h1 {
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
  box-shadow: 5px 10px 30px rgba(24, 139, 119, 0.2);

}

.resume-btn:hover{
  background-color: #23cdaf;
  transition:all ease 0.2s;
}

.menu li a:hover{
   background-color: #23cdaf;
   transition:all ease 0.2s;
   box-shadow: 5px 10px 30px rgba(24, 139, 119, 0.2);
   color: white;
   }


.image a:hover{
   background-color: #23cdaf;
   transition:all ease 0.2s;
   box-shadow: 5px 10px 30px rgba(24, 139, 119, 0.2);
   color: white;
   }
   .main-text p a{
   padding-left: 10px;
  }
  .main-text p a:hover{
   background-color: #23cdaf;
   transition:all ease 0.2s;
   box-shadow: 5px 10px 30px rgba(24, 139, 119, 0.2);
   color: white;
  }
.hey:hover{
   background-color: #23cdaf;
   transition:all ease 0.2s;
   box-shadow: 5px 10px 30px rgba(24, 139, 119, 0.2);
   color: white;
  }

  
  .logo:hover{
   background-color: #23cdaf;
   transition:all ease 0.2s;
   box-shadow: 5px 10px 30px rgba(24, 139, 119, 0.2);
   color: white;
  }
  
