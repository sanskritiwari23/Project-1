# Project-1
My first Web development project using HTML and CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anu Agency</title>
</head>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="stylesheet" href="css/style.css">
<style>
   body{
    font-family: 'Baloo Bhai 2', cursive;
       color: antiquewhite;
       margin: 0px;
       padding: 0px;
       background: url('https://images.unsplash.com/photo-1538947151057-dfe933d688d1?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8N3x8Ymx1ZXxlbnwwfDB8MHx8&auto=format&fit=crop&w=500&q=60');
       background-repeat: no-repeat;
       background-size: cover;
       background-attachment: fixed;
   }
   .left{
       top: auto;
       position: absolute;
       color: antiquewhite;
       display: inline-block;
   }
   .mid{
       display: inline-block;
       margin-top: auto;
       width: auto;
       display: block;
       color: antiquewhite;
   }
   .right{
       top: 30px;
       position: absolute;
       right:34px;
       color: antiquewhite;
   }
   .navbar{
       text-align: center;
       padding: 18px 24px;
       background-color: rgb(1, 1, 43);
   }
   .navbar li{
       display: inline-block;
       font-size: 20px;
   }
   .navbar li a{
       color: rgb(241, 241, 245);
       text-decoration: none;
       padding: 34px 23px;
   }
   .navbar li a:hover, .navbar li a.active{
       text-decoration: underline;
       color: rgb(131, 170, 248);
   }
   .left{
      font-size: x-small;
      color: rgb(255, 251, 251);
      text-align: center;
   }
   .btn{
       font-family: 'Baloo Bhai', cursive;
       margin: 0px 9px;
       padding: 4px 14px;
       border: 2px solid rgb(90, 72, 255);
       border-radius: 10px;
       cursor: pointer;
   }
   .btn:hover{
       background-color: rgb(187, 184, 184);
   }
   .container{
       border:2px solid rgb(1, 1, 106);
       margin: 80px 80px;
       padding: 65px;
       width: 30%;
       border-radius:20px ;

   }
   .form-group input{
       text-align: center;
       display: block;
       width: 400px;
       padding: 6px;
       border: 2px solid black;
       margin: 10px auto;
       font-size: 15px;
       border-radius: 23px;
       font-family: 'Baloo Bhai', cursive;
   }
   .container h1{
       text-align: center;
   }
   .container button{
       display: block;
       width: 23%;
       margin: 20px auto;
   }
</style>
<body>
    <header class="header">
        <div class="left">
            <!--For logo-->
            <img src="https://cdn.pixabay.com/photo/2020/11/14/19/01/elderly-5743157__340.png" alt="loading" width="60px">
            <div>Anu Agency</div>
        </div>
        <div class="mid">
            <!--for navbar-->
            <ul class="navbar">
                <li><a href="#">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Schemes</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </div>
        <div class="right">
            <!--for buttons-->
            <button class="btn">Feedback</button>
        </div>
    </header>
    <div class="container">
        <h1>Enter your details</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Name">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Name of Shop">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Contact Number">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Address">
            </div>
            <button class="btn">Submit</button>
        </form>
    </div>
</body>
</html>
