<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Crumbly Bliss - Christmas Edition</title>
<style>
/* General Body Styling */
body {
    background-color: #eaf2f8; /* Light Snowy Blue */
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    color: #333333; /* Dark Gray for Text */
}

/* Header Styling */
header {
    background-color: #b22222; /* Christmas Red */
    text-align: center;
    padding: 20px 0;
    color: #ffffff; /* White Text */
    font-size: 2.5rem;
    font-weight: bold;
    text-shadow: 2px 2px #800000; /* Dark Red Shadow */
}

/* Article Section Styling */
article {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* Three columns */
    gap: 20px;
    padding: 20px;
}

/* Card Styling */
.cookie-card {
    background-color: #008000; /* Christmas Green */
    border-radius: 15px;
    overflow: hidden;
    text-align: center;
    box-shadow: 0px 6px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    border: 3px solid #b22222; /* Red Border */
}

.cookie-card:hover {
    transform: translateY(-10px);
    box-shadow: 0px 8px 16px rgba(0, 0, 0, 0.2);
}

.cookie-card h1 {
    font-size: 2.5rem;
    margin: 0;
    color: #ffffff;
    padding: 10px 0;
    text-shadow: 1px 1px #006400; /* Dark Green Shadow */
}

.cookie-card p {
    font-size: 1.2rem;
    margin: 0;
    color: #ffffff;
    padding: 10px;
    text-shadow: 1px 1px #006400; /* Dark Green Shadow */
}

/* Image Styling */
.cookie-card img {
    width: 100%;
    height: auto;
    border-bottom: 3px solid #b22222; /* Red Border under image */
    cursor: pointer;
    transition: opacity 0.3s ease;
}

.cookie-card img:hover {
    opacity: 0.8;
}
</style>
</head>
<body>
<header>
    <h2>🎄 Crumbly Bliss - Christmas Edition 🎄</h2>
</header>

<article>
    <!-- $2 Cookie 1 -->
    <div class="cookie-card">
        <h1>$2</h1>
        <p>Classic Chocolate Chip</p>
        <a href="https://www.paypal.com/ncp/payment/PGEEEFZXZN9RW" target="_blank">
            <img src="https://via.placeholder.com/300x200.png?text=Classic+Chocolate+Chip" alt="Classic Chocolate Chip">
        </a>
    </div>
    
    <!-- $2 Cookie 2 -->
    <div class="cookie-card">
        <h1>$2</h1>
        <p>Double Chocolate</p>
        <a href="https://www.paypal.com/ncp/payment/PGEEEFZXZN9RW" target="_blank">
            <img src="https://via.placeholder.com/300x200.png?text=Double+Chocolate" alt="Double Chocolate">
        </a>
    </div>
    
    <!-- $5 Cookie 1 -->
    <div class="cookie-card">
        <h1>$5</h1>
        <p>Oatmeal Raisin</p>
        <a href="https://www.paypal.com/ncp/payment/BPHSFZ7VP3QLU" target="_blank">
            <img src="https://via.placeholder.com/300x200.png?text=Oatmeal+Raisin" alt="Oatmeal Raisin">
        </a>
    </div>
    
    <!-- $5 Cookie 2 -->
    <div class="cookie-card">
        <h1>$5</h1>
        <p>Peanut Butter</p>
        <a href="https://www.paypal.com/ncp/payment/BPHSFZ7VP3QLU" target="_blank">
            <img src="https://via.placeholder.com/300x200.png?text=Peanut+Butter" alt="Peanut Butter">
        </a>
    </div>
    
    <!-- $5 Cookie 3 -->
    <div class="cookie-card">
        <h1>$5</h1>
        <p>Snickerdoodle</p>
        <a href="https://www.paypal.com/ncp/payment/BPHSFZ7VP3QLU" target="_blank">
            <img src="https://via.placeholder.com/300x200.png?text=Snickerdoodle" alt="Snickerdoodle">
        </a>
    </div>
</article>
</body>
</html>
