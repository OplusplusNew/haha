<!DOCTYPE html>
<html lang="en">

<style>
  * {
    text-align: center;

    background-color: burlywood;
  }

  h1 {

    border-style: solid;
    text-shadow: 1px 2px 1px white,
    1px 3px 1px black,
    1px 4px 1px black;
    box-shadow: 1px 2px 1px black,
    1px 3px 1px black,
    1px 4px 1px black;
    
    


  }
  h2 {
    display: none;
color:white;
    font-size: 30px;
    text-shadow: 1px 2px 1px whitesmoke,
    1px 3px 1px whitesmoke,
    1px 4px 1px black;
    
    
  }

  form {
    
    text-align: center;
    background-image: url(/cati.jpeg);
    background-size: 12cm;
    border-radius: 30px;
    border-color: white;
    border-style: solid;

    width: 400px;
    height: 513px;
    box-shadow: 9px 9px 7px black;



  }

  ::placeholder {

    color: white;
    font-style: bold;
    font-size: 40px;



  }

h1:hover{

  display: block;
  letter-spacing: 15px;
  color:white;
  transition: 2s;
  
  
}

.pie:hover , .equal:hover , .button:hover{
  color: black;
 transition: 0.4s;
 letter-spacing:3px;
  text-shadow: 1px 2px 1px white;
    box-shadow: 1px 2px 1px floralwhite;
    border-color: white;
    background-color: white;
 
}

.del:hover{
  color: black;
  box-shadow: 1px 2px 1px darkred;
  text-shadow: 1px 2px 1px darkred;
   
    color: red;
    font-style: bold;
    font-size: 25px;
    border-radius: 15px;
    width: 80px;
    height: 70px;
    position: relative;
    background-color: orangered;
    border-color: red;darkred

    
    
}
  .del {
    text-shadow: 1px 2px 1px darkred;
    box-shadow: 1px 2px 1px darkred;
    color: red;
    font-style: bold;
    font-size: 25px;
    border-radius: 15px;
    width: 80px;
    height: 70px;
    position: relative;
    background: transparent;
    border-color: red;
    
    transition: 0.1s;
  }
img:hover + h2{
  
  display:inline-block;
 
  
  
 
  
}
img:hover{
  border-radius: 1px;
  transition: 0.5s;
  width: 90px;
   
  
}

  .display {
margin-top:3px;
margin-bottom: 20px;
    font-size: 40px;
    color: white;
    height: 80px;
    width: 380px;
    border-style: solid;
    border-radius: 30px;
    text-align: center;
    word-spacing: none;
    background: transparent;
    border-color: white;
    box-shadow: 2px 2px 0px white;
  }

  .shh{


    font-size: 50px;
    height: 100vh;
    display: flex;
    justify-content: left ;
    align-items: top;


  }




  .button,
  .equal,
  .pie {

     
    color: white;
    width: 80px;
    height: 70px;

    position: relative;
    font-size: 29px;
    font-style: bold;
    text-align: center;
    
    background: transparent;
    border-radius: 15px;
    border-color: white;
    word-spacing: none;
    transition: 1s;

    text-shadow: 1px 1px 1px white;
    box-shadow: 2px 2px 0px white;



  }


    
  
  img{
    
    
    
    background: cover;
    border: cover;
    border-radius: 50px;
    
    
    
  }
  .imgs{
    
    

    display: flex;
    justify-content: left;
    align-items: top;
    border: none;
    

  }
 
  
</style>

<head>
  
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>OPLUSPLUS</title>

  <!-- HTML -->


  <!-- Custom Styles -->
  <link rel="stylesheet" href="style.css">
</head>

<body>

  <h1>HAYST</h1>
  <div class="imgs">
<img src="/received_3118405335091720.webp" alt="" width="50px"> <h2>Sheshhh..<h2>
<br>

  </div>
  <br>

   
 </nav>
  <div class=shh>

    <form name="calcy">


      <input type="text" class="display" name="display" id="a" placeholder="CALCULATOR">
      <br>


      <input type="button" class="button" value="Clr" onclick="calcy.display.value=''" id="del">
      <input type="button" class="button" value="÷" onclick="calcy.display.value+='/'">
      <input type="button" class="button" value="×" onclick="calcy.display.value+='*'">
      <input type="button" class="del" value="Del" onclick="calcy.display.value= calcy.display.value.slice(0,-1)"> <br>

      <input type="button" class="button" value="7" onclick="calcy.display.value+='7'">
      <input type="button" class="button" value="8" onclick="calcy.display.value+='8'">
      <input type="button" class="button" value="9" onclick="calcy.display.value+='9'">
      <input type="button" class="button" value="-" onclick="calcy.display.value+='-'"><br>

      <input type="button" class="button" value="4" onclick="calcy.display.value+='4'">
      <input type="button" class="button" value="5" onclick="calcy.display.value+='5'">
      <input type="button" class="button" value="6" onclick="calcy.display.value+='6'">
      <input type="button" class="button" value="+" onclick="calcy.display.value+='+'"><br>

      <input type="button" class="button" value="1" onclick="calcy.display.value+='1'">
      <input type="button" class="button" value="2" onclick="calcy.display.value+='2'">
      <input type="button" class="button" value="3" onclick="calcy.display.value+='3'">
      <input type="button" class="button" value="%" onclick="calcy.display.value+='%'"><br>

      <input type="button" class="button" value="." onclick="calcy.display.value+='.'">
      <input type="button" class="button" value="0" onclick="calcy.display.value+='0'">
      <input type="button"  class="equal" value="=" onclick="calcy.display.value= eval(calcy.display.value)" >
      <input type="button" class="pie" value="π" onclick="calcy.display.value +='3.14'">



    </form>
  </div>


</body>

</html>
