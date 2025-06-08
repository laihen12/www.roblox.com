<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Roblox Login and Add Friend</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .box {
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      width: 300px;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
    }

    input[type="text"],
    input[type="password"] {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      font-size: 16px;
    }

    button {
      width: 100%;
      padding: 10px;
      margin-top: 20px;
      font-size: 16px;
      background-color: #007bff;
      color: white;
      border: none;
      cursor: pointer;
    }

    .message {
      margin-top: 15px;
      text-align: center;
      font-weight: bold;
      color: green;
    }
  </style>
</head>
<body>
  <div class="box" id="login-box">
    <h2>Login</h2>
    <input type="text" id="username" placeholder="Username" />
    <input type="password" id="password" placeholder="Password" />
    <button onclick="login()">Log In</button>
  </div>

  <div class="box" id="friend-box" style="display: none;">
    <h2>Welcome!</h2>
    <p id="welcome-text"></p>
    <button onclick="addFriend()">Add Friend</button>
    <div class="message" id="friend-message"></div>
  </div>

  <script>
    function login() {
      const username = document.getElementById("username").value;
      const password = document.getElementById("password").value;

      if (username && password) {
        // Hide login, show friend UI
        document.getElementById("login-box").style.display = "none";
        document.getElementById("friend-box").style.display = "block";
        document.getElementById("welcome-text").innerText = "Hello, " + username + "!";
      } else {
        alert("Please enter both username and password.");
      }
    }

    function addFriend() {
      document.getElementById("friend-message").innerText =
        "Friend request sent! (simulated)";
    }
  </script>
</body>
</html>
