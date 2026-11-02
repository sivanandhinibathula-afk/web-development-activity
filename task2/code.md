<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NutriLife - Healthy Food & Nutrition</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&display=swap" rel="stylesheet">
</head>
<body>

<header>
    <nav class="navbar">
        <h2 class="logo">🥗 NutriLife</h2>
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#categories">Categories</a></li>
            <li><a href="#recipes">Recipes</a></li>
            <li><a href="#mealplans">Meal Plans</a></li>
            <li><a href="#tips">Healthy Tips</a></li>
        </ul>
        <a href="#recipes" class="nav-btn">Explore Food</a>
    </nav>
</header>

<section class="hero" id="home">
    <div class="hero-content">
        <p class="tagline">EAT HEALTHY, LIVE BETTER</p>
        <h1>Good Food.<br><span>Good Health.</span><br>Good Life.</h1>
        <p>
            Discover delicious healthy recipes, balanced meal plans,
            and simple nutrition tips for a better lifestyle.
        </p>
        <a href="#recipes" class="btn">Explore Recipes →</a>
    </div>
    <div class="hero-image">
        <img src="https://images.unsplash.com/photo-1512621776951-a57141f2eefd?w=900" alt="Healthy vegetable salad">
    </div>
</section>

<section class="stats">
    <div><h2>50+</h2><p>Healthy Recipes</p></div>
    <div><h2>20+</h2><p>Meal Plans</p></div>
    <div><h2>100%</h2><p>Healthy Choices</p></div>
    <div><h2>24/7</h2><p>Nutrition Tips</p></div>
</section>

<section class="section" id="categories">
    <p class="subtitle">EXPLORE FOOD</p>
    <h2 class="section-title">Food Categories</h2>
    <div class="category-grid">
        <div class="category-card">
            <span>🥗</span><h3>Salads</h3>
        </div>
        <div class="category-card">
            <span>🍎</span><h3>Fruits</h3>
        </div>
        <div class="category-card">
            <span>🥦</span><h3>Vegetables</h3>
        </div>
        <div class="category-card">
            <span>🥑</span><h3>Healthy Fats</h3>
        </div>
        <div class="category-card">
            <span>🥜</span><h3>Protein</h3>
        </div>
        <div class="category-card">
            <span>🌾</span><h3>Whole Grains</h3>
        </div>
    </div>
</section>

<section class="section recipes-section" id="recipes">
    <p class="subtitle">TASTY AND HEALTHY</p>
    <h2 class="section-title">Popular Healthy Recipes</h2>

    <div class="recipe-grid">
        <div class="recipe-card">
            <img src="https://images.unsplash.com/photo-1512621776951-a57141f2eefd?w=600" alt="Vegetable salad">
            <div class="recipe-info">
                <h3>Fresh Green Salad</h3>
                <p>Fresh vegetables with olive oil and lemon dressing.</p>
                <div class="recipe-details">
                    <span>🔥 180 kcal</span>
                    <span>⏱ 15 min</span>
                </div>
                <button onclick="showRecipe('salad')">View Recipe</button>
            </div>
        </div>

        <div class="recipe-card">
            <img src="https://images.unsplash.com/photo-1490645935967-10de6ba17061?w=600" alt="Healthy breakfast bowl">
            <div class="recipe-info">
                <h3>Healthy Breakfast Bowl</h3>
                <p>Oats, fresh fruits, nuts, and natural yogurt.</p>
                <div class="recipe-details">
                    <span>🔥 320 kcal</span>
                    <span>⏱ 10 min</span>
                </div>
                <button onclick="showRecipe('oats')">View Recipe</button>
            </div>
        </div>

        <div class="recipe-card">
            <img src="https://images.unsplash.com/photo-1547592180-85f173990554?w=600" alt="Healthy vegetable soup">
            <div class="recipe-info">
                <h3>Vegetable Soup</h3>
                <p>A nutritious soup made with fresh vegetables.</p>
                <div class="recipe-details">
                    <span>🔥 150 kcal</span>
                    <span>⏱ 25 min</span>
                </div>
                <button onclick="showRecipe('soup')">View Recipe</button>
            </div>
        </div>
    </div>
</section>

<section class="meal-section section" id="mealplans">
    <p class="subtitle">PLAN YOUR DAY</p>
    <h2 class="section-title">Daily Healthy Meal Plan</h2>

    <div class="meal-grid">
        <div class="meal-card">
            <span>🌅</span>
            <h3>Breakfast</h3>
            <p>Oatmeal, banana, almonds and milk.</p>
            <h4>350 Calories</h4>
        </div>
        <div class="meal-card">
            <span>☀️</span>
            <h3>Lunch</h3>
            <p>Brown rice, dal, vegetables and salad.</p>
            <h4>500 Calories</h4>
        </div>
        <div class="meal-card">
            <span>🍎</span>
            <h3>Evening Snack</h3>
            <p>Fresh fruit and a handful of nuts.</p>
            <h4>180 Calories</h4>
        </div>
        <div class="meal-card">
            <span>🌙</span>
            <h3>Dinner</h3>
            <p>Vegetable soup and whole wheat roti.</p>
            <h4>400 Calories</h4>
        </div>
    </div>
</section>

<section class="ingredients section">
    <div class="ingredient-image">
        <img src="https://images.unsplash.com/photo-1540420773420-3366772f4999?w=800" alt="Fresh healthy ingredients">
    </div>
    <div class="ingredient-content">
        <p class="subtitle">FRESH AND NATURAL</p>
        <h2>Healthy Ingredients for Your Body</h2>
        <p>Choose fresh and nutritious ingredients to support a balanced diet.</p>
        <ul>
            <li>🥦 Broccoli – Vitamins and fiber</li>
            <li>🥑 Avocado – Healthy fats</li>
            <li>🍎 Apples – Fiber and antioxidants</li>
            <li>🥜 Almonds – Protein and minerals</li>
            <li>🌾 Oats – Whole grain energy</li>
            <li>🥕 Carrots – Vitamin A</li>
        </ul>
    </div>
</section>

<section class="tips-section section" id="tips">
    <p class="subtitle">HEALTHY LIFESTYLE</p>
    <h2 class="section-title">Healthy Eating Tips</h2>

    <div class="tips-grid">
        <div class="tip-card">
            <span>💧</span>
            <h3>Drink More Water</h3>
            <p>Stay hydrated throughout the day.</p>
        </div>
        <div class="tip-card">
            <span>🥗</span>
            <h3>Eat More Vegetables</h3>
            <p>Include different vegetables in your meals.</p>
        </div>
        <div class="tip-card">
            <span>🍬</span>
            <h3>Reduce Added Sugar</h3>
            <p>Limit sugary drinks and processed foods.</p>
        </div>
        <div class="tip-card">
            <span>🏃</span>
            <h3>Stay Active</h3>
            <p>Exercise regularly and maintain a healthy routine.</p>
        </div>
    </div>
</section>

<section class="newsletter">
    <h2>Start Your Healthy Journey Today!</h2>
    <p>Eat better, feel better, and live a healthier life.</p>
    <a href="#recipes" class="btn">Discover Healthy Food</a>
</section>

<footer>
    <h2>🥗 NutriLife</h2>
    <p>Healthy Food | Healthy Mind | Healthy Life</p>
    <p>© 2026 NutriLife. All Rights Reserved.</p>
</footer>

<div id="recipeModal" class="modal">
    <div class="modal-content">
        <span class="close" onclick="closeRecipe()">&times;</span>
        <h2 id="recipeTitle"></h2>
        <p id="recipeDescription"></p>
        <h3>Ingredients</h3>
        <ul id="recipeIngredients"></ul>
        <h3>Preparation</h3>
        <p id="recipeSteps"></p>
    </div>
</div>

<script src="script.js"></script>
</body>
</html>

    

