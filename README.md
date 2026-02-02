<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cover India - Premium Phone Covers Online</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        /* Global Styles */
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background: linear-gradient(135deg, #FF9933 0%, #FFFFFF 50%, #128807 100%); /* Indian tricolor gradient */
            background-attachment: fixed;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        h1, h2, h3 {
            margin: 0;
        }
        a {
            text-decoration: none;
            color: inherit;
        }
        button {
            background: #FF9933;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
            transition: background 0.3s;
        }
        button:hover {
            background: #e67e22;
        }

        /* Header */
        header {
            background: rgba(255, 255, 255, 0.9);
            padding: 10px 0;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .logo {
            font-size: 24px;
            font-weight: 700;
            color: #128807;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }
        nav a {
            font-weight: 500;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #FF9933;
        }
        .search-bar {
            display: flex;
            gap: 10px;
        }
        .search-bar input {
            padding: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        /* Hero */
        .hero {
            background: url('https://via.placeholder.com/1200x400?text=Premium+Phone+Covers') center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            position: relative;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0,0,0,0.5);
        }
        .hero-content {
            position: relative;
            z-index: 1;
        }
        .hero h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 18px;
            margin-bottom: 20px;
        }

        /* Sections */
        section {
            padding: 60px 0;
            background: white;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        .about, .products, .testimonials, .contact {
            text-align: center;
        }
        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .product {
            border: 1px solid #ddd;
            padding: 20px;
            border-radius: 10px;
            transition: transform 0.3s;
        }
        .product:hover {
            transform: translateY(-5px);
        }
        .product img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 5px;
        }
        .testimonials {
            background: #f9f9f9;
        }
        .testimonial {
            margin: 20px 0;
            font-style: italic;
        }
        .contact form {
            max-width: 500px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        .contact input, .contact textarea {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        /* Footer */
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        .social-links a {
            margin: 0 10px;
            font-size: 20px;
        }

        /* Cart Modal */
        .cart-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.8);
            justify-content: center;
            align-items: center;
        }
        .cart-content {
            background: white;
            padding: 20px;
            border-radius: 10px;
            max-width: 400px;
            width: 90%;
        }

        /* Responsive */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                gap: 10px;
            }
            .hero h1 {
                font-size: 32px;
            }
            .products-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div style="display: flex; justify-content: space-between; align-items: center;">
                <div class="logo">Cover India</div>
                <nav>
                    <ul>
                        <li><a href="#about">About</a></li>
                        <li><a href="#products">Products</a></li>
                        <li><a href="#testimonials">Testimonials</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </nav>
                <div class="search-bar">
                    <input type="text" placeholder="Search covers...">
                    <button>Search</button>
                </div>
            </div>
        </div>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h1>Premium Phone Covers Made in India</h1>
            <p>Protect your device with style. Explore our exclusive collection. <br> "भारत में बने प्रीमियम कवर" (Premium Covers Made in India)</p>
            <button>Shop Now</button>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>About Cover India</h2>
            <p>Founded in 2020, Cover India is India's leading online store for premium phone covers. We specialize in high-quality, durable covers crafted with Indian craftsmanship. Our mission is to provide stylish protection for your devices while supporting local artisans.</p>
        </div>
    </section>

    <section id="products" class="products">
        <div class="container">
            <h2>Our Products</h2>
            <div class="products-grid">
                <div class="product">
                    <img src="https://via.placeholder.com/250x200?text=iPhone+Cover" alt="iPhone Cover">
                    <h3>iPhone Premium Cover</h3>
                    <p>₹499</p>
                    <button onclick="addToCart('iPhone Premium Cover')">Add to Cart</button>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/250x200?text=Samsung+Cover" alt="Samsung Cover">
                    <h3>Samsung Premium Cover</h3>
                    <p>₹399</p>
                    <button onclick="addToCart('Samsung Premium Cover')">Add to Cart</button>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/250x200?text=OnePlus+Cover" alt="OnePlus Cover">
                    <h3>OnePlus Premium Cover</h3>
                    <p>₹349</p>
                    <button onclick="addToCart('OnePlus Premium Cover')">Add to Cart</button>
                </div>
                <!-- Add more products as needed -->
            </div>
        </div>
    </section>

    <section id="testimonials" class="testimonials">
        <div class="container">
            <h2>What Our Customers Say</h2>
            <div class="testimonial">
                <p>"Amazing quality and fast delivery! Proud to support an Indian brand." - Rajesh K., Mumbai</p>
            </div>
            <div class="testimonial">
                <p>"The covers are stylish and durable. Highly recommend!" - Priya S., Delhi</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 Cover India. All rights reserved.</p>
            <div class="social-links">
                <a href="#">Facebook</a>
                <a href="#">Instagram</a>
                <a href="#">Twitter</a>
            </div>
        </div>
    </footer>

    <div id="cartModal" class="cart-modal">
        <div class="cart-content">
            <h3>Your Cart</h3>
            <p id="cartItems">No items yet.</p>
            <button onclick="closeCart()">Close</button>
        </div>
    </div>

    <script>
        let cart = [];
        function addToCart(item) {
            cart.push(item);
            document.getElementById('cartModal').style.display = 'flex';
            document.getElementById('cartItems').innerText = cart.join(', ');
        }
        function closeCart() {
            document.getElementById('cartModal').style.display = 'none';
        }
    </script>
</body>
</html>
