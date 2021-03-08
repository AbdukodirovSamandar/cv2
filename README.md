<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Abdukodirov Samandar</title>
    <link rel="icon" href="favicon.ico">
  <link rel="stylesheet" href="style.css">
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@300&family=Montserrat:wght@200&family=Sacramento&display=swap" rel="stylesheet">
 </head>
  <body>
    <div class="top-container">
      <img class="top-cloud" src="images/cloud.png" alt="cloud-img">
      <h1>I'm Samandar</h1>
      <p class="meh">a <span class="pro">pro</span>grammer.</p>
      <img class="bottom-cloud" src="images/cloud.png" alt="cloud-img">
     <img  src="images/mountain.png" alt="mountain-img">

    </div>
    <div class="middle-container">
      <div class="profile">
        <img src="images/sam1.png" width="200px" alt="profile-img">
        <h2 class="hey">Hello.</h2>
        <p><em>Founder and CEO of <strong>Apple Kugay Company</strong></em></p>
         <p>I'm going to be a student at <a  class="colum" href="https://www.colum.edu/"> Columbia College Chicago.</a>I🖤 coffee and cooking pizzas</p>
      </div>
      <hr>
      <div class="skills">
        <h2>My Skills.</h2>
        <div class="skill-row">
          <img class="Web" src="images/circle-cropped (2).png" alt="conputer-img">
          <h3>Programming</h3>
          <p>I started learning to code back in 2020 and have been practicing for over 3 months now. I know both basic and intermediate HTML and CSS. I believe that I can create awesome websites and web applications</p>
        </div>
        <div class="skill-row">
          <img class="eating" src="images/chillies.png" alt="chilly.png">
          <h3>Eating chillies</h3>
          <p>However, my  best skills is eating chillies. I always eat them along with any meal for lunch and dinner.</p>
        </div>
      </div>
      <hr>
      <div class="contact-me">
        <h2>Get In Touch</h2>
        <h3>Always Welcome</h3>
        <p>If you have any questions regarding my past academic work or just anything, feel free to contact me.</p>
        <a class="btn" href="https://www.abdukodirovsamandar3@gmail.com/">CONTACT ME</a>
      </div>
    </div>


    <div class="bottom-container">
      <a class="Reddit" href="https://www.Reddit.com/u/Free_Banana_9990/" target="_blank">Reddit</a>
      <a class="Instagram" href="https://Instagram.com/samandaar.a/" target="_blank">Instagram</a>
      <a class="footer-link" href="https://Telegram.org/@optimistic_21/"target="_blank">Telegram</a>
      <p>© 2021 Abdukodirov Samandar</p>
    </div>


  </body>
</html>
 131  style.css 
@@ -0,0 +1,131 @@
 body{
  color: #40514E;
  margin: 0;
  font-family:'Merriweather', sans-serif;
  text-align:center;
}

h1{
  font-family:'Sacramento', cursive;
  color: #66BFBF;
  font-size: 90px;
  margin-top:0;
}
.hey {
  padding-bottom: 10px;

}
h2 {
  font-weight: normal;
  color: #66BFBF;
  font-size:2.5rem;
}
h3 {
  color:#66BFBF;
}
p {
  line-height: 2;
}
.top-container {
  background-color: #e4fbff;
}
hr {
  border:dotted #EAF6 6px;
  border-bottom: none;
  width: 4%;
  margin:100px auto;

}

.eating {
  position: relative;
  right: 300px;
  width: 20%;
}
.Web {
  position: relative;
  left: 400px;
  width: 20%;
}
.middle-container{
margin: 100px;
}

.bottom-container{
background-color: #66BFBF;
padding:50px 0 20px;
}

.pro{
  text-decoration: underline;
}
.meh {
  font-family: 'Montserrat', sans-serif;
  font-size: 32px;
}
.intro {
  margin: auto;
  width: 30%;
}
.top-cloud {
  position:relative;
  left:440px;
}
.bottom-cloud{
  position: relative;
  right: 300px;
}
.web {
  font:'Catamaran';
}
a {
color:#11999E;
font-family:  'Merriweather', serif;
margin: 10px 20px;
text-decoration: none;
}
a:hover {
  color: #EAF6F6;
}
.contact-me {
  text-align: center;
  width: 40%;
  margin: 40px auto 60px;
}
.copyright {
  color: #EAF6F6;
  font-size: 0.75rem;
  padding: 20px 0:
}
.btn {
  background: #11CDD4;
  background-image: -webkit-linear-gradient(top, #11CDD4, #11999E);
  background-image: -moz-linear-gradient(top, #11CDD4, #11999E);
  background-image: -ms-linear-gradient(top, #11CDD4, #11999E);
  background-image: -o-linear-gradient(top, #11CDD4, #11999E);
  background-image: linear-gradient(to bottom, #11CDD4, #11999E);
  -webkit-border-radius: 8;
  -moz-border-radius: 8;
  border-radius: 8px;
  font-family:'Merriweather', serif;
  color: #ffffff;
  font-size: 20px;
  padding: 10px 20px 10px 20px;
  text-decoration: none;
}
.colum {
  margin: 0;
}
.colum {
  hover
}

.btn:hover {
  background: #30E3CB;
  background-image: -webkit-linear-gradient(top, #30E3CB, #2BC4AD);
