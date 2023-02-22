# oasis_task2level
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PORTFOLIO</title>
    <link rel="stylesheet" type="text/css" href="css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css" integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <div class="hero">
           <nav>
             <h2 class="logo"><span class="a">PORTFO</span><span>LIO</span></h2>
             <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">ABOUT</a></li>
                <li><a href="#"> SERVICE</a></li>
                <li><a href="#">SKILL</a></li>
                <li><a href="#"> CONTACT</a></li>
                

             </ul>
             <a href="#" class="btn">SUBSCRIBE</a>
           </nav>
           <div class="content">
            <h4>Hello,my name is</h4>
            <h1 class="a">SHIVAM <span>KUMAR</span></h1>
            <h3>I am a web developer</h3>
            <div class="newsletter">
                <form>
                    <input type="email"name="email" id="mail" placeholder="Enter your mail">
                    <input type="submit" name="submit"value="letstart">
                </form>

            </div>

           </div>
    </div>

    <section class="about">
        <div class="main">
            <img src="/ss.jpg">
            <div class="about-text">
                <h2>ABOUT ME</h2>
                <h5>WEB DEVELOPER & <span>DESIGNER</span></h5>
                <p>
                    I AM SHIVAM KUMAR,I AM A FRONT END DEVELOPER .I CAN PROVIDE CLEAN CODE AND PIXEL
                    PERFECT ANIMATION.CURRENTLY I  AM PURSUING MY B.TECH FROM SHIVALIK COLLEGE OF ENGINEERING
                    IN BRANCH O F COMPUTER SCIENCE OF ENGINEERING.I AM FROM BIHAR EAST CHAMPARAN .BUT CURRENTLY
                    I LIVE IN DEHRADUN FOR MY UG COURSE .THANK YOU!/.
                </p>
                <button type="button">Lets Talk!</button>

            </div>

        </div>

    </section>

      <div class="service">
        <div class="title">
            <h2>OUR SERVICES</h2>
        </div>
        <div class="box">
            <div class="card">
                <i class="fa-sharp fa-solid fa-bars"></i>
                <h5>WEB DEVELOPMENT</h5>
                <div class="pra">
                    <p>EVERY WEBSITE BUILD WITH TWO PRIMARY GOALS: FISRT IT NEED WORK ACROOS ALL DEVICE
                        SECOND IT WORK AS FAST. </p>

                        <p style="text-align: center;">
                            <a class="button" href="#" >READ MORE</a>
                        </p>
                   
                   

                </div>

            </div>


            <div class="card">
                <i class="far fa-user"></i>
                <h5>WEB DEVELOPMENT</h5>
                <div class="pra">
                    <p>EVERY WEBSITE BUILD WITH TWO PRIMARY GOALS: FISRT IT NEED WORK ACROOS ALL DEVICE
                        SECOND IT WORK AS FAST. </p>

                        <p style="text-align: center;">
                            <a class="button" href="#" >READ MORE</a>
                        </p>
                   
                   

                </div>

            </div>


            <div class="card">
                <i class="far fa-bell"></i>
                <h5>WEB DEVELOPMENT</h5>
                <div class="pra">
                    <p>EVERY WEBSITE BUILD WITH TWO PRIMARY GOALS: FISRT IT NEED WORK ACROOS ALL DEVICE
                        SECOND IT WORK AS FAST. </p>

                        <p style="text-align: center;">
                            <a class="button" href="#" >READ MORE</a>
                        </p>
                   
                   

                </div>

            </div>

        </div>

      </div>


       <div class="contact-me">
        <p>LET ME GET A BEAUTY FULL WEBSITE</p>
        <a  class="b2"href="#">HIRE ME</a>

       </div>


       <footer>
        <p>THANK YOU</p>
        <p>FOR VIEWING MY PORTFOLIO</p>
        <div class="social">
            <a href="http://www.facebook.com/Shivam kumar"><i class="fa-brands fa-facebook"></i></a>
            <a href="http://www.instagram.com/_its__shivam11"><i class="fa-brands fa-instagram"></i></a>
            <a href="http://www.google.com"><i class="fa-solid fa-envelope"></i></a>
            <a href="mailto:shivamkumaradp4@gmail.com"><i class="fa-solid fa-messages-question"></i>sk</a>
            <!-- <a data-email="rahulneha@likeher.com" href="mailto:shivamkumaradp4@gmail.com">MAIL TO:SHIVAM</a> -->
            
        </div>
        <p class="end">COPYRIGHT BY SHIVAM KUMAR @2023</p>
        
       </footer>
</body>
</html>





##csssss

*{
    padding: 0;
    margin: 0;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    box-sizing: border-box;

}
.hero{
    height: 100vh;
    width: 100%;
    background-image: url(/sssss.jpg);
    background-size: cover;
    background-position: center;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: 45px;
    padding-left: 8%;
    padding-left: 7%;
}
.logo{
    color: white;
    font-size: 35px;
    letter-spacing: 2px;
    cursor: pointer;

}
span{
    color: #f9004d;

}
.a{
    color: #000;
}
nav ul li{
    list-style: none;
    display: inline-block;
    padding: 11px 25px;

}
nav ul li a{
    color:white;
    text-decoration: none;
    font-weight: bold;
    text-transform: capitalize;
}
nav ul li a:hover{
    color: #f9004d;
    transition: .4s;
}
.btn{
    background-color: #f9004d;
    color: white;
    text-decoration: none;
    border: 2px solid transparent;
    padding: 11px 25px ;
    border-radius: 30px;
    transition: transform.4s;

}
.btn:hover{
    transform: scale(1.2);
}
.content{
    position: absolute;
    top: 50%;
    left: 8%;
    transform: translateY(-50%);

}
h1{
    color: #f9004d;
    margin: 20px 0px 20px;
    font-size: 55px;
}
h3{
    color: antiquewhite;
    font-size: 25px;
    margin-bottom: 50px;
}
h4{
    color:cyan ;
    letter-spacing: 2px;
    font-size: 21px;
}
.newsletter form{
    width: 380px;
    max-width: 100%;
    position: relative;
}
.newsletter form input:first-child{
    font-display: inline-block;
    width: 100%;
    padding: 14px 130px 14px 15px;
    border: 4px solid #f9004d;
    outline: none;
    border-radius: 30px;
}
.newsletter form input:last-child{
    position: absolute;
    display: inline-block;
    outline: none;
    border: none;
    padding: 10px 30px;
    border-radius: 30px;
    background-color: #f9004d;
    color: aliceblue;
    box-shadow: 0px 0px 5px #000,0px 0px 15px #858585;
    top: 7px;
    right: 7px;

}
.about{
    width: 100%;
    padding: 100px 0px;
    background-color: #191919;
}
.about img{
    height: auto;
    width: 500px;
}
.about-text{
    width: 505px;
}
.main{
    width: 1111px;
    max-width: 90%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-around;
}
.about-text h2{
    color:white;
    font-size: 75px;
    text-transform: capitalize;
    margin-bottom:21px ;

}
.about-text h5{
    color:darkslategrey;
    letter-spacing: 2px;
    font-size: 22px;
    margin-bottom: 25px;
    text-transform: capitalize;

}
.about-text p{
    color: #f9004d;
    letter-spacing: 2px;
    line-height: 27px;
    font-size: 18px;
    margin: 45px;
}
button{
    background-color: #f9004d;
    color: antiquewhite;
    text-decoration: none;
    border: 2px solid transparent;
    font-size: bold;
    padding: 11px 11px ;
    border-radius: 21px;
    transition: .4s;
}
button:hover{
    background-color: transparent;
    border: 5px solid #f9004d;
    cursor: pointer;
}
.service{
    background-color: #101010;
    width: 100%;
    padding: 100px 0px;
}
.title h2{
    color: white;
    font-size: 75px;
    width: 1130px;
    margin: 30px auto;
    text-align: center;
}
.box{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 402px;
}
.card{
    height: 365px;
    width: 335px;
    padding: 20px 35px;
    background: #191919;
    border-radius: 20px;
    margin: 15px;
    position: relative;
    overflow: hidden;
    text-align: center;
}
.card i{
    font-size: 51px;
    display: block;
    text-align: center;
    margin: 25px 0px ;
    color: #f9004d;
}
h5{
    color: white;
    font-size:22px;
    margin-bottom:15px;

}
.pra p{
    color: #fcfc;
    font: 17px;
    line-height: 27px;
    margin-bottom: 25px;
}
.card .button{
    background-color: #f9004d;
    color: antiquewhite;
    text-decoration: none;
    border: 2px solid transparent;
    font-size: bold;
    padding: 11px 11px ;
    border-radius: 21px;
    transition: .4s;
}
.card .button:hover{
    background-color: transparent;
    border: 5px solid #f9004d;
    cursor: pointer;
}
.contact-me{
    width: 100%;
    height: 291px;
    background: #101010;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
}
.contact-me p{
    color: white;
    font-size: 30px;
    font-weight: bold;
    margin-bottom: 25px;

}
.contact-me .b2{
    background-color: #f9004d;
    color: antiquewhite;
    text-decoration: none;
    border: 2px solid transparent;
    font-size: bold;
    padding: 11px 11px ;
    border-radius: 21px;
    transition: .4s;
}
.contact-me .b2:hover{
    background-color: transparent;
    border: 5px solid #f9004d;
    cursor: pointer;
}
footer{
    position: relative;
    width: 100%;
    height: 400px;
    background: #101010;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
footer p:nth-child(1){
    font-size: 30px;
    color: white;
    margin-bottom: 20px;
    font-weight: bold;
}
footer p:nth-child(2){
    color: white;
    font-size: 17px;
    width: 500px;
    text-align: center;
    line-height: 26px;
}
.social{
    display: flex;
} 
.social a{
    width: 45px;
    height: 45px;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #f9004d;
    border-radius: 50%;
    margin: 22px 11px;
   
    color: white;
    text-decoration: none;
    font-size: 20px;
}
.social a:hover{
    transform: scale(1.3);
    transition: .33s;

} 
.end{
    position: absolute;
    color: #f9004d;
    bottom: 35px;
    font-size: 14px;

}

