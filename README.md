
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Q233_CORTEZ_LOGINFORM</title>
    <link rel="stylesheet" href="labno.4.css">
</head>
<body>

<div class="wrapper">
    <div class="login_box">
        <div class="login">
            <span>Login</span>
        </div>

        <form>
            <div class="info_box">
                <label for="USERNAME" class="label">Username:</label>
                <input type="text" id="USERNAME" class="input" required>
            </div>

            <div class="info_box">
                <label for="PASSWORD" class="label">Password:</label>
                <input type="password" id="PASSWORD" class="input" required>
            </div>

            <div class="remember-forgot">
                <label><input type="checkbox"> Remember me</label>
            </div>

            <button class="input-login" onclick="location.href='https://seraphimkyla.github.io/OwnLab/'">
                Login
            </button>

            <div class="register">
                <span>Don't have an account? <a href="labno.5.html">Sign Up</a></span>
            </div>
        </form>
    </div>
</div>

</body>
</html>
