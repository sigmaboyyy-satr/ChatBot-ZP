<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Discord Bot Dashboard</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>🚀 My Discord Bot Dashboard</h1>
    <button id="loginBtn">Login with Discord</button>
    <button id="logoutBtn" style="display:none;">Logout</button>
  </header>

  <main>
    <section id="userInfo" style="display:none;">
      <h2>User Info</h2>
      <img id="avatar" src="" alt="Avatar">
      <p id="username"></p>
    </section>

    <section id="guilds" style="display:none;">
      <h2>Your Servers</h2>
      <ul id="guildList"></ul>
    </section>
  </main>

  <script src="script.js"></script>
</body>
</html>
