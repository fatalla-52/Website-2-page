<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Milk Tea Page</title>

<style>
    body {
        background: #c6c0a4;
    }

    h2 {
        text-align: left;
        margin-top: 20px;
    }

    .section {
        max-width: 1100px;
        margin: auto;
        padding: 20px;
    }

    .flex {
        display: flex;
        gap: 20px;
        flex-wrap: wrap;
        justify-content: center;
    }
    .item-1 {
        width: 300%; 
        height: 100%;
        border-radius: 6px;
    }
    .item-2 {
        width: 700%;
        height: 500%;
        border-radius: 6px;
    }
    .item-3 {
        width: 700%;
        height: 500%;
        border-radius: 6px;
    }

    ul {
        margin: 10px 0;
        padding-left: 20px;
    }
    .nav {
        padding: 15px;
        display: flex;
        justify-content: flex-end;
        gap: 25px;
    }
    .contact-info {
        margin-bottom: 20px;
        margin: 6px 0;
        font-size: 15px;
    }

    form {
        display: flex;
        flex-direction: column;
        max-width: 400px;
        gap: 15px;
        justify-content: right;
    }

    input, textarea {
        width: 100%;
        padding: 12px;
        border-radius: 8px;
        border: none;
        background: white;
        box-shadow: 4px 4px 0px black;
        font-size: 14px;
    }

    textarea {
        height: 120px;
        resize: none;
    }

    button {
        width: 120px;
        padding: 10px;
        border: none;
        background: #85e6ff;
        font-size: 16px;
        border-radius: 6px;
        cursor: pointer;
        justify-content: right;
    }
</style>
</head>

<body>

<div class="section">
<nav>
    <a href="#">Home</a>
    <a href="#">learn</a>
    <a href="#">contact</a>
</nav>
    

    <h2>Equipment and ingredients for making milktea</h2>

    <div class="flex">

        <div class="item-1">
            <img src="equipment.jpg" alt="Equipment">
            <ul>
                <li>Bar spoon small</li>
                <li>Pearl Scooper</li>
                <li>Coffee spoon big</li>
                <li>Clear jigger small</li>
                <li>Clear cocktail shaker 350ml</li>
            </ul>
        </div>

        <div class="item-2">
            <img src="bubble-tea-boba-1.jpg" alt="">
            <ul>
                <li>Black Tea</li>
                <li>Brown Sugar</li>
                <li>Milk</li>
                <li>Tapioca Balls</li>
                <li>Water</li>
                <li>Ice</li>
            </ul>
        </div>

        <div class="item-3">
            <img src="ingredients.jpg" alt="Recipe">
        </div>
    </div>

    <h2>Contact Us</h2>

    <div class="contact-info">
        <p><strong>Email:</strong> angiefatalla@gmail.com</p>
        <p><strong>Phone No:</strong> 09623428152</p>
        <p><strong>Address:</strong> Sara Smile, 123 Giggle Ave, Richmond, VA 22548</p>
    </div>

    <form>
        <input type="text" placeholder="Full Name:">
        <input type="email" placeholder="Email:">
        <textarea placeholder="Message:"></textarea>
        <button type="submit">Send</button>
    </form>
</div>

</body>
</html>

