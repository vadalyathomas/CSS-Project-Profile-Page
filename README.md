<html>
<head>
  <title>John Doe's Profile</title>
</head>
<body>
  <div>
  <center>
  <ul id="profile">
    <center><img src="https://blob.sololearn.com/courses/ava.png"></center>
    <h2>John Doe</h2>
    <div style="padding-right: 22px;"><pre><p>🇺🇸USA</p></pre></div>
    <li>25 Followers</li>
    <li>20 Following</li>
    <li>⭐️1581 XP</li>
  </ul>
  </center>
  </div>
  <div id="streak">Streak 
    <ul>
      <div style="color: #00CC00;">
      <li class="active-day">M</li>
      <li class="active-day">T</li>
      <li class="active-day">W</li>
      <li class="inactive-day">T</li>
      <li class="inactive-day">F</li>
      <li class="inactive-day">S</li>
      <li class="inactive-day">S</li>
    </ul>
    <br>
    <p>Current Streak: 3</p>
    <br>
    <p>Longest Streak: 16</p>
  </div>

<!-- CSS styling -->
<style> 
  body {
    background-color: darkslategrey;
    max-width: 1500px;
    font-family: Arial, sans-serif;
  }       

  div p, div ul h2 {
    text-align: center;
    max-width: 1500px;
    color: white;  
  }  
  #profile {
    color: white; 
  }                 
  ul, li {
    display: inline-block;
    text-align: center;
    max-width: 1500px;
  }

  .active-day {
  animation-name: pulse;
  animation-duration: 2s;
  animation-iteration-count: infinite; 
  }    
   
</body>
</style>
</html>

<!---- Css styling section--->
<style>
    .active-day {
    text-align: center;
    display: inline-block;
 }
    .inactive-day {
    text-align: center;
    display: inline-block;
    color: #CCCCCC;
 }
    #streak {
    text-align: center;
    max-width: 5000px;
    text-indent: 17px;
    padding-left: 5px;
    color: #676767;
    list-style-type: none;
    background-color: #FFFFFF;
    border-radius: 5px;
    padding-top: 10px;
    margin: 5px;
    padding: 5px;
 } 
    #profile{
    color:  #FFFFFF;
    list-style-type: none;
    display: inline;
    margin: 15px;
 }
    #streak p {
    color: #676767;
    display: inline;
    margin: 10px;
    line-height: 22px;
    }

    @keyframes pulse {
    50% {transform: scale(1); color: #00cc00;}
    100% {transform: scale(2);}
    120% {transform: scale(1);}
    100% {transform: scale(2);}
    }
</style>  
