# Ex.07 Restaurant Website
# Date:08-11-2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #709962;
            color: #333;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            text-align: center;
            background-color: #444;
        }
        nav a {
            color: white;
            padding: 14px 15px;
            text-decoration: none;
            display: inline-block;
        }
        nav a:hover {
            background-color: #575757;
        }
        .container {
            width: 90%;
            margin: 0 auto;
            padding: 20px;
        }
        .about, .menu, .contact {
            padding: 20px 0;
        }
        .menu-items {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .menu-item {
            background-color: #989898;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            flex-basis: 27%;
            text-align: center;
        }
        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        footer a {
            color: white;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    <h1>Spicy Hut</h1>
    <p>Your favorite place for delicious meals</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
</nav>

<div class="container">
    <!-- Home Section -->
    <section id="home">
        <div class="about">
            <h2>Welcome to Our Restaurant</h2>
            <p>At Spicy Hut, we serve the best food in town with a unique blend of flavors and the finest ingredients. Come and enjoy a memorable dining experience with us!</p>
        </div>
    </section>

    <!-- Menu Section -->
    <section id="menu">
        <div class="menu">
            <h2>Our Menu</h2>
            <div class="menu-items">
                <div class="menu-item">
                    <h3>pizza</h3>
                    <p>Pizza is a popular Italian dish consisting of a round, flat base of dough topped with tomato sauce, cheese, and various other ingredients such as meats, vegetables, and herbs.</p>
                    <p>Rs:199</p>
                    <img src="C:\Users\admin\Downloads\pizza.jpeg">
                </div>
                <div class="menu-item">
                    <h3>Burger</h3>
                    <p>A burger is a classic fast-food dish typically made with a ground beef patty, served in a bun with various toppings such as lettuce, tomato, cheese, pickles, and condiments like.</p>
                    <p>Rs:159</p>
                    <img src="C:\Users\admin\Downloads\burger.jpeg">
                </div>
                <div class="menu-item">
                    <h3>chicken nuggets</h3>
                    <p>Chicken nuggets are bite-sized pieces of chicken, usually breaded and deep-fried, creating a crispy exterior with a tender.Crunch into Joy, One Nugget at a Time! </p>
                    <p>Rs:269</p>
                    <img src="C:\Users\admin\Downloads\chicken nuggets.jpeg">
                </div>
                <div class="menu-item">
                    <h3>Biriyani</h3>
                    <p>Biriyani is a flavorful and aromatic South Asian dish made with rice, meat (such as chicken, beef, lamb, or shrimp), and a blend of spices. </p>
                    <p><Rs:159></p>
                    <img src="C:\Users\admin\Downloads\biriyani.jpeg">
                </div>
                
                <div class="menu-item">
                    <h3>prawn fry</h3>
                    <p>Prawn fry is a flavorful dish made by sautéing prawns in a mix of spices, herbs, and oil, resulting in a crispy, aromatic, and savory dish. </p>
                    <p>Rs:169</p>
                    <img src="C:\Users\admin\Downloads\prawn fry.jpeg">
                </div>
                <div class="menu-item">
                    <h3>paneer roast</h3>
                    <p>Paneer Roast is a flavorful dish made with paneer cubes marinated in a blend of aromatic spices, then roasted to golden perfection. </p>
                    <p>RS:219</p>
                    <img src="C:\Users\admin\Downloads\paneer roast.jpeg">
                </div>
            </div>
        </div>
    </section>
</body>
</html>
about us
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #709962;
            color: #333;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            text-align: center;
            background-color: #444;
        }
        nav a {
            color: white;
            padding: 14px 15px;
            text-decoration: none;
            display: inline-block;
        }
        nav a:hover {
            background-color: #575757;
        }
        .container {
            width: 90%;
            margin: 0 auto;
            padding: 20px;
        }
        .about, .menu, .contact {
            padding: 20px 0;
        }
        .menu-items {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .menu-item {
            background-color: #989898;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            flex-basis: 27%;
            text-align: center;
        }
        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        footer a {
            color: white;
            text-decoration: none;
        }
    </style>
</head>
<section id="menu">
    <div class="container">
    <section id="about">
        <div class="about">
            <h2>About Us</h2>
            <p>Founded in 2000. Our chefs use the finest ingredients and traditional cooking techniques to bring you the best dining experience.</p>
        </div>
    </section>
</div>
</section>
<section id="menu"
><div class="container">
    <section id="contact">
        <div class="contact">
            <h2>Contact Us</h2>
            <p>For reservations, catering inquiries, or general questions, feel free to reach out to us!</p>
            <p>Email: contact@restaurant.com</p>
            <p>Phone: (123) 456-7890</p>
        </div>
    </section>
</div></section>
</html>
```
# OUTPUT:
![Screenshot (49)](https://github.com/user-attachments/assets/25d40cc4-dec0-4497-b79e-35f2e3493719)
![Screenshot (50)](https://github.com/user-attachments/assets/49b963b8-6bc9-4e29-8506-394f8c409d46)
![WhatsApp Image 2024-12-28 at 07 10 14_cbfe99bd](https://github.com/user-attachments/assets/134d73f4-917f-4f2d-be57-f9d32ac74047)
![WhatsApp Image 2024-12-28 at 07 07 56_f0c990aa](https://github.com/user-attachments/assets/aa46e8ce-f606-4cb4-a595-d8f87555eccf)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
