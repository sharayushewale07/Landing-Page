<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recipe Sharing Platform</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #FFF8F0;
            color: #333;
        }
        header {
            background-color: #FF6F61;
            padding: 20px;
            text-align: center;
            color: #fff;
            font-size: 3rem;
            letter-spacing: 1px;
            font-weight: bold;
            text-transform: uppercase;
        }
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.7)), url('https://source.unsplash.com/1600x900/?delicious-food') no-repeat center/cover;
            height: 70vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            text-shadow: 3px 3px 8px rgba(0, 0, 0, 0.9);
            text-align: center;
            flex-direction: column;
        }
        .hero h1 {
            font-size: 3rem;
            animation: slide-in 1.5s ease-out;
        }
        .hero p {
            font-size: 1.4rem;
            margin-top: 10px;
            animation: fade-in 2s ease-out;
        }
        @keyframes slide-in {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        @keyframes fade-in {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .container {
            padding: 40px 20px;
        }
        .recipes {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }
        .recipe-card {
            background-color: #fff;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.15);
            overflow: hidden;
            transition: transform 0.3s ease;
        }
        .recipe-card:hover {
            transform: scale(1.05);
        }
        .recipe-card img {
            width: 100%;
            border-bottom: 5px solid #FF6F61;
        }
        .recipe-card h3 {
            padding: 15px;
        }
        .footer {
            background-color: #2C3E50;
            color: #fff;
            text-align: center;
            padding: 15px 0;
        }
    </style>
</head>
<body>
    <header>🍲 Recipe Sharing Platform</header>

    <div class="hero">
        <h1>Cook, Share, Enjoy!</h1>
        <p>Discover mouth-watering recipes, explore global cuisines, and create magic in your kitchen! 🍽️</p>
    </div>

    <div class="container">
        <h2>Featured Recipes</h2>
        <div class="recipes">
            <div class="recipe-card">
                <img src="c:\Users\Sakshi\Downloads\pasta.webp" alt="Pasta">
                <h3>Classic Italian Pasta</h3>
            </div>
            <div class="recipe-card">
                <img src="c:\Users\Sakshi\Downloads\lava cake.jpeg" alt="Cake">
                <h3>Chocolate Lava Cake</h3>
            </div>
            <div class="recipe-card">
                <img src="c:\Users\Sakshi\Downloads\salad.jpg" alt="Salad">
                <h3>Fresh Veggie Salad</h3>
            </div>
            <div class="recipe-card">
                <img src="c:\Users\Sakshi\Downloads\pizza.jpeg" alt="Pizza">
                <h3>Homemade Pizza</h3>
            </div>
            <div class="recipe-card">
                <img src="c:\Users\Sakshi\Downloads\maggie.png" alt="Maggi">
                <h3>Spicy Masala Maggi</h3>
            </div>
            <div class="recipe-card">
                <img src="c:\Users\Sakshi\Downloads\noodles.webp" alt="Noodles">
                <h3>Hot & Spicy Noodles</h3>
            </div>
            <div class="recipe-card">
                <img src="c:\Users\Sakshi\Downloads\manchurian.jpg" alt="Manchurian">
                <h3>Veg Manchurian</h3>
            </div>
            <div class="recipe-card">
                <img src="c:\Users\Sakshi\Downloads\soupe.jpg" alt="Soup">
                <h3>Hot & Sour Soup</h3>
            </div>
            <div class="recipe-card">
                <img src="c:\Users\Sakshi\Downloads\sandwich.jpeg" alt="Sandwich">
                <h3>Grilled Sandwich</h3>
            </div>
            <div class="recipe-card">
                <img src="c:\Users\Sakshi\Downloads\momos.jpeg" alt="MOmos">
                <h3>Momos</h3>
            </div>
        </div>
    </div>

    <div class="footer">
        &copy; 2025 Recipe Sharing Platform | Designed by Sharayu Shewale
    </div>
</body>
</html>
