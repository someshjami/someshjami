- <!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />
    <title>nuuk</title>

    <style>
        .container{
            background-image:url("https://nuuk-e3eaa.firebaseapp.com/assets/img/slide-2.jpg");
            height: 80vh;
            width: 97%;
            background-position: center;
            background-size: cover;
            padding: 10px 20px;
            font-family: sans-serif;
            background-color: rgb(243, 241, 241);

        }
        .logo{
            background-color:orange;
            height: 20px;
            width: 40px;
            padding: 30px;
            text-size-adjust: 2px 3px;
        }
        .nav{
            padding: 10px;
                margin: 0px;
                justify-content: space-evenly;
                color:orange;
                display: flex;
                background-color:white; 
                font-family: sans-serif;      
        }
        .button{
            background-color: orange;
            color: white;
            display: flex;
            border-radius: 5px;
            padding: 10px;
            font-family: sans-serif;
        }
        .menu{
            background-color: orange;
        }
        .container1{
            background-color: orangered;
            padding: 10px;
            height: 200px;
            width: 1091px;
            margin-left:200px;
            position: relative;
            align-items: center;
            justify-content: space-evenly;
            font-family: sans-serif;
        }
        .content{
            display: flex;
            justify-content: space-evenly;
            padding-inline-start: 10px;
            padding-inline-end: 10px;
            color: white;
            font-family: sans-serif;
        }
        .button1{
            background-color: black;
            width: 50px;
            height: 200px;
            position: relative;
            margin-left: 1260px;
            font-family: sans-serif;
        }
        .head{
            color:ghostwhite;
            font-size: 100px;
            margin-left: 30px;
            font-family: sans-serif;
        }
         .index1{
             font-size: 35px;
            margin-top: -60px;
            margin-left: 100px;
            
            font-family: sans-serif;
        }
        .anchor{
            
        font-family: sans-serif;
        position:relative;
        color: #919198;
        font-size: 13px;
        letter-spacing: 1px;
        text-transform: uppercase;
        display: inline-block;
        max-width: 100%;
        text-decoration: none;
        }
        .anchor{
        overflow: hidden;
        margin-left: 0px;
        margin-top: 15px;
        padding-top: 0px;
        padding-bottom: 5px;
        cursor: pointer;
        }
        .anchor::after{
        left:0;
        content: '';
        position: absolute;
        width: 100%;
        height: 2px;
        bottom: 0;
        background-color: hsla(0,0%,100%,0.3);
        transition: .2s;
        }
        .anchor:hover::after{
            background-color: #e47312;
        }
        .container2{
            
            font-family: sans-serif;
            display: flex;
            justify-content: space-evenly;
         }
         .container3{
            
            font-family: sans-serif;
            display: flex;
            justify-content: space-evenly;
         }
         .head1{
            color:ghostwhite;
            font-size: 100px;
            margin-left: 60%;
            margin-top: -450px;
            font-family: sans-serif;
            flex-direction: column;
         }
         .index2{
            font-size: 35px;
            margin-top: -52px;
            margin-left: 850px;
            justify-content: space-evenly;
            font-family: sans-serif;
         }
       .paragraph{
        margin-left: 64%;
        font-family: sans-serif;
        margin-right: 10%;
       }  
       .nav-link{
        position:relative;
        color: #919198;
        font-size: 13px;
        letter-spacing: 1px;
        text-transform: uppercase;
        display: inline-block;
        max-width: 100%;
        text-decoration: none;
        

       }
        .nav-link::after{
        left:0;
        content: '';
        position: absolute;
        width: 100%;
        height: 2px;
        bottom: 0;
        background-color: hsla(0,0%,100%,0.3);
        transition: .2s;
        }
        .nav-link:hover::after{
            background-color: #e47312;
        }
        .nav-link{
            overflow: hidden;
        margin-left: 0px;
        margin-top: 15px;
        padding-top: 0px;
        padding-bottom: 5px;
        cursor: pointer;
       }
       .content1{
        display: flex;
        justify-content: space-evenly;
        margin-left: 10%;
        font-family: sans-serif;
        margin-right: 20%;
        

       }
    .content1 h1{
        font-size: 40px;
    }
    .images{
        background-color: aliceblue;
        padding: 15px;
        margin-bottom: 100px;  
    }
    .images .head2{
        font-size: 100px;
        color:ghostwhite;
        font-family: sans-serif;
    }
    .images .index3{
        font-size: 35px;
        font-family: sans-serif;
        margin-left: 50px;
        margin-top: -60px;
    }
    .container4{
        background-image:url("https://nuuk-e3eaa.firebaseapp.com/assets/img/banner-2.jpg");
        height: 30vh;
        width:200vh;
        background-position: center;
        background-size: cover;
        
        }
    .container4 .content2{
        background-color: rgba(248, 107, 25, 0.863);
        height: 175px;
        width:99%;
        padding: 10px;
        color: white;
        font-family: sans-serif;
    }
    .container5{
        
        font-family: sans-serif;
        justify-content: space-evenly;
        display: flex;
    }
    .card-container{
       display: flex;
      
    }
    .card{
        background-color: white;
        text-align: center;
        font-family: sans-serif;
        padding: 20px;
        width: 300px;
    }
    .blog{
        display: flex;
        justify-content: space-evenly;
        position: relative;
        font-family: sans-serif;
    }
    .blog1{
        width: 300px;
        
    }
    .blog2{
        background-color: orangered;
        padding: 15px;
        position: relative;
        
        margin-top: -30px;
        color: white;
        
    }
    .ul.ul{
        position: absolute;
        margin-left: 195px;
        margin-top: -500px;
        
    }
    .logos{
        display: flex;
        justify-content: space-evenly;
        background-color: orangered;
        height: 100px;
        position: relative;
    }
    .footer{
        background-color: black;
        display: flex;
        justify-content: space-evenly;
        color: white;
        height: 400px;
        margin-top: -17px;
        position: absolute;
        width: 1000px;
        margin-left: 150px;
        padding: 30px;
    }
    
    
    
        
    </style>
    
        
    
</head>
<body><div class="container">
        <div><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/logo-white.png" 
         alt=" logo-white" width="100px" height="50px" align="left"class=logo>
        <div class="nav"align="nav-top"><a href="#HOME" style="text-decoration: none">HOME</a>
            <a href="#PROJECTS"  style="text-decoration: none";>PROJECTS</a>
            <a href="#ABOUT"style="text-decoration: none">ABOUT</a>
            <a href="#SERVICES"style="text-decoration: none">SERVICES</a>
            <a href="#BLOG"style="text-decoration: none">BLOG</a>
            <a href="#PAGES"style="text-decoration: none">PAGES
                 <img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/sort-down.svg" height="10px" width="10px"></a>
            <div ><button class="button">GET FREE QUOTE</button></div></div></div><br>
          <div><p><h1 style="color:white;">YOU DREAM.WE CREATE.</h1></p>
            <p  style="color:white;">We turn your ideas to reality,we don't stop until you're satisfied.</p>
        </div><button class="button">GET FREE QUOTE</button>
        <div><button class="button1" style="cursor:pointer">
            <li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/facebook-logo.png" alt=""width= "30px"
                height="30px"></li>
                <li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/twitter-logo.png " alt=""width= "30px"
                    height="30px"></li>
            <li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/linkedin-logo.png " alt=""width= "30px"
                height="30px"></li>
            <li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/instagram-logo.png " alt=""width= "30px"
                height="30px"></li> </button>
        </div><div class="container1"><div class="content"><div><ul type="none">
            <li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/phone.svg"
            height="30px" width="30px"></li><br>
            <li>PHONE NUMBER</li><br>
            <li>12344-8766</li><br>
            <li>746547329</li>
        </ul></div>
        <div><ul type="none">
            <li> <img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/mail.svg" height="30px" width="30px"></li><br>
            <li>CONTACT</li><br>
            <li>contact@gmail.com</li><br>
            <li>support@gmail.com</li>
        </ul></div>
        <div><ul type="none">
            <li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/clock.svg "  height="30px" width="30px"></li><br>
            <li>OPENING TIMES</li><br>
            <li>Mon-Sat 8:00-17:30,Sunday-Closed</li><br>
            <li> <p style="cursor: pointer;">FIND ON MAP</p></li>
        </ul></div>
     </div>
    </div>
            
    </div><br><br><br><br><br><br><br><br><br><br>
    <div class="head"> SERVICES</div>
    <div class="index1"> OUR SPECILIZATION
    <a href="view all services" class="anchor"  style="margin-left: 650px;"> VIEW ALL SERVICES</a></div><br><br>
    <div class="container2"><div> <ul type="none"><li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/brickwall.svg"
         height="55px" width="55px"></li>
               <li><h4>RENOVATION</h4></li>
               <li><P>Lorem ipsum dolor sit amet consectetur adipisicing elit. Optio vel illum minus vitae, amet
                porro ipsa velit atque qui eum, non praesentium similique aut aliquam temporibus,
                 ut magni maiores. Neque.</p></li><br>
                <li><a href="LEARN MORE"class="nav-link"> LEARN MORE</a></li></ul></div>
               <div> <ul type="none"><li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/set-square.svg " 
                height="55px" width="55px"></li>
                     <li><h4>ARCHITECTURE</h4></li>
                     <li><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Optio vel illum minus vitae, amet
                        porro ipsa velit atque qui eum, non praesentium similique aut aliquam temporibus,
                         ut magni maiores. Neque.</p></li>
                         <li><br><a href="LEARN MORE" class="nav-link"> LEARN MORE</a></li></ul></div>
                <div><ul type="none"><li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/toolbox.svg"  height="55px" width="55px" ></li>
                    <li><h4>CONSTRUCTION</h4></li>
                    <li><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Optio vel illum minus vitae, amet
                     porro ipsa velit atque qui eum, non praesentium similique aut aliquam temporibus,
                      ut magni maiores. Neque.</p></li><br>
                      <li><a href="LEARN MORE"class="nav-link"> LEARN MORE</a></li></ul></div>
                <div><ul type="none"><li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/paint-roller.svg " height="55px" width="55px"></li>
                        <li><h4>FINANCIAL RESULTS</h4></li>
                        <li><p >Lorem ipsum dolor sit amet consectetur adipisicing elit. Optio vel illum minus vitae, amet
                            porro ipsa velit atque qui eum, non praesentium similique aut aliquam temporibus,
                             ut magni maiores. Neque. </p></li><br>
                        <li><a href="LEARN MORE" class="nav-link"> LEARN MORE</a></li></ul></div>

            </div></div><br><br><br><br><br><br>
    
        <img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/serv-1.jpg " 
        height="400px" width="550px" style="margin-left:100px ;">
       <div class="head1">ABOUT</div>
         <div class="index2"> <strong>WHO WE ARE</strong></div>
        <div class="paragraph"><p>Based on collective work and shared knowledge, Nuuk aims to favor dialogue and debate, to transform individual knowledge into increased creative potential.<br><br>
          Our studio is a architecture practice based in NY and Paris.
          Today, it includes 150 architects, urban planners, landscape and interior
          designers of 25 different nationalities. The company principle of
          Architecture-Studio is the collective conception. From the very beginning,
          the practice has believed in the virtues of exchange, crossing ideas, common effort, 
          shred knowledge.<br><br><br>
          <a href="MEET THE TEAM " class="nav-link">MEET THE TEAM </a></p></div><br><br>
         <div class="content1"><div><ul type="none" ><li><h1 style="color: #e47312;">170</h1><p>Employer with over 10 years of experience</p></li></ul></div>
                <div><ul type="none"><li><h1 style="color: #e47312;">10</h1><p>Years experience in construction industries</p></li></ul></div>
                <div><ul type="none"><li><h1 style="color: #e47312;">690</h1><p>Residential premises completed in 2019</p></li></ul></div>
                    <div><ul type="none"><li><h1 style="color: #e47312;">7.1</h1><p>Milion dollar value on investments</p></li></ul></div></div><br><br> <br>       
     <div> <div class="images">
            <div class="head2">PROJECTS</div>
            <div class="index3">OUR WORK
            <a href="VIEW ALL WORKS" class="anchor" style="margin-left: 900px;" >VIEW ALL WORKS</a></div><br><br><br><br>
            <div> <table cellspacing="5px">
                <tr>
                    <td><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/p-1.jpg " height="350px" width="430px" ></td>
                    <td><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/p-4.jpg" height="350px" width="430px"  ></td>
                    <td><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/p-3.jpg"  height="350px" width="430px" ></td>
                </tr>
                <tr>
                    <td><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/p-6.jpg" height="350px" width="430px" ></td>
                    <td><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/p-5.jpg" height="350px" width="430px"  ></td>
                    <td><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/p-2.jpg"  height="350px" width="430px" ></td>
                </tr>
            </table></div><br><br>
        <div class="container4"> <div class="content2">
        <h2 style="font-size: 35px ;" align="center" >LET'S MAKE SOMETHING GREAT TOGETHER</h2> 
                 <p align="center">Get in touch with us and send some basic info for a quick quote.</p><br>
                  </div></div><br><br><br>
                <div class="head"> TEAM</div>
            <div class="index1" >PROFESSIONALS
            <a href="ABOUT US" class="anchor"  style="margin-left: 650px;"> ABOUT US</a></div><br>
            <div class="container5" ><div><ul type="none" ><li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/team-1.jpg" width="250px" height="300px"></li>
                      <li  style="background-color: white; position: relative;color: black;text-align: center;
                       width: 250px;margin-top: -25px;height: 70px;"> <h3>PHILIP BROWER</h3>
                      <p style="color: gray;">Managing Director</p></li>
                      </ul></div>

                    <div> <ul type="none" ><li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/team-2.jpg " width="250px" height="300px"></li>
                    <li style="background-color: white; position: relative;color: black;text-align: center;
                    width: 250px;margin-top: -25px;height: 70px;"><h3>JOHN WICK</h3>
                    <p style="color: gray;">Managing Director</p></li></ul></div>

                <div><ul type="none"><li> <img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/team-3.jpg" width="250px" height="300px"></li>
                   <li style="background-color: white; position: relative;color: black;text-align: center;
                   width: 250px;margin-top: -25px;height: 70px;"><h3>JIMMY MCGILL</h3>
                   <p style="color: gray;">Managing Director</p></li></ul></div>

                <div><ul type="none" > <li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/team-4.jpg" width="250px" height="300px"></li>
                    <li style="background-color: white; position: relative;color: black;text-align: center;
                    width: 250px;margin-top: -25px;height: 70px;" ><h3> SARA CONNOR</h3>
                     <p style="color: gray;">Managing Director</p></li></ul></div></div>
                    

                
                <div> <ul type="none" style="cursor: pointer;background-color: orangered;width: 30px;
                 margin-left:281px ; margin-top: -127px;  padding: 4px;position: absolute;"  >
                    <li><a href="https://www.facebook.com"><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/facebook-logo.png" alt=""width= "30px"
                    height="30px"></a></li>
                    <li><a href="https://twitter.com/?lang=en"><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/twitter-logo.png " alt=""width= "30px"
                        height="30px"></a></li>
                <li><a href="https://in.linkedin.com"><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/linkedin-logo.png " alt=""width= "30px"
                    height="30px"></a></li>
                </li></ul></div>
            
                <div> <ul type="none" style="cursor: pointer;background-color: orangered;width: 30px;
                    margin-left:600px ; margin-top: -127px;  padding: 4px;position: absolute;"  >
                       <li><a href="https://www.facebook.com"><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/facebook-logo.png" alt=""width= "30px"
                       height="30px"></a></li>
                       <li><a href="https://twitter.com/?lang=en"><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/twitter-logo.png " alt=""width= "30px"
                           height="30px"></a></li>
                   <li><a href="https://in.linkedin.com"><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/linkedin-logo.png " alt=""width= "30px"
                       height="30px"></a></li>
                   </li></ul></div>

                   <div> <ul type="none" style="cursor: pointer;background-color: orangered;width: 30px;
                    margin-left:918px ; margin-top: -127px;  padding: 4px;position: absolute;"  >
                       <li><a href="https://www.facebook.com"><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/facebook-logo.png" alt=""width= "30px"
                       height="30px"></a></li>
                       <li><a href="https://twitter.com/?lang=en"><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/twitter-logo.png " alt=""width= "30px"
                           height="30px"></a></li>
                   <li><a href="https://in.linkedin.com"><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/linkedin-logo.png " alt=""width= "30px"
                       height="30px"></a></li>
                   </li></ul></div>

                   <div> <ul type="none" style="cursor: pointer;background-color: orangered;width: 30px;
                    margin-left:1235px ; margin-top: -127px;  padding: 4px;position: absolute;"  >
                       <li><a href="https://www.facebook.com"><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/facebook-logo.png" alt=""width= "30px"
                       height="30px"></a></li>
                       <li><a href="https://twitter.com/?lang=en"><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/twitter-logo.png " alt=""width= "30px"
                           height="30px"></a></li>
                   <li><a href="https://in.linkedin.com"><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/linkedin-logo.png " alt=""width= "30px"
                       height="30px"></a></li>
                   </li></ul></div><br><br><br>
          
            <div class="head2">
              CLIENT  
            </div>
            <div class="index3"  >TESTIMONIALS</div>
            <p>Aenean ut eros et nisl sagittis vestibulum.<br> Fusce neque.
                 Praesent blandit laoreet nibh. Morbi mollis tellus ac sapien.</p>
                 <a href="OUR SERVICES" class="nav-link">OUR SERVICES</a>
            
               <div class="card-container"> <div class="card"  style="margin-left: 500px;   " >SARA WILLIAM
                    <h5>CEO at Webflow</h5>
                    <p> "Duis cursus, mi quis viverra ornare, eros dolor interdum nulla,
                     ut commodo diam libero vitae erat. Aenean faucibus nibh et justo cursus id rutrum lorem imperdiet"</p></div>
                
                     <div class="card"   style="margin-left: 50px; margin-bottom: 30px; ">RAVEN DURGAN
                        <h5>Architect at Group</h5>
                        <p> "Aliquam eu nunc. Cras dapibus. Vestibulum turpis sem, aliquet eget, lobortis pellentesque, rutrum eu, nisl"</p></div> </div>
                    <br><br>
                       

                    <div class="card-container"  ><div class="card" style="margin-left: 500px;margin-top: 30px;" >JOHN JUNIOR
                        <h5>Menager at Complex</h5>
                        <p> "Duis cursus, mi quis viverra ornare, eros dolor interdum nulla,
                         ut commodo diam libero vitae erat. Aenean faucibus nibh et justo cursus id rutrum lorem imperdiet"</p></div> 
                    
                    <div class="card" style="margin-left: 50px;margin-top: 30px;" >SAMI TYPO
                        <h5>SEO at Balfin</h5>
                         <p>"Vestibulum fringilla pede sit amet augue. Morbi ac felis. Ut a nisl id ante tempus hendrerit"</p> </div>
                        </div> 
                  </div></div></div><br><br><br><br>
                   
                  <div class="head">BLOG</div>
                  <div class="index1" >LATEST NEWS
                    <a href="VIEW BLOG" class="anchor"  style="margin-left: 650px;">VIEW BLOG</a></div><br><br><br><br><br><br>


            
                  <div class="blog">
                     <div class="blog1" ><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/port-1.jpg " width="300px" height="300px">
                     <div class="blog2"><h1>BLOGPOST 1</h1>
                    <p>Service and providing potential clients and customers with testimonials is one of the best ways to market.</p>
                      <a href="READ MORE" class="nav-link" style="color: white;">READ MORE</a>
                    <div class="ul">
                        <ul type="none">
                            <li>
                                <h1 style="background-color: orangered; color: white; height: 70px;
                                width: 50px; ">17</h1>
                            </li>
                            <p style="background-color: white; color:gray; margin-top: -25px;width: 50px;height: 20px;">OCT</p>
                        </ul>
                    </div></div></div>

                      <div  class="blog1"><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/port-2.jpg " width="300px" height="300px" >
                       <div class="blog2"> <h1>BLOGPOST 2</h1>
                        <p>Service and providing potential clients and customers with testimonials is one of the best ways to market.</p>
                        <a href="READ MORE" class="nav-link" style="color: white;">READ MORE</a>
                        <div class="ul">
                            <ul type="none">
                                <li>
                                    <h1 style="background-color: orangered; color: white; height: 70px;
                                    width: 50px; ">11</h1>
                                </li>
                                <p style="background-color: white; color:gray; margin-top: -25px;width: 50px;height: 20px;">DEC</p>
                            </ul>
                        </div>
                      </div></div>

                      <div class="blog1"><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/port-3.jpg " width="300px" height="300px" >
                        <div class="blog2"> <h1>BLOGPOST 3</h1>
                           <p>Service and providing potential clients and customers with testimonials is one of the best ways to market.</p>
                           <a href="READ MORE" class="nav-link" style="color: white;">READ MORE</a>
                           <div class="ul">
                            <ul type="none">
                                <li>
                                    <h1 style="background-color: orangered; color: white; height: 70px;
                                    width: 50px; ">27</h1>
                                </li>
                                <p style="background-color: white; color:gray; margin-top: -25px;width: 50px;height: 20px;">OCT</p>
                            </ul>
                        </div>
                      </div></div>
                  </div> <br><br><br><br><br><br><br><br>

                  <div >
                     <ul type="none" class="logos">
                       <div> <li> <img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/logo-1w.png" height="80px" width="80px"></li></div>
                       <div><li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/logo-2w.png" height="80px" width="80px" ></li></div>
                        <div><li> <img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/logo-3w.png" height="80px" width="80px"></li></div>
                        <div><li> <img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/logo-4w.png" height="80px" width="80px"></li></div>
                        <div> <li> <img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/logo-5w.png" height="80px" width="80px"></li></div>
                     </ul>
                  </div>
                  <footer class="footer">
                    <div ><ul type="none"><li><h2>ABOUT NUUK </h2></li><br><br>
                                          <li>Based on collective work and shared knowledge, <br>Nuuk aims to favor dialogue and debate,<br> to transform individual knowledge into increased <br>creative potential.</li><br><br><br>
                                            <li><a href="FIND ON MAP" class="nav-link" style="color: white;">FIND ON MAP</a></li> </ul></div>
                    <div>
                        <ul type="none"> <li><h2>SERVICES</h2></li><br><br>
                                         <li>FINANCIAL RESULTS</li><br>
                                         <li>CONSTRUCTION</li><br>
                                         <li>ARCHITECTURE</li><br>
                                         <li>ARCHITECTURE</li><br>
                                         <li>RENOVATION</li>
                                        </ul></div>  
                    <div><ul type="none"><li><h2>CONTACT US</h2></li><br><br>
                        <li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/phone.svg" height="30px" width="30px"> PHONE NUMBER</li>
                        &nbsp;<li>1-800-506-266</li>
                        <li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/clock.svg"height="30px" width="30px" >OPENING TIMES</li>
                        &nbsp;<li>Mon - Sat 8:00 - 17:30, Sunday - Closed</li>
                        <li><img src="https://nuuk-e3eaa.firebaseapp.com/assets/img/mail.svg" height="30px" width="30px">CONTACT</li>
                        &nbsp;<li>contact@nuuk.com</li>
                        
                    </ul></div>                                          
                  </footer>
</body>
</html>
👋 Hi, I’m @someshjami
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
someshjami/someshjami is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
