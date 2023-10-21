<!DOCTYPE html>
<html>
<head>
    <title>Login Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            max-width: 400px;
            padding: 20px;
            background-color: #000;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(255, 255, 255, 0.2);
        }

        .form-header {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 10px;
            border-radius: 10px 10px 0 0;
        }

        h2 {
            margin: 0;
        }

        .form-group {
            margin: 10px 0;
        }

        label {
            display: block;
            font-weight: bold;
            color: #fff;
        }

        input[type="text"],
        input[type="password"] {
            width: 100%;
            padding: 10px;
            background-color: #333;
            border: 1px solid #fff;
            border-radius: 5px;
            color: #fff;
        }

        .submit-btn {
            width: 100%;
            background-color: #fff;
            color: #000;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .submit-btn:hover {
            background-color: #444;
        }

        .switch-form {
            margin-top: 10px;
        }

        .switch-form a {
            color: #007BFF;
            text-decoration: none;
        }

        .switch-form a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="form-header">
            <h2>Login</h2>
        </div>
        <form action="login.php" method="POST">
            <div class="form-group">
                <label for="login-username">Username:</label>
                <input type="text" id="login-username" name="login-username" required>
            </div>
            <div class="form-group">
                <label for="login-password">Password:</label>
                <input type="password" id="login-password" name="login-password" required>
            </div>
            <button type="submit" class="submit-btn">Login</button>
        </form>
        <div class="switch-form">
            <a href="#" id="signup-link">Don't have an account? Sign up</a>
        </div>
    </div>

    <script>
        const loginForm = document.querySelector('.container');
        const signupLink = document.getElementById('signup-link');

        signupLink.addEventListener('click', () => {
            window.location.href = "signup.html"; // Redirect to the signup page
        });
    </script>
</body>
</html>
