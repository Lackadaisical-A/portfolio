<!DOCTYPE html>
<html>
  <head>
    <script>

    function checkpassword() {
      var password = document.getElementById("box"); var passwordText = password.value;
        if(passwordText == "susg91012") {
                    return true;
                 }
      
      alert("Wrong password");
      return false;
      
      
    }
    </script>
       
       
    <title>
	Website
  </title>
  <style>
    .image {
      margin: 5px;

       width: 300px;
       float: left;
       border: 4px solid lightblue;



    }
  </style>
  <style>
    .title {
background-color: lightblue; 
 padding: 25px;
height: 100px;
font-size: 36pt;
text-align: center;


    }
  </style>
  <style>
    .bodytext {

width: 60%;
float: left; 
background-color: beige;
font-size: 29px;
   



    }
  </style>
  
  </head>
  <body>

  
<br/>

  	<div class="title">
Welcome to my website!</div>



<div class="bodytext"><p>Hello! Welcome to the website that I created! Here you will find many links and buttons to different projects, accomplishments, and hobbies that I like. Have fun on it!</p>
</div>
<img class="image" src="https://i.imgur.com/vlmUXyk.jpeg">
<div style="float: left;">
<a href="georgecui.com" target="_blank">My website</a>

    <p>Password:<input id="box" type="text"/></p>
    <a href="https://www.georgecui.com" onclick="return checkpassword();">Click This</a>
</div>
  </body>

</html>
