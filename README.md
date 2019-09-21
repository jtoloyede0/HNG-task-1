# HNG-task-1
Login web page
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial, Helvetica, sans-serif;
background-image: url("img-jpeg.jpg");
padding-top: 5vh;
}
/*form {border: 3px solid #f1f1f1;}*/
* {
  box-sizing: border-box;
}

.container {
  width: 350px;
  height: auto;
  padding: 20px 30px;
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 0 10px 0 #000;
  margin: auto;
}

input[type=text], input[type=password] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
  border-radius: 5px;
}

button {
  background-color: #55ACEE;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  border-radius: 5px;
}

button:hover {
  opacity: 0.8;
}

.cancelbtn {
  width: 40%;
  padding: 10px 18px;
  background-color: #f44336;
  border-radius: 5px;
}

.imgcontainer {
  text-align: center;
  margin: 30px 0 18px 0;
}

img.avatar {
  width: 70%;
  border: 70%;
}

/*.container {
  position: relative;
  border-radius: 5px;
  padding: 20px 0 30px 0;
}*/

.fb {
   border-radius: 5px;
   width: 40%;
   padding: 10px 18px;
   float: left;
  text-align: center;
  background-color: #3B5998;
  color: white;
}

.twitter {
  border-radius: 5px;
  width: 40%;
  padding: 10px 18px;
  float: right;
text-align: center;
  background-color: #55ACEE;
  color: white;
}

.google {
  width: 40%;
  padding: 10px 18px;
  border-radius: 5px;
  display: inline-block;
  background-color: #dd4b39;
  color: white;
  margin: auto;
}

/*.col {
  width: 100%;
  margin: 8px 0;
  padding: 14px 20px;
  margin-top: 6px;
}*/

/* Clear floats after the columns*/



span.psw {
  float: right;
 padding-top: 16px;
}

/* Change styles for span and cancel button on extra small screens */
@media screen and (max-width: 300px) {
  span.psw {
     display: block;
     float: none;
  }
  .cancelbtn {
     width: 100%;
  }
}
</style>
</head>
<body>

 

<form action="/action_page.php">
  <div class="container">
  <div class="imgcontainer">
    <img src="hng-icon.png" alt="Avatar" class="avatar">
  </div>
<h3 style="text-align:center">Login in</h3>
  
    <label for="uname"><b>Username</b></label>
    <input type="text" placeholder="Enter Username" name="uname" required>

    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required>
        
    <button type="submit" class="loginbtn"><a href="index.html"> Login </a> </button>
    <label>
      <input type="checkbox" checked="checked" name="remember"> Remember me
    </label>
  

  <p style="text-align: center"> Don't have an account?<a href="signup.html"> Sign up </a> here </p>
      <p style="text-align:center">Or </p>
      <p style="text-align: center">sign up with social media account</p>
      

      
        <a href="#" class="fb btn">
          <i class="fa fa-facebook fa-fw"></i> Facebook
        </a>
        <a href="#" class="twitter btn">
          <i class="fa fa-twitter fa-fw"></i> Twitter
        </a>
        <a style="text-align: center" href="#" class="google btn">
          <i class="fa fa-google fa-fw" ></i> Google+
        </a>
      
    
  

    
  
  <div style="background-color:#f1f1f1">
    <button type="button" class="cancelbtn">Cancel</button>
    <span class="psw">Forgot <a href="#">password?</a></span>
  </div>
</div>
</form>

</body>
</html> 
