# First-Round-Coin

/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body and Font Styles */
body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f9f9f9;
}

/* Header Styles */
.main-header {
    background-color: #1f1f1f;
    color: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
}

.logo img {
    max-height: 50px;
}

.navbar a {
    color: #fff;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
}

.navbar a:hover {
    color: #f9a825;
}

/* Auth Container */
.auth-container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
    background: linear-gradient(to right, #141e30, #243b55);
}

.form-container {
    background-color: #fff;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    width: 100%;
    max-width: 400px;
    text-align: center;
}

.form-container h1 {
    margin-bottom: 20px;
    font-size: 1.8rem;
    color: #333;
}

.form-group {
    margin-bottom: 15px;
    text-align: left;
}

.form-group label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
}

.form-group input {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 1rem;
}

.btn {
    background-color: #f9a825;
    border: none;
    color: #fff;
    padding: 10px 20px;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 5px;
    margin-top: 10px;
    width: 100%;
}

.btn:hover {
    background-color: #e68a00;
}

#switch-mode {
    margin-top: 15px;
    font-size: 0.9rem;
    color: #555;
}

#switch-mode span {
    color: #f9a825;
    cursor: pointer;
    font-weight: bold;
}

#switch-mode span:hover {
    text-decoration: underline;
}

/* Footer */
.main-footer {
    text-align: center;
    padding: 10px;
    background-color: #1f1f1f;
    color: #fff;
    font-size: 0.9rem;
}


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bank of First Round</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="main-header">
        <div class="logo">
            <img src="logo.png" alt="Bank of First Round Logo">
        </div>
        <nav class="navbar">
            <a href="#features">Features</a>
            <a href="#wallet">Wallet</a>
            <a href="#tracker">Token Tracker</a>
            <a href="#announcements">Announcements</a>
        </nav>
    </header>
    
    <section class="hero">
        <div class="hero-text">
            <h1>Welcome to the Bank of First Round</h1>
            <p>The secure, user-friendly wallet for First Round Coin. Modern banking, reimagined.</p>
            <div class="cta-buttons">
                <button onclick="location.href='#wallet'">Create an Account</button>
                <button onclick="location.href='#buy'">Buy First Round Coin</button>
            </div>
        </div>
    </section>
    
    <section id="tracker" class="tracker">
        <h2>Live Token Tracker</h2>
        <div id="token-stats">
            <p>Price: $0.00</p>
            <p>Market Cap: $0.00</p>
            <p>24h Volume: $0.00</p>
        </div>
    </section>
    
    <section id="features" class="features">
        <h2>Why Choose First Round Coin?</h2>
        <ul>
            <li>Secure wallet integration</li>
            <li>Direct purchase with USD</li>
            <li>Exclusive member perks</li>
            <li>Global multi-language support</li>
        </ul>
    </section>
    
    <footer class="main-footer">
        <p>&copy; 2025 Bank of First Round. All rights reserved.</p>
    </footer>
    
    <script src="script.js"></script>
</body>
</html>
