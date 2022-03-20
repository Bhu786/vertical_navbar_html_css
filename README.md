#####vertical_navbar with html and css#####


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <nav>
  <ul>
    <li><a href="#"> <i class="fa-solid fa-building"></i>Home  </a></li>
    <li><a href="#" class="active"> About </a></li>
    <li><a href="#">Shop  </a></li>
    <li><a href="#"> Blog </a></li>
    <li><a href="#"> Connect </a></li>
    <li><a href="#">  Contact</a></li>
    <li><a href="#"><i class="fab fa-twitter"></i></a></li>
<!--   icon adding   -->
    
  </ul>
  </nav>
  
</body>
</html>
<!-- vertical navbar -->




#xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx#


nav{
  border:1px solid #333;
  width:50%;
  margin:1rem auto;
/*  auto left right se evenly space or comes into center  */
  padding:1rem;
  background-color:#eee;
}
nav ul{
  list-style-type:none;
  margin:0;
  padding:0;
}


nav a{
  color:#00bff3;
  text-decoration:none;
  font-size:1.5rem;
  
}


*,
*:before,
*:after{
  box-sizing:inherit;
}

body{
  font-family:"Roboto slab ,serif";
  font-weight:400;
  margin:0;
  padding:0;
  font-size:1.2rem;
}

nav a:focus{
  background-color:#f0c808;
  color:black;
}

nav a:hover{
  color: #ff583d;
  font-weight:900;
}

nav li:hover{
  background-color:#f0c808;
/*  background-image:url(path)  */
}

nav li{
  padding:0.5rem 1rem;
}


.active{
  color:#ff583d;
  background-color:#c5e5ed;
  border-bottom:5px solid #00bff3;
  border-top:5px solid #00bff3;

}

.active:hover{
 background-color:red;
}

















