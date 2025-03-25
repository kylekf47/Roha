
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Roha Burger, Pizza & Juice Menu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 20px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        section {
            padding: 20px;
            background-color: white;
            margin: 10px 0;
        }
        .card-container {
            display: grid;
            grid-template-columns: repeat(1, 1fr); /* Default for mobile: single column */
            gap: 20px;
            justify-items: center;
        }
        .card {
            background-color: #fff;
            width: 250px;
            margin: 10px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 15px;
        }
        .card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 8px;
        }
        .card h3 {
            font-size: 20px;
            margin-top: 10px;
        }
        .card p {
            font-size: 16px;
            color: #555;
        }
        .card .price {
            font-size: 18px;
            color: #333;
            font-weight: bold;
            margin-top: 10px;
        }
        .back-to-top {
            text-align: center;
            margin-top: 20px;
        }

        /* Media query for larger screens (tablet, desktop, etc.) */
        @media (min-width: 600px) {
            .card-container {
                grid-template-columns: repeat(2, 1fr); /* 2 columns for tablets */
            }
        }
        @media (min-width: 900px) {
            .card-container {
                grid-template-columns: repeat(3, 1fr); /* 3 columns for desktop */
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Roha Burger, Pizza & Juice Menu</h1>
</header>

<nav>
    <a href="#burgers">🍔 Burgers</a> | 
    <a href="#pizzas">🍕 Pizzas</a> | 
    <a href="#juices">🥤 Juices & Drinks</a> | 
    <a href="#contact">📍 Visit Us</a>
</nav>

<section id="burgers">
    <h2>🍔 BURGERS</h2>
    <div class="card-container">
        <div class="card">
            <img src="burger_image1.jpg" alt="Classic Beef Burger">
            <h3>Classic Beef Burger</h3>
            <p>A juicy beef patty with fresh lettuce, tomatoes, and our special sauce.</p>
            <p class="price">$5.99</p>
        </div>
        <div class="card">
            <img src="burger_image2.jpg" alt="Cheese Burger">
            <h3>Cheese Burger</h3>
            <p>Delicious beef patty topped with melted cheese, lettuce, and pickles.</p>
            <p class="price">$6.99</p>
        </div>
        <div class="card">
            <img src="burger_image3.jpg" alt="Roha Special Burger">
            <h3>Roha Special Burger</h3>
            <p>A signature burger with a unique blend of spices and premium toppings.</p>
            <p class="price">$7.99</p>
        </div>
        <div class="card">
            <img src="burger_image4.jpg" alt="Chicken Burger">
            <h3>Chicken Burger</h3>
            <p>Grilled chicken breast with fresh veggies and a creamy sauce.</p>
            <p class="price">$5.99</p>
        </div>
        <div class="card">
            <img src="burger_image5.jpg" alt="Veggie Burger">
            <h3>Veggie Burger</h3>
            <p>Made with a delicious veggie patty, fresh veggies, and a zesty sauce.</p>
            <p class="price">$5.49</p>
        </div>
        <div class="card">
            <img src="burger_image6.jpg" alt="Double Patty Burger">
            <h3>Double Patty Burger</h3>
            <p>For the true burger lovers – two beef patties with extra cheese.</p>
            <p class="price">$8.99</p>
        </div>
    </div>
    <div class="back-to-top">
        <a href="#top">🔝 Back to Top</a>
    </div>
</section>

<section id="pizzas">
    <h2>🍕 PIZZAS</h2>
    <div class="card-container">
        <div class="card">
            <img src="pizza_image1.jpg" alt="Margherita Pizza">
            <h3>Margherita Pizza</h3>
            <p>A classic pizza topped with fresh tomatoes, mozzarella, and basil.</p>
            <p class="price">$9.99</p>
        </div>
        <div class="card">
            <img src="pizza_image2.jpg" alt="Pepperoni Pizza">
            <h3>Pepperoni Pizza</h3>
            <p>Loaded with pepperoni and melted cheese on a fresh tomato base.</p>
            <p class="price">$10.99</p>
        </div>
        <div class="card">
            <img src="pizza_image3.jpg" alt="BBQ Chicken Pizza">
            <h3>BBQ Chicken Pizza</h3>
            <p>Tender BBQ chicken, onions, and a smoky sauce for an amazing flavor.</p>
            <p class="price">$11.99</p>
        </div>
        <div class="card">
            <img src="pizza_image4.jpg" alt="Roha Special Pizza">
            <h3>Roha Special Pizza</h3>
            <p>Our signature pizza with a mix of meats, cheese, and special herbs.</p>
            <p class="price">$12.99</p>
        </div>
        <div class="card">
            <img src="pizza_image5.jpg" alt="Veggie Delight Pizza">
            <h3>Veggie Delight Pizza</h3>
            <p>A perfect mix of vegetables on a tomato base with mozzarella cheese.</p>
            <p class="price">$9.99</p>
        </div>
        <div class="card">
            <img src="pizza_image6.jpg" alt="Meat Lovers Pizza">
            <h3>Meat Lovers Pizza</h3>
            <p>Loaded with all your favorite meats, including pepperoni, sausage, and bacon.</p>
            <p class="price">$13.99</p>
        </div>
    </div>
    <div class="back-to-top">
        <a href="#top">🔝 Back to Top</a>
    </div>
</section>

<section id="juices">
    <h2>🥤 JUICES & DRINKS</h2>
    <div class="card-container">
        <div class="card">
            <img src="juice_image1.jpg" alt="Fresh Orange Juice">
            <h3>Fresh Orange Juice</h3>
            <p>Freshly squeezed oranges, served chilled for a refreshing taste.</p>
            <p class="price">$3.99</p>
        </div>
        <div class="card">
            <img src="juice_image2.jpg" alt="Mango Juice">
            <h3>Mango Juice</h3>
            <p>Sweet and tropical mango juice, perfect for hot days.</p>
            <p class="price">$4.49</p>
        </div>
        <div class="card">
            <img src="juice_image3.jpg" alt="Avocado Juice">
            <h3>Avocado Juice</h3>
            <p>A creamy blend of fresh avocados and a touch of sweetness.</p>
            <p class="price">$4.99</p>
        </div>
        <div class="card">
            <img src="juice_image4.jpg" alt="Mixed Fruit Juice">
            <h3>Mixed Fruit Juice</h3>
            <p>A delicious mix of seasonal fruits in a refreshing juice.</p>
            <p class="price">$5.49</p>
        </div>
        <div class="card">
            <img src="juice_image5.jpg" alt="Soft Drinks">
            <h3>Soft Drinks</h3>
            <p>Choose from a variety of popular soft drinks.</p>
            <p class="price">$1.99</p>
        </div>
        <div class="card">
            <img src="juice_image6.jpg" alt="Bottled Water">
            <h3>Bottled Water</h3>
            <p>Stay hydrated with our refreshing bottled water.</p>
            <p class="price">$0.99</p>
        </div>
  

