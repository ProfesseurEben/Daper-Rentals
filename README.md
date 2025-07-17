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
            text-align: center;
            position: relative;
        }
        .hero h2 {
            font-size: 3em;
            margin: 0;
            color: #FF4500; /* Change to reddish */
        }
        .hero p {
            font-size: 1.5em;
            margin: 10px 0;
            color: #FF4500; /* Change to reddish */
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
            justify-content: center; /* Center align the cards */
            padding: 20px;
        }
        .card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            margin: 10px;
            width: 300px; /* Fixed width for cards */
            text-align: center;
            overflow: hidden;
            transition: transform 0.3s;
        }
        .card:hover {
            transform: scale(1.05);
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
        .why-choose {
            padding: 20px;
            text-align: center;
        }
        .why-choose ul {
            list-style-type: none;
            padding: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Your Home Rentals</h1>
    <nav>
        <a href="#catalog" id="catalogBtn">Catalog</a>
        <a href="#services" id="servicesBtn">Services</a>
        <a href="#Contact" id="ContactBtn">Contact</a>
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
        <img src="https://github.com/ProfesseurEben/Dapper-Rentals-/blob/main/B.jpg?raw=true" alt="Wedding Suits">
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
        <img src="https://github.com/ProfesseurEben/Dapper-Rentals-/blob/main/Suits.png?raw=true" alt="Men's Suits">
        <h3>Men's Suits</h3>
        <p>Stylish and elegant men's suits for your special day.</p>
    </div>

<div class="card">
        <img src="https://github.com/ProfesseurEben/Dapper-Rentals-/blob/main/h.jpg?raw=true" alt="Women's Dresses">
        <h3>Women's Dresses</h3>
        <p>Stylish and elegant women's dresses for your special day.</p>
    </div>

<div class="card">
        <img src="https://github.com/ProfesseurEben/Dapper-Rentals-/blob/main/f.png?raw=true" alt="Accessories">
        <h3>Accessories</h3>
        <p>Complete your look with our range of accessories.</p>
    </div>

</div>

<div class="why-choose">
    <h2>Why Choose Us?</h2>
    <ul>
        <li><strong>Fully Digital Experience:</strong> Browse, book, and pay online without visiting physical stores.</li>
        <li><strong>Doorstep Delivery:</strong> Enjoy professional delivery service across Rwanda, ensuring timely arrivals.</li>
        <li><strong>Quality Guarantee:</strong> All items are maintained to the highest standards.</li>
        <li><strong>Cultural Pride:</strong> Celebrate Rwandan traditions with pride.</li>
        <li><strong>Affordable Luxury:</strong> High-end fashion accessible without breaking the bank.</li>
        <li><strong>Friendly Support:</strong> Our dedicated team is here to help you find the perfect outfit for any occasion.</li>
    </ul>
</div>

<!-- Modal for Catalog -->
<div id="catalogModal" class="modal">
    <div class="modal-content">
        <span class="close" id="closeCatalog">&times;</span>
        <h2>Catalog</h2>
        <ul>
            <li>1. Imikenyero</li>
            <li>2. Rugabire</li>
            <li>3. Suit</li>
            <li>4. Ibiseke</li>
            <li>5. Inkoni</li>
            <li>6. Ingofero</li>
            <li>7. Amakanzu y' Abakobwa</li>
        </ul>
    </div>
</div>

<!-- Modal for Services -->
<div id="ServicesModal" class="Services">
    <div class="Services-content">
        <span class="close" id="closeServices">&times;</span>
        <h2>Services</h2>
        <ul>
            <li>1. Wedding Decorations</li>
            <li>2. Celemonial Decoration</li>
            <li>3. Doorstep delivery</li>
        </ul>
    </div>
</div>

<!-- Modal for Contact -->
<div id="ContactModal" class="Contact">
    <div class="modal-content">
        <span class="close" id="closeContact">&times;</span>
        <h2>Contact</h2>
        <ul>
            <li>OTHER CONTACTS</li>
            <li>1. Phone: +250 783 217 215</li>
            <li>Email: irebene7@gmail.com</li>
            <li>2. Phone: +250 783 217 215</li>
            <li>Email: irebene7@gmail.com</li>
            <li>3. Phone: +250 783 217 215</li>
            <li>Email: irebene7@gmail.com</li>
        </ul>
    </div>
</div>

<footer>
    <h3>Contact Us</h3>
    <p>Email: irebene7@gmail.com</p>
    <p>Email: irebene77@gmail.com</p>
    <p>Phone: +250 783 217 215</p>
    <p>© 2024 Dapper Rentals. All rights reserved.</p>
</footer>

<script>
    // Get modal elements
    var catalogModal = document.getElementById("catalogModal");
    var servicesModal = document.getElementById("servicesModal");
    var ContactModal = document.getElementById("ContactModal");

    // Get button elements
    var catalogBtn = document.getElementById("catalogBtn");
    var servicesBtn = document.getElementById("servicesBtn");
    var ContactBtn = document.getElementById("ContactBtn");

    // Get close elements
    var closeCatalog = document.getElementById("closeCatalog");
    var closeServices = document.getElementById("closeServices");
    var closeContact = document.getElementById("closeContact");

    // Open catalog modal
    catalogBtn.onclick = function() {
        catalogModal.style.display = "block";
    }

    // Open services modal
    servicesBtn.onclick = function() {
        servicesModal.style.display = "block";
    }

    // Open services modal
    ContactBtn.onclick = function() {
        ContactModal.style.display = "block";
    }
    
    // Close catalog modal
    closeCatalog.onclick = function() {
        catalogModal.style.display = "none";
    }

    // Close services modal
    closeServices.onclick = function() {
        servicesModal.style.display = "none";
    }

    // Close services modal
    closeContact.onclick = function() {
        ContactModal.style.display = "none";
    }
    
    // Close modal when clicking outside of it
    window.onclick = function(event) {
        if (event.target == catalogModal) {
            catalogModal.style.display = "none";
        }
        if (event.target == servicesModal) {
            servicesModal.style.display = "none";
        }
        if (event.target == ContactModal) {
            ContactModal.style.display = "none";
        }
    }
</script>

</body>
</html>
