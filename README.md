<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Hell - Digital Marketplace</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>The Hell</h1>
            <nav>
                <ul>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#admin">Admin Panel</a></li>
                    <li><a href="#stats">Statistics</a></li>
                    <li><a href="#reviews">Reviews</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="products">
        <div class="container">
            <h2>Digital Products</h2>
            <p>Explore our wide range of digital games, skins, and shooting games available for purchase.</p>
            <div class="product-list">
                <!-- Products will be dynamically loaded here -->
                <button>Buy Now</button>
            </div>
        </div>
    </section>

    <section id="admin">
        <div class="container">
            <h2>Admin Panel</h2>
            <p>Manage your products, roles, and user activities efficiently.</p>
            <ul>
                <li><a href="#manage-roles">Manage Roles</a></li>
                <li><a href="#manage-products">Manage Products</a></li>
                <li><a href="#analytics">View Analytics</a></li>
            </ul>
        </div>
    </section>

    <section id="stats">
        <div class="container">
            <h2>Sales and Click Statistics</h2>
            <p>Monitor product performance and inventory in real-time.</p>
            <div id="statistics-dashboard">
                <div class="stat-item">
                    <h3>Total Sales</h3>
                    <p id="total-sales">Loading...</p>
                </div>
                <div class="stat-item">
                    <h3>Total Clicks</h3>
                    <p id="total-clicks">Loading...</p>
                </div>
                <div class="stat-item">
                    <h3>Remaining Inventory</h3>
                    <p id="remaining-inventory">Loading...</p>
                </div>
            </div>
        </div>
    </section>

    <section id="reviews">
        <div class="container">
            <h2>Customer Reviews</h2>
            <div id="reviews-list">
                <!-- Reviews will be dynamically loaded here -->
            </div>
        </div>
    </section>

    <section id="payment">
        <div class="container">
            <h2>Payment Gateway</h2>
            <p>Securely pay for your digital products with our trusted gateway providers.</p>
            <button>Proceed to Payment</button>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <ul>
                <li>Email: support@thehell.com</li>
                <li>Phone: +123 456 7890</li>
                <li>Social Media:
                    <ul>
                        <li><a href="#">Facebook</a></li>
                        <li><a href="#">Twitter</a></li>
                        <li><a href="#">Instagram</a></li>
                    </ul>
                </li>
            </ul>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 The Hell. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
