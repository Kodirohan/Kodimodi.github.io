<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Register and Login</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="container">
    <!-- Registration Form -->
    <div id="register-form">
      <h1>Register</h1>
      <label for="username">Username</label>
      <input type="text" id="reg-username" placeholder="Enter Username" required>

      <label for="password">Password</label>
      <input type="password" id="reg-password" placeholder="Enter Password" required>

      <label for="reg-image">Profile Image</label>
      <input type="file" id="reg-image" required>
      
      <button id="register-btn">Register</button>
      <p id="register-error"></p>
    </div>

    <!-- Login Form -->
    <div id="login-form" style="display: none;">
      <h1>Login</h1>
      <label for="login-username">Username</label>
      <input type="text" id="login-username" placeholder="Enter Username" required>

      <label for="login-password">Password</label>
      <input type="password" id="login-password" placeholder="Enter Password" required>

      <button id="login-btn">Login</button>
      <p id="login-error"></p>
    </div>

    <!-- Welcome Message after Login -->
    <div id="welcome-message" style="display: none;">
      <h1>Welcome, <span id="username-display"></span></h1>
      <CENTER><img id="user-image" src="" alt="User Profile Image" style="max-width: 150px; border-radius: 50%; margin-top: 20px;"></CENTER>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
