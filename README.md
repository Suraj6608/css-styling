<html>
    <head>
        <title>WEBDEV CREATIONS</title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
    </head>
    <body>
           <header>
               <div class="main">
                   <ul>
                       <li><a href="#">Home</a> </li>
                       <li><a href="#">Services</a> </li>
                       <li><a href="#">Gallery</a> </li>
                       <li><a href="#">About</a> </li>
                       <li><a href="#">Contact</a> </li>
                   </ul>
                   </div>
                   <div class="title">
                       <h1>WEBDEV CREATIONS</h1>>
                   </div>
                   <div class="button">
                       <a href="#" class="btn">WATCH VIDEO</a>
                       <a href="#" class="btn">LEARN MORE</a>
           </header>
    </body>
</html>
  
  *{
    margin: 0;
    padding: 0;

}

header{
    background-image: url(../11.jpg);
    height: 100vh;
    background-size: cover;
    background-position: center;
}

ul{
    float: right;
    list-style-type: none;
    margin-top: 25px;
}


ul li{
    display: inline-block; 
}

ul li a{
    text-decoration: none;
    color: black;
    padding: 5px 20px;
    border: 1px solid transparent;
    transition: 0.6s ease;
}

ul li a:hover{
    background-color: white;
    color: #000;
}
.title{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
}
.title h1{
    color: black;
    font-size: 50px;
}

.button{
    position: absolute;
    top: 65%;
    left: 50%;
    transform: translate(-50%,-50%);
}
.btn{
    border: 1px solid #fff;
    padding: 10px 30px;
    color: white;
    text-decoration: none;
}
.btn:hover{
    background-color: white;
    color: #000;
    transition: 0.6S ease;
}





