# Contacts-App.html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Sign Up</title>
</head>
<body>
    <div>
        <dive>
            <h1>Sign Up</h1>
             <div>
                <p><label for="email">Email Address</label></p>
                <input type="email"id="email"name="email"required autocomplete="off">
             </div>
             <div>
                <p><label for="password">Password</label></p>
                <input type="password"id="password"required>
             </div>
             <div>
               <p><label for="secret">secret</label></p>
               <input type="secret"id="secret"required>
               </div>
              <p><button type="button"id="btn">SignUp Now</button></p>
             <p>Already a member?<a href="login.html">Log in</a></p>
            <div></div>  
        </dive>
    </div>
</body>
</html>
 ADD CSS
   {box-sizing:border-box}
   .container
   {
    padding:16x;
   }
   input[type=text],input[type=password]
   {
    width:100%;
    padding:15px;
    margin:5px 0 22px 0;
    display:inline-block;
    border:none;
    background:#f1f1f1;
   }
   input[type=text]focus,input[type=secret]focus
   {
    background-color:#ddd;
    outline:none;
    }
     hr{
     border:1px solid #f1f1f1;
     margin-bottom:25px;
   }
    .signupbtn{
    background-color:#04AA6D;
    color:white;
    padding:16px 20px;
    margin:8px 0;
    border:none;
    cursor:pointer;
    width:100%;
    opacity:0.9;
   }
   .signupbtn:hover
   {
   opacity:1;
   a{
   color:dodgerblue;
   }
   .log in {
   background-color:#f1f1f1;
   text-align:center;
  }
