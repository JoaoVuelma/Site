HTML:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Cartão</title>
</head>
<body>
<div class="container">
    <div class="card">
        <div class="circle1"><div class="circle2"></div></div><p>L. Alberto Suárez</p>
    <div class="body">
        <div class="circle1"><div class="circle2"></div>  
    </div><p>L. Alberto Suárez</p>
    </div>
    </div>
    <h1>VMcard<p2>&copy;</p2></h1>
</div>
</body>
</html>

CSS:

body{
    background-color: #fff;
    box-sizing: border-box;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    overflow: hidden;
}
.container{
    width: 400px;
    height: 400px;
    position: relative;
}

.card {
    width: 350px;
    height: 200px;
    background-color: #cccccc;
    border-radius: 20px;
    padding: 50px;
    box-shadow: 4px 4px 10px  #000000;

  }
  
  .body {
    width: 350px;
    height: 200px;
    background-color: #333;
    bottom: 0;
    left: 70px;
    border-radius: 20px;
    padding: 50px;
    box-shadow: 4px 4px 10px  #4c00ff;
  }
  
  .circle1 {
    width: 70px;
    height: 70px;
    background-color: #c70c0cc5;
    bottom: 0;
    border-radius: 50%;
    margin-top: -70px;

  }
  .circle1:first-of-type {
    left: 25px
  }
  
  .circle1:last-of-type {
    right: 25px;
  }
  
  
  .circle2 {
    width: 70px;
    height: 70px;
    background-color: #ddba1de1;
    bottom: 0;
    border-radius: 50%;
  }
  
  .circle2:first-of-type {
    left: 25px;
    margin: 50px;
  }
  
  .circle2:last-of-type {
    right: 25px;
  }
  
  p{
    color: beige;
    font-size: 22px;
    text-align: end;
    margin-top: -50px;
    font-family: arial;
  }

  h1 p2 {
    font-size: 13px;
  }

  h1 {
    color: beige;
    margin-left: 80px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  }
  