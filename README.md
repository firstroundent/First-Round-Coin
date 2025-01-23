# First-Round-Coin


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


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign-Up / Log-In</title>
    <link rel="stylesheet" href="style.css">
</head><script src="https://www.gstatic.com/firebasejs/9.21.0/firebase-app.js"></script>
<script src="https://www.gstatic.com/firebasejs/9.21.0/firebase-auth.js"></script>

<body>
    <header class="main-header">
        <div class="logo">
            <img src="logo.png" alt="Bank of First Round Logo">
        </div>
        <nav class="navbar">
            <a href="index.html">Home</a>
            <a href="#wallet">Wallet</a>
            <a href="#tracker">Token Tracker</a>
        </nav>
    </header>
    
    <section class="auth-container">
        <div class="form-container">
            <h1 id="form-title">Sign Up</h1>
            <form id="auth-form">
                <div class="form-group">
                    <label for="username">Username</label>
                    <input type="text" id="username" name="username" placeholder="Enter your username" required>
                </div>
                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" placeholder="Enter your email" required>
                </div>
                <div class="form-group">
                    <label for="password">Password</label>
                    <input type="password" id="password" name="password" placeholder="Enter your password" required>
                </div>
                <button type="submit" class="btn">Sign Up</button>
                <p id="switch-mode">Already have an account? <span onclick="toggleForm()">Log In</span></p>
            </form>
        </div>
    </section>
    
    <footer class="main-footer">
        <p>&copy; 2025 Bank of First Round. All rights reserved.</p>
    </footer>
    
    <script src="script.js">// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyA5w4owsG5-DbCXFtLYSFwt4tAAnelxTBE",
  authDomain: "firstroundcoin.firebaseapp.com",
  projectId: "firstroundcoin",
  storageBucket: "firstroundcoin.firebasestorage.app",
  messagingSenderId: "236154978212",
  appId: "1:236154978212:web:ce8a204d4e1459c30c4b31",
  measurementId: "G-XEYSDD2X02"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);</script>
</body>
</html>
