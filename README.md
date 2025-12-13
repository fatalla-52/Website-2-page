<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Milk Tea Recipe Layout</title>
    <style>
      * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
        }

       body {
        font-family: Arial, Helvetica, sans-serif;
        background-color: #e0e0d1; 
        line-height: 1.6;
        padding: 20px;
        }

      .container {
        max-width: 1200px;
        margin: 0 auto;
        background: #c7c1a5
        padding: 15px;
        border-bottom: 5px solid black
        }

       header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding-bottom: 10px;
        }

       header h1 {
        font-size: 40px;
        color: #333;
        font-family: bold;
        }
        
      .nav {
        padding: 15px 30px;
        display: flex;
        justify-content: flex-end;
        font-weight: bold;
        gap: 25px;
      }

      .content-wrapper {
        display: flex;
        flex-wrap: wrap;
        gap: 20px; 
        margin-top: 20px;
        }

      .column {
        flex: 1;
        min-width: 280px; 
        }

      h2 {
        font-size: 1.1rem;
        margin-bottom: 0.5rem;
        color: #555;
        }

      ul {
        padding: 5px 0;
        border-bottom: 1px solid #eee;
        font-size: 25px;
        }

     @media (max-width: 768px) {
      .content-wrapper {
        flex-direction: column;
            }
      .container {
        padding: 10px;
            }
        }
    </style>
</head>
<body>
      <nav>
        <a href="#">Home</a>
        <a href="#">Learn</a>
        <a href="#">Contact</a>
      </nav>
      
   <div class="container">
     
   <header>
     <h1>Equipment and ingredients for making milktea</h1>
        </header>
        
  <main class="content-wrapper">
     <section class="column">
  <div class="equipment.jpg" alt="Equipment">
                </div>
       <ul>
        <p>1. Bar spoon small</p>
        <p>2. Pearl Scooper</p>
        <p>3. Coffee spoon big</p>
        <p>4. Clear jigger small</p>
        <p>5. Clear cocktail shaker 350ml</p>
       </ul>
       </section>

    <section class="column">
        <div class="bubble-tea-boba.jpg">
         </div>
       <ul>
        <p>1. Black Tea</p>
        <p>2. Brown Sugar</p>
        <p>3. Milk</p>
        <p>4. Tapioca balls</p>
        <p>5. Water</p>
        <p>6. Ice</p>
      </ul>
      </section>
            <section class="column">
                <div class="Ingredients.jpg" alt="Ingredients">
                </div>
            </section>
        </main>
    </div>
</body>
</html>
