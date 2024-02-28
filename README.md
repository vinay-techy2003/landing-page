# HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title>landingpage</title>
</head>
<body>
   <div class="container">
    <div id="nav" >
      <ul type="none">
        <li>contactus</li>
        <li>about</li>
        <li>home</li>
        <img src="logo1.jpeg" alt="" class="logo">
      </ul>
    </div>
    <div class="content">
      <h1>welcome to our page</h1> 
      <p>
        let's explore  all over the world
      </p>
      <button class="btn">sign up</button>
       </div>
   </div>
   </div>
  </body>
</body>
</html>
#CSS
*{
    margin: 0;
    padding: 0;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.container{
    width: 1250px;
    height: 550px;
    background-image:url("img.jpg");
    background-position: center;
    background-size:cover;
}
#nav{
    color: hsl(252, 25%, 60%);
    width: 100%;
    height: 100px;
    align-items: center; 
    
}
#nav li{
            float: right;
            margin: 30px;
            border:2px solid red;
            border-radius: 200px;
            width: 100px;
            background-color:hsl(68, 95%, 56%);
            padding: 14px;
            font-size:28px;
            /* position: relative;*/
        }
.content {
    width: 100%;
    position: absolute;
    top: 50%;
    text-align: center;
    color: rgb(129, 13, 13);
}
.content h1{
    font-size: 80px;
    margin-top: 0%;
}
.content p{
    margin: 20px auto;
    font-weight: 100;
    line-height: 20px;
    font-size: 40px;
    color: red;
}
.logo{
    height: 250px;
    width: 300px;
    left: 30px;
}
.btn{
    height:40px;
    width: 90px;
    font-size:20px;
    color: brown;
    background-color: aquamarine;
    border-radius: 190px;
}
li:hover{
    color: blue;
}
h1:hover{
    color: white;
}
