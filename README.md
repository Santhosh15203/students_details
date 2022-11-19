content.css
body{
    margin: 0%;
    padding: 0%;
    background-color: whitesmoke;
}
.com{
    background-color:  #6782bf;
    margin-top: 0%;
    height: 12vh;
    padding-left: 110px;
    padding-top: 15px;  
}
.tit{
    margin-top: -65px;
    background-color: transparent;
    color: black;
    margin-left: 320px;
    
}
.sms{
    color: rgb(9, 50, 134);
    font-size: x-large;
    margin-left: 40px;
}
.ive{
    font-size: larger; 
    color: rgb(2, 97, 18);
}
.del{
    margin-left: 40px;
    font-size: x-large;
    padding-bottom: 650px;
    color: rgb(9, 50, 134);
}
.slas{
    font-size: x-large;
    text-decoration: none;
    color: black;
}

.go{
    margin-top: -205px;
    padding-top: 50px;
    margin-left: 30px;
    font-size: smaller;
    width: 100px;
    background: transparent;
}
.log{
    text-decoration: none;
    color: whitesmoke;
    background-color: tomato;
    margin-left: 30px;
    font-size: smaller;
    padding-top: 10px;
    padding-left: 15px;
    padding-bottom: 10px;
    padding-right: 15px;
    border-radius: 3px;
    box-shadow: 2px solid whitesmoke;
    font-family:  Arial, Helvetica,sans-serif; 
}
.log:hover{
    cursor: pointer;
    background-color: rgb(80, 80, 211);
}
.reg{
    text-decoration: none;
    color:rgb(158, 44, 24);
    background-color: tomato;
    color: whitesmoke;
    margin-left: 5px;
    padding-top: 10px;
    padding-left: 10px;
    padding-bottom: 10px;
    padding-right: 10px;
    border-radius: 3px;
    font-size: smaller;
    font-family:  Arial, Helvetica,sans-serif; 
}
.reg:hover{
    cursor: pointer;
    background-color: rgb(80, 80, 211);
}
.pic{
    margin-top: 15px;
    background-position:center;
    position: absolute;
}
.cont{
    margin-left: 10px;
    text-decoration: none;
    color: whitesmoke;
    border-radius: 3px;
    padding-top: 10px;
    padding-left: 10px;
    padding-bottom: 10px;
    padding-right: 10px;
    font-family:  Arial, Helvetica,sans-serif;  
}

.blo{
    margin-left: 10px;
    text-decoration: none;
    color: whitesmoke;
    border-radius: 3px;
    padding-top: 10px;
    padding-left: 10px;
    padding-bottom: 10px;
    padding-right: 10px;
    font-family:  Arial, Helvetica,sans-serif;
}
.pro{
    margin-left: 10px;
    text-decoration: none;
    color: whitesmoke;
    padding-top: 10px;
    padding-left: 10px;
    padding-bottom: 10px;
    padding-right: 10px;
    border-radius: 3px;
    font-family:  Arial, Helvetica,sans-serif;
}
.ser{
    margin-left: 10px;
    text-decoration: none;
    color: whitesmoke;
    padding-top: 10px;
    padding-left: 10px;
    padding-bottom: 10px;
    padding-right: 10px;
    border-radius: 3px;
    font-family:  Arial, Helvetica,sans-serif;
}
.abo{
    margin-left: 10px;
    text-decoration: none;
    border-radius: 3px;
    padding-top: 10px;
    padding-left: 10px;
    padding-bottom: 10px;
    padding-right: 10px;
    color: whitesmoke;
    font-family:  Arial, Helvetica,sans-serif;
}
.home{
   
    text-decoration: none;
    color: whitesmoke;
    padding-top: 10px;
    padding-left: 10px;
    padding-bottom: 10px;
    padding-right: 10px;
    margin-left: 80px;
    border-radius: 3px;
    font-family:  Arial, Helvetica,sans-serif;
}
.home:hover{
    cursor: pointer;
    background-color: rgb(80, 80, 211);
}
.abo:hover{
    cursor: pointer;
    background-color: rgb(80, 80, 211);
}
.ser:hover{
    cursor: pointer;
    background-color: rgb(80, 80, 211);
}
.pro:hover{
    cursor: pointer;
    background-color: rgb(80, 80, 211);
}
.blo:hover{
    cursor: pointer;
    background-color: rgb(80, 80, 211);
}
.cont:hover{
    cursor: pointer;
    background-color: rgb(80, 80, 211);
}
.log:hover{
    cursor: pointer;
    background-color: rgb(80, 80, 211);
}
.reg:hover{
    cursor: pointer;
    background-color: rgb(80, 80, 211);
}
--------------------------------------------------
content.html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>SMS COMPANY</title>
    <link rel="stylesheet" href="content.css">
</head>
<body>
    
    <span  class="nav" >
        
        <h1 class="com"><b class="sms"> SMS </b>  <br> <b class="del"> DE<b class="ive">LIVE</b>RY </b></h1>
        <div class="tit"><a href="#" class="home">HOME</a>
        <a href="#" class="abo">ABOUT</a>
        <a href="#" class="ser">SERVICES</a>
        <a href="#" class="pro">PROCESS</a>
        <a href="#" class="blo">BLOG</a>
        <a href="#" class="cont">CONTACT US</a>
        <a href="#" class="log">LOGIN</a>
        <a href="#" class="reg"> REGISTER</a>
        </div>
    </span><br><br>
    <img src="image/google (1).jpg" class="go">
    <img class="pic" src="image/back.jpg" >

</body>
</html>
------------------------------------------------
index.html
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Website</title>
    <link rel="stylesheet" href="stylesheet.css">
    <script src="https://kit.fontawesome.com/c127414c8b.js" crossorigin="anonymous"></script>
  
</head>
<body>
    <form class="form" action="">
        <h2 class="num0">Sign In</h2><br>
        <span class="num2"><i class="fa-solid fa-user"><input class="num22" type="text" placeholder="username or email"></i></span><br><br>
        <span class="num3"><i class="fa-solid fa-key"><input class="num33" type="password" placeholder="password" id="h0"></i></span>
        <span class="eye" onclick=" myfunction()">
            <i id="h1" class="fa-solid fa-eye"></i>
            <i id="h2" class="fa-solid fa-eye-slash"></i></span><br><br>
        <a href="https://myaccount.google.com/intro/signinoptions/password" class="wrd">Forgot  Password?</a><br><br><br>
        <a href="content.html" class="click">Login</a>
        <p class="para">Don't have an account?<a href="register.html" class="sign">Register</a></p><br>
        <p class="para1">----------------  or connect with  --------------------</p><br>
        <a href="https://m.youtube.com/channel/UCUyH84XoDAUPeKaGsITnxkg" class="google"><i class="fa-brands fa-google"></i>Sign in with   Google+ </a><br><br><br>
        <a href="https://www.facebook.com/login/" class="fb"><i class="fa-brands fa-facebook"></i>Sign in with   Facebook</a><br><br><br>
        <a href="https://www.instagram.com/accounts/login/" class="insta"><i class="fa-brands fa-instagram"></i>Sign in with   Instagram</a>
    

       
    </form>



    <script>
        function myfunction(){
            var x=document.getElementById('h0');
            var y=document.getElementById("h1");
            var z=document.getElementById("h2");
            if(x.type==="password"){
                x.type="text";
                y.style.display="block";
                z.style.display='none';
            }
            else{
                x.type="password";
                y.style.display="none";
                z.style.display="block";
            }
        }
    </script>
    
</body>
</html>
--------------------------------------------------------
output.css
body{
    margin: 0;
    padding: 0%;

}
.out{
    font-size: larger;
    text-align: center;
    margin-top: 250px;
}
---------------------------------
output.html
<!DOCTYPE html>
<html lang="en">
<head>

    <title>Verification</title>
    <link rel="stylesheet" href="output.css">
</head>
<body>
    <h1 class="out">REGISTERATION SUCCESSFULLY !!!</h1>
    
</body>
</html>
---------------------------------------
register.css
body{
    margin: 0%;
    padding: 0%;
    background-image:url("image/register.jpg");
    background-position: cover;
}
.form{
    top: 6%;
    padding-left: -20px;
    margin-left: 40px;
    color: white;
    background: transparent;
    position: absolute;
    width: 600px;
    height: 90vh;
    border-radius: 6px;
    border: 2px solid white;
    box-shadow: 4px solid whitesmoke;
    
}
.h1{
    padding-top: 13px;
    color: rgb(255, 232, 21);
    text-align: center;
}
.para{
    color: white;
    padding-top: 20px;
    padding-left: 45px;
    font-size: large;
    line-height: 20px;
}
.but{
    margin-left: 45px;
    width: 80px;
    height: 5vh;
    background-color: rgb(189,0,0);
    border-bottom: none;
    border-top: none;
    border-left: none;
    border-right: none;
    border-radius: 5px;
    font-size:smaller;
}
.li{
    color: white;
    text-decoration: none;
    border-color: #125688;
    cursor: pointer;
}
.but:hover{
    background-color:  rgb(175, 54, 54);
}
.design{
    top: 3%;
    right: -20px;
    color: white;
    background-color: transparent;
    position: absolute;
    width: 760px;
    height: 100vh;
}
.head{
    color: rgb(255, 232, 21);
    text-align: center;
    margin-top: 30px;
}
.first{
    padding-left: 80px;
    margin-top: 10px;
    position: absolute;
    
}
.n2{
    width: 250px;
    height: 6vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white  ;
    color: white;
}

.second{
    padding-left: 400px;
    margin-top: 10px;
    position: absolute;
}
.s2{
    width: 250px;
    height: 6vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white  ;
    color: white;
}
.mail{
    padding-left: 80px;
    margin-top: 55px;
    position: absolute;
}
.m2{
    width: 250px;
    height: 6vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white  ;
    color: white;
}
.pass{
    padding-left: 400px;
    margin-top: 60px;
    position: absolute;
}
.p2{
    width: 250px;
    height: 6vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white  ;
    color: white;

}
.h9{
    text-align: center;
    color: aqua;
}
.gen{
    padding-left: 80px;
    margin-top: 110px;
    position: absolute;
    cursor: pointer;
}
.gen1{
    width: 250px;
    height: 4vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    
    color: white;
}
.na{
    font-size: 15px;
    font-weight:400;
}
.add{
    padding-left: 80px;
    margin-top: 190px;
    position: absolute;
}
.add2{
    width: 580px;
    height: 8vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white;
    color: white;
    margin-top: 15px;
    font-size: 15px;
    font-weight: 190px;
}
.phone{
    padding-left: 400px;
    margin-top: 130px;
    position: absolute;
}
 .ph2{
    width: 60px;
    height: 5vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background: transparent;
    border-bottom: 1px solid white;
    color: white;
    margin-top: 7px;
    font-size: 15px;
    font-weight: 190px;
 }
 .ph2:hover{
    background-color: rgb(7, 4, 4);
 }
 .ph3{
    width: 185px;
    height: 5vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white;
    color: white;
 }
 .state{
    padding-left: 80px;
    margin-top: 290px;
    position: absolute;
 }
 .sa2{
    width: 180px;
    height: 6vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white  ;
    color: white;
 }
 .dist{
    padding-left: 280px;
    margin-top: 290px;
    position: absolute;
 }
 .di2{
    width: 180px;
    height: 6vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white  ;
    color: white;
 }
 .pincode{
    padding-left: 480px;
    margin-top: 290px;
    position: absolute;
 }
 .pin2{
    width: 180px;
    height: 6vh;
    border-radius: 5px;
    border: none;
    outline: none;
    padding-left: 5px;
    background-color: transparent;
    border-bottom: 1px solid white  ;
    color: white;
 }
 .last{
    padding-left: 80px;
    margin-top: 380px;
    position: absolute;
 }
 .la2{
    color: rgb(191, 255, 0);
 }
 .button{
   
    margin-top: 420px;
    position: absolute;
    text-align: center;
    width: 600px;
    margin-left: 70px;
    height: 4vh;
    background-color:  rgb(189,0,0);
    color: white;
    border: none;
    border-radius: 10px;
    cursor: pointer;
    text-decoration: none;
    padding-top: 10px;
   
 }
 .button:hover{
    background-color:  rgb(175, 54, 54);
 }
 -----------------
 register.html
 !<!DOCTYPE html>
<html lang="en">
<head>
    <title>Register Form</title>
    <link rel="stylesheet" href="register.css">
    
</head>
<body>
    <form class="form" action="/action_page.php">
    <h3 class="h1">INFORMATION</h3>
    <p class="para">Digital marketing, also called online marketing, is the promotion of <br> brands to connect with potential customers using the internet and other forms of digital communication. This includes not only email, social <br> media, and web-based advertising, but also text and multimedia messages <br> as a marketing channel. <br><br>Digital marketing considers how individual tools or digital channels <br> can convert prospects. A brand's digital marketing strategy may use <br> multiple platforms or focus all of its efforts on 1 platform. For example, <br> a company may primarily create content for social media platforms and email marketing campaigns while ignoring other digital marketing <br> avenues. <br><br>On the other hand, inbound marketing is a holistic concept. It considers <br> the goal first, then looks at the available tools to determine which will effectively reach target customers, and then at which stage of the sales funnel that should happen. As an example, say you want to boost website traffic to generate more prospects and leads. You can focus on search <br> engine optimization when developing your content marketing strategy, resulting in more optimized content, including blogs, landing pages, and more.</p>
    <button class="but"><a href="index.html" class="li">Sign In</a></button>
    </form>  
    <form class="design" action="/action_page.php">
        <h3 class="head">REGISTERATION  FORM</h3> 
        <h4 class="h9">Please fill in this form to create an account. </h4>

        <span class="first"><label class="na" for="">First Name</label><br>
            <input class="n2" type="text" placeholder="first name"></span>
        <span class="second"> <label class="s1" for="">Last Name</label><br>
        <input class="s2" type="text" placeholder="last name"></span><br>
        <span class="mail">
            <label class="m1" for="">E-mail ID</label><br>
            <input class="m2" type="mail" placeholder="xyz123@gmail.com">
        </span>
        <span class="gen" >
            <p class="gen1" >Gender <br><br>
                <input class="r1" type="radio" name="gender">
                <label for="">Male</label>
                <input class="r2" type="radio" name="gender">
                <label for="">Female</label>
                <input class="r3" type="radio" name="gender">
                <label for="">Others</label>
            </p>
        </span>
        <span class="pass">
            <label class="p1" for="">Password</label><br>
            <input type="text" class="p2" placeholder="password">
        </span>
        <span class="phone">
            <label class="ph1" for="">Phone Number</label><br>
            <select class="ph2" name="" id="">
                <option >+93</option>
                <option >+61</option>
                <option >+880</option>
                <option >+32</option>
                <option >+55</option>
                <option >+1</option>
                <option >+86</option>
                <option >+45</option>
                <option >+20</option>
                <option >+358</option>
                <option >+33</option>
                <option >+49</option>
                <option >+30</option>
                <option >+299</option>
                <option >+852</option>
                <option >+354</option>
                <option >+91</option>
                <option >+62</option>
                <option >+964</option>
                <option >+353</option>
                <option >+972</option>
                <option >+39</option>
                <option >+81</option>
                <option >+60</option>
                <option >+52</option>
                <option >+95</option>
                <option >+977</option>
                <option >+31</option>
                <option >+64</option>
                <option >+850</option>
                <option >+92</option>
                <option >+63</option>
                <option >+48</option>
                <option >+7</option>
                <option >+966</option>
                <option >+381</option>
                <option >+65</option>
                <option >+27</option>
                <option >+82</option>
                <option >+34</option>
                <option >+94</option>
                <option >+268</option>
                <option >+41</option>
                <option >+886</option>
                <option >+66</option>
                <option >+90</option>
                <option >+380</option>
                <option >+44</option>
                <option >+1</option>
                <option >+84</option>
            </select>
            <input class="ph3" type="number" placeholder="97*** *****"><br><br>
        </span>
        <span class="add">
            <label class="add1" for="">Address</label><br>
            <textarea class="add2"  name="address" placeholder="permanent address..." cols="30" rows="9"></textarea>
        </span>
        <span class="state">
            <label class="sa1">State</label><br>
            <input class="sa2" type="text" placeholder="state">
        </span>
        <span class="dist">
            <label class="di1">District</label><br>
            <input class="di2" type="text" placeholder="district">
        </span>
        <span class="pincode">
            <label class="pin1">Pincode</label><br>
            <input class="pin2" type="number" placeholder="pincode">
        </span>
        <span class="last">
            <label class="la1">By creating an account you agree to our <a href="t and c.html" class="la2"> Terms & Privacy.</a> </label>
        </span>
        <a href="output.html" class="button">Register</a>

    </form>
</body>
</html>
-------------------------------
stylesheet.css
body{
    background-image: url('images/login.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    height: 100vh;
}
.form{
    margin-top: 100px;
    outline: outset;
    color: #746c6c;
    margin-left: 800px;
    width: 405px;
    height: 530px;
    background: transparent;
    border-bottom: px solid #746c6c;
    border-radius: 15px;
    box-shadow:4px 5px 7px rgb(211, 199, 199);
}
.num0{
    background: transparent;
    border-radius: 1px;
    text-align: center;
    padding-top: 15px;
    color: #746c6c;
    border-bottom: 3px solid #746c6c;
    border-color: #746c6c;
    padding-bottom: 5px;
    outline: outset;
}
.num2{

    color: #746c6c;
    width: 490px;
    height: 10px;
    padding: 10px;
    margin-left: 35px;
    border-radius: 5px;
    
}
.num22{
   background: transparent;
   color: white;
    width: 260px;
    height: 20px;
    padding: 3px;
    border: none;
    border-radius: 5px;
    margin-left: 20px;
    outline: none;
    border-bottom: 2px solid #746c6c;
}
.num3{

    background: transparent;
    width: 450px;
    height: 50px;
    padding: 10px;
    margin-left: 35px;
    border-radius: 5px;
    color: #746c6c;
}
.num33{
   
    width: 260px;
    height: 28px;                               
    padding: 3px;
    border: none;
    border-radius: 5px;
    margin-left: 20px;
    outline: none;
    background: transparent;
    border-bottom: 2px solid #746c6c;
    color: white;
}
.eye{
    margin-left: -30px;
    position: absolute;
    margin-top: 11px;
    color: #746c6c;
    cursor: pointer;
}
#h1{
    display: none;
}

.wrd{

    margin-left: 230px;
    color: #746c6c;
   
}
.wrd:hover{
    cursor: pointer;
    color: #d14835;
}
.click{
    padding-left: 130px;
    padding-right: 130px;
    margin-left: 40px;
    border-radius: 10px;
    padding-top: 7px;
    padding-bottom: 7px;
   font-size: medium;
   border-radius: 10px;
   background: transparent;
   color: #746c6c;
   text-decoration: none;
   border-bottom:2px solid #746c6c;
   border-left: 3px solid #746c6c;
   border-top: 3px solid #746c6c;
   border-right: 1px solid #746c6c;
   box-shadow: 5px solid #746c6c;
   
  
}
.click:hover{
    cursor: pointer;
    color: whitesmoke;
    background-color: rgb(199, 13, 13);
}
.para{
    
    text-align: center;
    margin-top: 20px;
    font-size: large;
    margin-left: -10px;
    color: #746c6c;

}
.sign{
    
    color: #746c6c;
    font-size: large;
    font-weight: bold;
    text-decoration: none;
    margin-left: 5px;
}
.sign:hover{
    cursor: pointer;
    color: #d14835;
}
.para1{
    
    text-align: center;
    margin-top: -10px;
    font-weight: bold;
    margin-left: -8px;
    color: #746c6c;

}

.google{ 
    padding-left: 70px;
    padding-right: 75px;
    padding-top: 7px;
    padding-bottom: 7px;
    text-decoration: none;
    margin-left: 40px;
    border-radius: 10px;
    color: #746c6c;
    border-bottom:2px solid #746c6c;
    border-left: 3px solid #746c6c;
    border-top: 3px solid #746c6c;
    border-right: 1px solid #746c6c;
    box-shadow: 5px solid #746c6c;
}
.google:hover{
    cursor: pointer;
   
    background-color: #f7290e;
}
.fa-google{
    width: 30px;

}
.fa-facebook{
    width: 30px;
}
.fb{
    color: #746c6c;
    padding-left: 70px;
    padding-right: 70px;
    padding-top: 7px;
    padding-bottom: 7px;
    text-decoration: none;
    margin-left: 40px;
    border-radius: 10px;
    color: #746c6c;
    border-bottom:2px solid #746c6c;
   border-left: 3px solid #746c6c;
   border-top: 3px solid #746c6c;
   border-right: 1px solid #746c6c;
   box-shadow: 5px solid #746c6c;
   
}
.fb:hover{
    cursor: pointer;
   
    background-color: rgb(32, 38, 53);
   
}
.fa-instagram{
    width: 30px;
}
.insta{
    padding-left: 70px;
    padding-right: 70px;
    padding-top: 7px;
    padding-bottom: 7px;
    text-decoration: none;
    margin-left: 40px;
    border-radius: 10px;
    color: #746c6c;
    border-bottom:2px solid #746c6c;
   border-left: 3px solid #746c6c;
   border-top: 3px solid #746c6c;
   border-right: 1px solid #746c6c;
   box-shadow: 5px solid #746c6c;
    
}
.insta:hover{
    cursor: pointer;
    background-color: #08558b;
}
-----------------------------------------
t and c.css
body{
    background:linear-gradient(to right,tomato,blue);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    height: 100vh;
}
.form{
    background-color: rgb(103, 143, 236);
    width: 350px;
    height: 480px;
    border-radius: 5px;
    box-shadow:2px 2px 4px;
    margin-top: 100px;
    margin-left: 700px;
}
.num0{
    text-align: center;
    padding-top: 15px;
    color: white;
    border-color: white;
    background: linear-gradient(to right,#dd4b39,rgb(0,0, 225));
    padding-bottom: 5px;
    border-radius: 2px 2px 5px 5px;
}
.num22{
    width: 230px;
    height: 30px;
    padding: px;
    border: none;
    border-radius: 5px;
    margin-left: 15px;
    outline: none;
}
.num33{
    width: 230px;
    height: 28px;                               
    padding: 3px;
    border: none;
    border-radius: 5px;
    margin-left: 15px;
    outline: none;
}
.num2{
    background-color: white;
    width: 400px;
    height: 50px;
    padding: 10px;
    margin-left: 30px;
    border-radius: 5px;
    outline: none;
}
.eye{
    margin-left: -30px;
    position: absolute;
    margin-top: 11px;
}
#h1{
    display: none;
}
.num3{
    background-color: white;
    width: 380px;
    height: 50px;
    padding: 10px;
    margin-left: 30px;
    border-radius: 5px;
}
.wrd{
    
    margin-left: 200px;
    color: black;
    border-color: black;
}
.wrd:hover{
    cursor: pointer;
    color: #d14835;
}
.click{
    background-color:rgb(189, 0, 0);
    color: rgb(226, 229, 237);
    text-align: center;
    border-bottom: none;
    border-radius: 8px;
    height: 8vh;
    box-shadow: none;
    width: 280px;
    height:30px;
    margin: 30px;
    border-color: rgb(103, 143, 236) ;
    font-size: medium;
    font-family: Arial, Helvetica, sans-serif;
}
.click:hover{
    cursor: pointer;
    background-color: rgb(175, 54, 54);
}
.para{
    text-align: center;
    margin-top: -10px;
    font-size: large;
}
.sign{
    color: rgb(189, 0, 0);
    border-color: black;
    font-size: large;
    font-weight: bold;
    text-decoration: none;
    margin-left: 5px;
}
.sign:hover{
    cursor: pointer;
    color: #d14835;
}
.para1{
    text-align: center;
    margin-top: -15px;
    font-weight: bold;
}

.google{
    background-color: #dd4b39;
    color: white;
    padding-left: 10px;
    padding-right: 95px;
    padding-top: 5px;
    padding-bottom: 5px;
    text-decoration: none;
    margin-left: 35px;
    border-radius: 5px;
    border-color: rgb(103, 143, 236) ;
    
}
.google:hover{
    cursor: pointer;
    background-color: #d14835;
}
.fa-google{
    width: 30px;

}
.fa-facebook{
    width: 30px;
}
.fb{
    background-color:#3B5998;
    color: white;
    padding-left: 10px;
    padding-right: 90px;
    padding-top: 5px;
    padding-bottom: 5px;
    text-decoration: none;
    margin-left: 35px;
    border-radius: 5px;
    border-color: rgb(103, 143, 236) ;
}
.fb:hover{
    cursor: pointer;
    opacity: 0.9;
}
.fa-instagram{
    width: 30px;
}
.insta{
    background-color:#125688;
    color: white;
    padding-left: 10px;
    padding-right: 90px;
    padding-top: 5px;
    padding-bottom: 5px;
    text-decoration: none;
    margin-left: 35px;
    border-radius: 5px;
    border-color: rgb(103, 143, 236) ;
}
.insta:hover{
    cursor: pointer;
    background-color: #206a9f;
}
------------------------------------------------
t and c.html;
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Terms and Conditions</title>
    <link rel="stylesheet" href="t and c.css">
</head>
<body>
    <span class="d1"><h1 class="dig1">Digital</h1>
    <h1 class="mar">Marketing</h1></span>
    <h1 class="ter">TERMS AND CONDITIONS</h1>
    <span class="tit"><h1 class="t1">Terms and </h1>
    <h1 class="t2">Conditions</h1></span>
    <p class="p1"><b >Marketing</b> aims to deal with its clients in a professional, timely and favorable manner. By engaging <b>Marketing </b>with their business, the clients <br>will be accepting the following terms and conditions:</p>
    <span class="s1"><h1 class="p2">The </h1>
    <h1 class="p3">Contract</h1></span>
    <ul class="order">
        <li>An independent contractor relationship will be created between the clients and <b>Marketing</b>, and that no partnership or joint venture <br>is intended or implied by either party.</li><br>
        <li>A date of commencement of the services will be agreed upon by both parties and charges will be applicable according to that date.</li><br>
        <li>A monthly report of performance services will be given to the clients.</li><br>
        <li>Either party may not cancel or fully transfer the service responsibilities to another service vendor before a prior notice of at least 10 <br> business days.</li><br>
        <li><b>Marketing</b> reserves the right to subcontract a third party service provider for some of the service tasks.</li><br>
        <li>A person who is not a party to the Contract shall not have any rights under or in connection with it.</li>
    </ul>
    <h1 class="pay">Payment</h1>
    <ul class="ord">
        <li>If clients avail any monthly service package of <b>Marketing</b> then they are obliged to pay a full chargeable amount prior to the commencement <br> of the work.</li><br>
        <li>If <b>Marketing</b> and the client agree on a fixed quote regarding any services then they are liable to pay 50% of the billable amount in advance,<br> prior to the commencement of the work.</li><br>
        <li> The remaining 50% of the payment will have to be made within 7 days of the start date of the services.</li><br>
        <li> <b>Marketing</b>  shall invoice the clients monthly, in advance.</li><br>
        <li>Also, if the clients do not pay a monthly invoice when it is due, <b>Marketing</b> shall terminate the services immediately. In this case, we will <br>not be liable to issue a 10 day prior notice.
        </li>
    </ul>
    <h1 class="abi">Liability</h1>
    <ul class="ab">
        <li> <b>Marketing</b>will not be liable for any indirect or consequential losses due to delay in obligated service deliverables, where the delay<br> is because of natural or ungovernable causes.</li><br>
        <li>The clients will defend, cover and hold <b>Marketing</b> harmless from and against any and all claims, losses, liabilities and expenses  related <br>to the services provided by <b>Marketing</b> to the clients under this agreement, including without limitation claims made by third parties<br>  related to any false advertising claims, liability claims for products or services sold by the client, claims for patent, copyright or trademark <br> infringement, claims due to disruption or malfunction of services provided, submitted by you for publication  by <b>Marketing</b> .</li><br>
        <li>Due to the nature of digital media, any content/information given by the clients to <b>Marketing</b> for publication will be accessible <br>by the public as soon as the publication is carried out.  will not be responsible for screening the material and any damages or<br> losses of profit, goodwill or any business asset due to the nature of content being publicized.
        </ul>
    <h1 class="wav">Waiver</h1>
    <ul class="wa">
        <li>If at any time during the term of a service contract, we fail to insist upon the strict performance of any of your obligations under the service<br> contract or any of these terms and conditions, then this will not automatically free of you from any of the obligations mentioned in<br>  the terms and conditions and will not constitute a waiver.</li><br>
        <li>Any waiver of term and conditioned will be valid officially only if it is communicated to you in writing.</li>
    </ul>
    <h1 class="pri">Privacy</h1>
    <h1 class="rig">Rights</h1>
    <ul class="pr">
        <li>Information, like name, email, contact number, website URL that the clients provide us by filling the contact form will be kept confidential <br> and not be exposed to a third party, without their prior consent. However, the information will be made privy to the employees of <b> Marketing</b> .</li><br>
        <li><b> Marketing</b> will take reasonable precautions to prevent the loss, misuse or alteration of your personal information.</li><br>
        <li>The transfer of data over the internet is inherently insecure, and any kind of security in this regard cannot be guaranteed by <b> Marketing</b> .</li><br>
        <li>Although, we use SSL encrypted technology for making any kind of money transaction to ensure maximum security against online theft  and<br> fraud.</li><br>
        <li>Cookies are used to track the browsing information/preferences of web users and we may use Cookies to gather statistical data about your <br> browsing pattern for optimizing our site.</li><br>
        <li>Some of the third party advertisers who have their ad links on our website may also use Cookies to gather statistical information about you. However, in no way Cookies give access to any of your personal information either to us or third party entity.</li><br>
         </ul>
    <p class="star">* <b>Marketing reserves the right to modify the above terms and conditions at any point of time, including the time of an ongoing contract and <br> changes in the terms and condition will be notified to the clients through company email * </b></p><br><br><br>
    <form class="form">
        <h1 class="ser">SERVICES</h1><br>
        <a href="#" class="dig"><b>DIGITAL MEDIA </b></a>
        <a href="#" class="vice"><b>PERFORMANCE SERVICES</b> </a><br><br>
        <a href="#" class="res">Data Response</a>
        <a href="#" class="seo">SEO</a><br><br>
        <a href="#" class="dat">Data Advertising</a>
        <a href="#" class="pay">Pay Per Click Advertising</a><br><br>
        <a href="#" class="ret">Retail Marketing</a>
        <a href="#" class="soc">Social Media Strategy</a><br><br>
        <a href="#" class="ad">Ad Channels</a>
        <a href="#" class="web">Web Analytics</a><br><br>
        <a href="#" class="rea">Real Time Bidding</a>
        <a href="#" class="mob">Mobile Strategy</a><br><br>
        <a href="#" class="loc">Location Based Marketing</a>
        <a href="#" class="use">User Experience</a><br><br>
        <a href="#" class="geo">Geo-Trageted PPC</a>
        <a href="#" class="aff">Affiliate Marketing</a><br><br>
        <a href="#" class="cre">Creative Services</a>
        <a href="#" class="mail">E-Mail Marketing</a><br><br><br><br>
        <a href="#" class="sol"><b> SOLUTIONS BY BUSINESS</b></a>
        <h1 class="vis"> <b>VISIT US</b></h1><br>
        <a href="#" class="agen">Ad Agency</a><br><br>
        <a href="#" class="vert">Advertiser</a><br><br>
        <a href="#" class="tail">Retailer</a><br><br>
        <a href="#" class="pub">Publisher</a><br><br>
        <a href="#" class="cmr">CMR</a><br><br>
        <a href="#" class="b2b">B2B Marketer</a><br><br>
        <a href="#" class="all">All Brands</a><br><br>
        <p class="can"><b>Canada </b> <span class="of1">Office</span> <br><br> 1121 O’Connor Drive, Toronto,<br> Ontario, Canada,<br> Zip Code: M4B 2T5</p><br><br>
        <p class="off"><b>India </b><span class="of1">Office</span><br> <br>1st Floor, Plot 6-7, Rama Park,<br> Dwarka Mor Metro Station,<br> New Delhi, India, <br> Zip Code: 110059</p>
        <img src="dm.jpg" class="age">
    </form>
</body>
</html>
