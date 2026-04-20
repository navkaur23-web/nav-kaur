<img width="185" height="273" alt="restaurant" src="https://github.com/user-attachments/assets/801892ed-4a4f-4256-916f-c31663755a65" /><!DOCTYPE html>
<html>
<head>
    <title>TasteHub Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <h1>TasteHub Restaurant</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#menu">Menu</a>
        <a href="#gallery">Gallery</a>
        <a href="#booking">Booking</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Welcome to TasteHub</h2>
    <p>Delicious Food, Cozy Place</p>
</section>

<section id="menu">
    <h2>Our Menu</h2>
    <img src="restaurant.jpg" alt="Menu" width="300">
</section>

<section id="gallery">
    <h2>Gallery</h2>
    <img src="gallery.jpg" alt="Restaurant Interior">

    <div id="burger">
        <h4>Burger</h4>
        <img src="burger.jpg" alt="Burger">
    </div>
</section>

<section id="booking">
    <h2>Book a Table</h2>
    <form id="bookingForm">
        <input type="text" placeholder="Your Name" required>
        <input type="tel" placeholder="Phone Number" required>
        <input type="date" required>
        <input type="time" required>
        <input type="number" placeholder="No. of People" required>
        <button type="submit">Book Now</button>
    </form>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Email: tastehub@gmail.com</p>
    <p>Phone: 9876543210</p>
</section>

<script src="script.js"></script>

</body>
</html>
