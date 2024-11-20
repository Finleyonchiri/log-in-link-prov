<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login and Register</title>
    <link rel="stylesheet" href="styles.css">
    <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
</head>
<body>
    <section class="form-container">
        <form class="form">
            <h1>Log in</h1>
            <div class="inputbox">
                <ion-icon name="mail-outline"></ion-icon>
                <input type="email" required>
                <label>User</label>
            </div>
            <div class="inputbox">
                <ion-icon name="lock-closed-outline"></ion-icon>
                <input type="password" required>
                <label>Password</label>
            </div>
            <div class="forget">
                <label><input type="checkbox">Remember</label>
                <a href="#">Forgot Password</a>
            </div>
            <button>Login</button>
            <div class="register">
                <p>I don't have an account <a href="#">Register</a></p>
            </div>
        </form>
    </section>

    <!-- Include Ionicons for icons -->
    <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
</body>
</html>
