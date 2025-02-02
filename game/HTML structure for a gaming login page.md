<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - Gaming Site</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="login-container">
        <div class="logo">
            <img src="logo.png" alt="Gaming Site Logo">
        </div>
        <form class="login-form" action="/login" method="POST">
            <h2>Welcome Back, Gamer!</h2>
            <div class="input-group">
                <label for="username">Username or Email</label>
                <input type="text" id="username" name="username" required>
            </div>
            <div class="input-group">
                <label for="password">Password</label>
                <input type="password" id="password" name="password" required>
            </div>
            <button type="submit" class="login-button">Login</button>
            <div class="links">
                <a href="/forgot-password">Forgot Password?</a>
                <span> | </span>
                <a href="/signup">Create an Account</a>
            </div>
        </form>
    </div>
</body>
</html>