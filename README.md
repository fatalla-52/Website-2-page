<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Milktea Materials</title>

<style>
    *{
        margin:0;
        padding:0;
        box-sizing:border-box;
    }

    body{
        background:#c7c0a4;
        font-family: Arial, sans-serif;
        padding:20px;
    }

    h1{
        text-align: left;
        font-size: 28px;
        margin-bottom: 30px;
        font-weight: bold;
    }
    .header{
      margin-right: 20px;
      font-weight: bold;
      text-align: right;
    }
      
    .container{
        max-width:1200px;
        margin:auto;
        display:grid;
        grid-template-columns: repeat(3, 1fr);
        gap:25px;
    }

    .box{
        background:#e8e2ce;
        padding:15px;
        border-radius:8px;
        text-align:center;
    }

    .box img{
        width:100%;
        border-radius:6px;
        margin-bottom:12px;
    }

    ol{
        text-align:left;
        padding-left:18px;
        font-size:16px;
        line-height:1.5;
    }
</style>
</head>
<body> 
   <header>
     <a href="#home">Home</a>
     <a href="#learn">Learn</a>
     <a href="#contact">Contact</a>
   </header>

<h1>Equipment and ingredients for making milktea</h1>

<div class="container">

    <div class="box">
        <img src="equipment.jpg" alt="Equipment">
        <ol>
            <li>Bar spoon small</li>
            <li>Pearl Scooper</li>
            <li>Coffee spoon big</li>
            <li>Clear jigger small</li>
            <li>Clear cocktail shaker 350ml</li>
        </ol>
    </div>

    
    <div class="box">
        <img src="bubble-tea-boba.jpg" alt="Ingredients">
        <ol>
            <li>Black Tea</li>
            <li>Brown Sugar</li>
            <li>Milk</li>
            <li>Tapioca balls</li>
            <li>Water</li>
            <li>Ice</li>
        </ol>
    </div>

    <div class="box">
        <img src="ingredients.jpg" alt="Recipe">
    </div>

</div>

</body>
</html>
