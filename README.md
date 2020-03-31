# MY-PROJECT
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zimkhitha Mbedla's Porfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
   <div class="profile-img">
    <img src="images/profilepicture.jpg">
   </div> 

   <div class="profile-info">
       <h1>Zimkhitha Mbedla</h1>
       <p class="about">I Am an efficient, organized and approachable person who is always willing to help.<br>Possessing fast learning ability and having technological background through matric classess.</p>

    <div class="social-media">
         <a href="https://www.facebook.com"> <img src="images/facebook.jpg"></a>
         <a href="https://www.instagram.com"><img src="images/instagram.png"></a>
         <a href="https://www.twitter.com"> <img src="images/twitter.png"></a>
          <a href="https://www.linkedin.com"><img src="images/linkedin.png"></a> 
    </div>

        <h2 style="color: lightcoral"><i>About Me</i></h2>
    
    <div class="about-me">
            <p><b>My PASSIONN & DESIRE</b></p>
              <small><b>Techonogy</b> is my <b>passion</b> and<br>
                     i enjoy nothing more than the trends that <b>Techonogy</b><br>
                     is taking in order to work more efficiently and see progress and success.<br>
                     I <b>love Techonogy</b>because i believe in progress,<br>
                    it improve lives and help others.</small>  
              
    </div>

    <div class="about-me">
                    <p style="text-align: right;"><b>MY SKILLS...............</b></p>
                      <small> Time management<br>
                              Trustworthy and<br>
                              able to work in confidential environment<br>
                              Listening and communication skill<br>
                              Having a fast typing skill also HTML, CSS and JavaScript</small>  


     </div>
        <h2 style="color: lightcoral"><i>My Project Work</i></h2>
    <div class="projects">
                <img src="images/mywork.png">
                <img src="images/mywork5.jpg">
                <img src="images/mywork4.jpg">
    </div>

<div class="form-box">
    <h2 style="color: lightcoral;">Contact Me</h2>
    <form method="POST" name="myemailform" action="mailto:zimkhitha.mbedla@younglings.africa" enctype="multipart/form-data">
     <div class="input-group">
     <input type="text" placeholder="First Name"><br>

     <input type="text" placeholder="Last Name">    
</div>   

<div class="input-group">
        <input type="text" placeholder="Phone Number"><br>

        <input type="email" placeholder="Email">    
</div>
<div class="textarea">
            <textarea rows="4" placeholder="Your Message"></textarea>
</div>
        <button type="submit" onclick="https://accounts.google.com/b/0/AddMailService" class="submit-btn">Send Message</button>
    </form>
</div>
<hr>
<div class="contact">
   <span><img src="images/phone.jpg">0717244304</span><br><br>
    <span><img src="images/googleplus.jpg">zimkhitha.mbedla@younglings.africa</span>
</div>

<p class="copyright">Designed by Zimkhitha Mbedla</p>
   </div>

</body>
</html>

*{
    margin: 0;
    padding: o;
    box-sizing: border-box;
}

body{
    background-color: #efefef;
    font-family: sans-serif;
}

.profile-img{
    width: 40%;
    float: right;
}

.profile-img img{
    width: 100%;
    height: 100%;
}

.about{
    margin-left: 15px;
}

.profile-info{
    width: 60%;
    height: 100vh;
    float: left;
    padding: 0 30px;
    overflow: scroll;
    overflow-x: hidden;
}

.profile-info h1{
margin-top: 50px;
margin-bottom: 30px;
color: turquoise;
font-family: 'Times New Roman', Times, serif;
}

.social-media img{
height: 30px;
margin-right: 15px;
}

.social-media{
    margin-top: 20px;
    margin-left: 15px;
    word-spacing: 60px;

}

a:hover{
    background-color: teal;
    width: 30%;
}

.profile-info h2{
   margin-top: 50px;
   margin-bottom: 15px; 
   font-size: xx-large;
}

.expertise img{
    height: 50px;
    margin: 5px;
}

.about-me{
    display: flex;
    width: 70%;
    padding: 40px 40px;
    margin: 2%;
    text-align: left;
    box-shadow: 0 3 15px  rgba(37, 73, 21, 214, 0.18);
    background-color: rgb(207, 230, 231);
}

.about small{
    padding-top: 10px;
    display: block;
    padding-left: 20px;
    padding-right: 0%;
}

.projects img{
    width: 31%;
    padding: 4px;
    margin-bottom: 5px;
    margin-left: 5px;
}

.form-box{
    margin-top: 30px;
}

.input-group input{
    width: 45%;
    border: 0;
    outline: none !important;
    padding: 10px;
    margin: 2%;
    display: inline-block;
    background: #fff;

}

.text-area textarea{
    width: 500px;
    border: 0;
    outline: none !important;
    margin-left: 50px;
    background: #fff;

}

.submit-btn{
    border: 0;
    outline: none !important;
    padding: 10px 20px;
    margin: 1%;
    background: grey;
    cursor: pointer;
    color: black;
 
}

.contact img{
    width: 30px;
    margin: -5px 10px;
}

.contact span{
    margin: 3%;
}

.contact{
    margin: 5% 0 5% 25%;
    width: 65%;
}

.icons{
    margin-left: 15px;
    word-spacing: 60px; 
}

.copyright{
    text-align: center;
    margin-bottom: 20px;
}

@media only screen and (max-width:900px)

{
    .profile-info
    {
        width: 100%;
        overflow: inherit;
    }
    .profile-img{
        width: 100%;
    }
    .expertise{
        width: 95%;
        margin-bottom: 10%;
    }
    .expertise img{
        height: 8%;
        margin: 10px 0;
    }
    .projects img{
        width: 47%;
    }
    span{
        display: block;
    }
}
