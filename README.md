<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Home Rentals</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #343a40;
            color: white;
            padding: 10px 20px;
        }
        header h1 {
            margin: 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }
        .hero {
            background-image: url('https://github.com/ProfesseurEben/Dapper-Rentals-/blob/main/a.jpg?raw=true');
            background-size: cover;
            background-position: center;
            height: 60vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            position: relative;
        }
        .hero h2 {
            font-size: 3em;
            margin: 0;
        }
        .hero p {
            font-size: 1.5em;
            margin: 10px 0;
        }
        .cta-button {
            padding: 10px 20px;
            background-color: #dc3545;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
        }
        .content {
            padding: 20px;
            text-align: center;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }
        .card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            margin: 10px;
            width: 300px;
            text-align: center;
            overflow: hidden;
        }
        .card img {
            width: 100%;
            height: auto;
        }
        .card h3 {
            margin: 10px 0;
            font-size: 1.5em;
        }
        .card p {
            padding: 0 10px 10px;
            color: #555;
        }
    </style>
</head>
<body>

<header>
    <h1>Your Home Rentals</h1>
    <nav>
        <a href="#catalog">Catalog</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
        <a href="#book" class="cta-button">Book Now</a>
    </nav>
</header>

<div class="hero">
    <div>
        <h2>Elegant Rentals for Every Occasion</h2>
        <p>Discover Rwanda's premier destination for wedding suits, traditional outfits, and ceremonial items.</p>
        <a href="#collection" class="cta-button">Browse Collection</a>
    </div>
</div>

<div class="content">
    <h2>Welcome to Your Home Rentals</h2>
    <p>Professional quality, delivered to your doorstep.</p>
</div>

<h2>Our Offerings</h2>

<div class="container">

<div class="card">
        <img src="https://github.com/ProfesseurEben/Dapper-Rentals-/blob/main/b.jpg?raw=true" alt="Wedding Suits">
        <h3>Wedding Suits</h3>
        <p>Stylish and elegant suits for your special day.</p>
    </div>

<div class="card">
        <img src="https://github.com/ProfesseurEben/Dapper-Rentals-/blob/main/c.jpg?raw=true" alt="Bride Dresses">
        <h3>Bride Dresses</h3>
        <p>Stylish and elegant bride dresses for your special day.</p>
    </div>

<div class="card">
        <img src="https://github.com/ProfesseurEben/Dapper-Rentals-/blob/main/d.jpg?raw=true" alt="Traditional Outfits">
        <h3>Traditional Outfits</h3>
        <p>Authentic Rwandan cultural attire.</p>
    </div>

<div class="card">
        <img src="https://github.com/ProfesseurEben/Dapper-Rentals-/blob/main/Suits.png?raw=true" alt="Traditional Outfits for Men">
        <h3>Men's Suits</h3>
        <p>Stylish and elegant men's suits for your special day.</p>
    </div>

<div class="card">
        <img src="https://github.com/ProfesseurEben/Dapper-Rentals-/blob/main/h.jpg?raw=true" alt="Traditional Outfits for Women">
        <h3>Women's Dresses</h3>
        <p>Stylish and elegant women's dresses for your special day.</p>
    </div>

<div class="card">
        <img src="https://github.com/ProfesseurEben/Dapper-Rentals-/blob/main/f.png?raw=true" alt="Accessories">
        <h3>Accessories</h3>
        <p>Complete your look with our range of accessories.</p>
    </div>

</div>

<h2>Why Choose Us?</h2>
<ul>
    <li><strong>Fully Digital Experience:</strong> Browse, book, and pay online without visiting physical stores.</li>
    <li><strong>Doorstep Delivery:</strong> Enjoy professional delivery service across Rwanda, ensuring timely arrivals.</li>
    <li><strong>Quality Guarantee:</strong> All items are maintained to the highest standards.</li>
    <li><strong>Cultural Pride:</strong> Celebrate Rwandan traditions with pride.</li>
    <li><strong>Affordable Luxury:</strong> High-end fashion accessible without breaking the bank.</li>
    <li><strong>Friendly Support:</strong> Our dedicated team is here to help you find the perfect outfit for any occasion.</li>
</ul>

<h2>What Our Clients Say</h2>
<p>Real stories from satisfied customers who trusted Dapper Rentals for their special moments.</p>

<h2>Get Started</h2>
<p>Join hundreds of happy customers and book your perfect outfit today!</p>
<ul>
    <li><a href="#collection">Browse Collection</a></li>
    <li><a href="#book">Start Booking</a></li>
</ul>

<hr>

<h3>Contact Us</h3>
<p>Email: hello@dapperrentals.rw</p>
<p>Phone: +250 123 456 789</p>

<h3>Quick Links</h3>
<ul>
    <li>Browse Catalog</li>
    <li>Our Services</li>
    <li>About Us</li>
</ul>

<h3>Categories</h3>
<ul>
    <li>Wedding Suits</li>
    <li>Women's Dresses</li>
    <li>Traditional Outfits</li>
    <li>Accessories</li>
</ul>

<footer>
    <p>Dapper Rentals</p>
    <p>Rwanda's trusted platform for elegant fashion and ceremonial rentals.</p>
    <p>© 2024 Dapper Rentals. All rights reserved. Making fashion accessible to all.</p>
</footer>

</body>
</html>
