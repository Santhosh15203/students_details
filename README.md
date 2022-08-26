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
        <a href="#" class="wrd">Forget  Password?</a>
        <button class="click">Login</button>
        <p class="para">Don't have an account?<a href="#" class="sign">Sign Up</a></p><br>
        <p class="para1">----------------   or connect with  -------------------</p>
        <a href="#" class="google"><i class="fa-brands fa-google"></i>Sign in with  Google+ </a><br><br>
        <a href="#" class="fb"><i class="fa-brands fa-facebook"></i>Sign in with  Facebook</a><br><br>
        <a href="#" class="insta"><i class="fa-brands fa-instagram"></i>Sign in with  Instagram</a>
    

       
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

---------------------------------------------------------------
body{
    background-image: url('image/hostel.jpg');
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
    background: linear-gradient(to right,red,rgb(30, 151, 238));
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
-----------------------------------------
