# firstFile

<!DOCTYPE html>
<html>
<head>
  <title>Create Your Gmail Account</title>
 <link rel="shortcut icon" href="icon.png">
 <link rel="stylesheet" href="16newstyle.css">
 <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
 <script src="20jquery.js"></script>

</head>
<body>
  
<div id="wrapper">
  <div class="inner-wrapper">
    <div class="header">
      <p><img src="logo.png" alt="Google logo" width="90px" height="50px"></p>
    </div>
    <div class="form-tag">
      <div class="form-left">
        <div class="tagline">
          <p>Create your Google Account</p>
          to continue to Gmail
        </div>
        <div class="form">
        <form>
          <div class="form-group">
            <input type="text" name="first" id="first" placeholder="">
            <span id="rfirst"></span>
          </div>
          <div class="form-group">
              <input type="text" name="last" id="last" placeholder="">
              <span id="rlast"></span>
          </div>
          <div class="form-group1">
            <input type="text" name="user" id="user" placeholder="" >
            <span>@gmail.com</span> 
            <sub id="userhide">You can use letters, numbers & periods</sub>
          </div>
          <div class="spanuser">  
            <span id="ruser"></span> 
          </div>
          <div class="form-group">
            <input type="text" name="pass" id="pass" placeholder="">
            <span id="rpass"></span>
          </div>
          <div class="form-group">
            <input type="text" name="cpass" id="cpass" placeholder="">
            <span id="rcpass"></span>
          </div>
          <div class="form-group1">
            <sup id="rcpass"></sup>
          </div>
          <div id="show" >
          </div>
          <div class="Add">
           <p> <a href="javascript:void(0)" onclick="add()">ADD</a></p>
          </div>
          <div class="Add">
           <button id="validate">Next</button>
          </div>
         </form>
        </div>
      </div>
      <div class="form-right">
        <div class="img">
          <p><img src="account.svg" alt="img"></p>
        </div>
        <div class="textline">
          <p>One Account. All of Google<br> working for you.</p>
        </div>
      </div>
    </div>
    <div class="form-buttom">
      <div class="form-group">
            <p style="font-size: 18px;"><a href="#">Sign in instead</a></p>
          </div>
    </div>
  </div>
</div>
<button></button>
</body>
</html>
