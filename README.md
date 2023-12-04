# Cse326
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="stylesheet" href="assects/css/Home.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foodio</title>
    <style>
        *,::after,::before{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    }
    body{
    margin: 0 100px;
    background-color: #ffeae0;
    }
    .nav{
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 30px 0;
    }
    .nav .logo h1{
        font-weight: 600;
        font-family: sans-serif;
        color: black;
    }
    .nav .logo b{
        color: #ff511c;
    }
    .nav ul{
        display: flex;
        list-style: none;
    }
    .nav ul li{
        margin-right: 30px;
    }
    .nav ul li a{
        text-decoration: none;
        color: black;
        font-weight: 500;
        font-family: sans-serif;
        font-size: 17px;
    }
    .nav ul .active::after{
        content: '';
        width: 50%;
        height: 3px;
        background-color: #ff511c;
        display: flex;
        position: relative;
        margin: 10px;
        
    }
    input{
        padding: 10px 20px;
        cursor: pointer;
        font-weight: 600;
    }
    .signin{
        background: transparent;
        border: none;
    }
    .signup{
        background-color: #ff511c;
        color: #ffffff;
        outline: none;
        border: none;
        border-radius: 5px;
        
    }
    .content{
        display: grid;
        grid-template-columns: 50% auto;
        gap: 30px;
        margin-top: 100px;
        align-items: center;
        justify-content: space-between;
        width: 100%;
    }
    .content .content-left{
        display: block;
        width: 100%;
    }
    .content .content-left .info{
        max-width: 100%;
        display: flex;
        flex-direction: column;
    }
    .content .content-left .info h2{
        font-size: 60px;
        font-family: sans-serif;
        margin-bottom: 30px;
    }
    .content .content-left button{
        padding: 10px 23px;
        background-color: #ff511c;
        color: #ffffff;
        border-radius: 5p;
        border: none;
        cursor: pointer;
    }
    .container {
      display: flex;
      align-items: center; 
      padding-left: 15px;
      margin: 5%;
    }
    img
    {
      margin-left: 20px ;
      margin-right: 20px;
      padding: 4%;
      padding-right: 2px;
    }
    footer {
        background-color: #ff511c
        ;
        padding: 20px 0;
        text-align: center;
        color: white;
    }
    button {
    padding: 10px 23px;
    background-color: #ff511c;
    color: #ffffff;
    border-radius: 5p;
    border: none;
    cursor: pointer;
    margin: 3%;
    margin-left: 70%;
    margin-bottom: 4%;
  }
  a{
    color: white;
  }
  .container a{
    color: black;
  }
    
    
    
    
    </style>
</head>
<body>
    <section class="menu">
        <div class="nav">
            <div class="logo"><h1>Food<b>io</b></h1></div>  
            <ul>
                <li><a class="active">Home</a></li>
                <li><a href="index.html">Menu</a></li>
                <li><a href="cart.html">Cart</a></li>
                <li><a href="Help.html">Help</a></li>
                <li><a href="About.html">About Us</a></li>
            </ul>
            <div class="signin">
            <button><a href="sign.html">signin</a></button>
            </div>
        </div>
    </section>
    <section class="grid">
        <div class="content">
            <div class="content-left">
                <div class="info">
                    <h2>Order you best<br>Food anytime</h2>
                </div>
                <button><a href="index.html">Explore Food</a></button>
    </section>
    <div class="container">
        <img src="assects/img/food1.jpeg" width="180px" height="200px" alt="Picture of manchurian">
        <a href="index.html"><p>Food1</p></a>
    
        <img src="assects/img/food2.jpeg" width="180px" height="200px"  alt="Picture of fried rice">
        <a href="index.html"><p>Food2</p></a>
    
        <img src="assects/img/food3.jpeg" width="180px" height="200px" alt="Picture of biriyani">
        <a href="index.html"><p>Food3</p></a>
        </div>
    </body>
    <footer>
        <p>&copy; 2022 LT FOOD COURT. All rights reserved.</p>
    </footer>
</html>
        
