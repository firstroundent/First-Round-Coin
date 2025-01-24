# First-Round-Coin


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FirstRoundCoin</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to FirstRoundCoin</h1>
        <p>Your gateway to secure and modern cryptocurrency banking.</p>
        <a href="signup_login.html" class="btn">Sign Up / Log In</a>
    </header>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Up / Log In</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://www.gstatic.com/firebasejs/9.21.0/firebase-app.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.21.0/firebase-auth.js"></script>
    <script src="script.js" defer></script>
</head>
<body>
    <div class="auth-container">
        <h1 id="form-title">Sign Up</h1>
        <form id="auth-form">
            <input type="email" id="email" placeholder="Email" required>
            <input type="password" id="password" placeholder="Password" required>
            <button type="submit">Submit</button>
        </form>
        <p id="switch-mode">Already have an account? <span onclick="toggleForm()">Log In</span></p>
    </div>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f3f4f6;
    color: #333;
    text-align: center;
}

header {
    padding: 50px;
    background: #007bff;
    color: white;
}

.btn {
    padding: 10px 20px;
    background: #0056b3;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

.auth-container {
    margin: 50px auto;
    width: 300px;
    padding: 20px;
    background: white;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

input {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    font-size: 16px;
}

button {
    width: 100%;
    padding: 10px;
    background: #007bff;
    color: white;
    border: none;
    border-radius: 5px;
}

#switch-mode span {
    color: #007bff;
    cursor: pointer;
}
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyA5w4owsG5-DbCXFtLYSFwt4tAAnelxTBE",
  authDomain: "firstroundcoin.firebaseapp.com",
  projectId: "firstroundcoin",
  storageBucket: "firstroundcoin.firebasestorage.app",
  messagingSenderId: "236154978212",
  appId: "1:236154978212:web:22df634eee87288a0c4b31",
  measurementId: "G-54T9Y0H06V"
};
   
