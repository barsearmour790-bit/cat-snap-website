# cat-snap-website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CatSnap - Subscription</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Welcome to CatSnap</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#features">Features</a>
      <a href="#subscribe">Subscribe</a>
    </nav>
  </header>

  <section id="home">
    <h2>What is CatSnap?</h2>
    <p>CatSnap is your go-to platform for sharing and enjoying cat videos, with features similar to TikTok!</p>
  </section>

  <section id="features">
    <h2>Features</h2>
    <ul>
      <li>Video Uploads</li>
      <li>Short Clips</li>
      <li>Subscription Content</li>
      <li>Custom Cat Filters</li>
    </ul>
  </section>

  <section id="subscribe">
    <h2>Subscribe for $27.5/month</h2>
    <p>Get full access to all premium content. Enjoy exclusive cat videos, live streams, and more!</p>
    <button onclick="subscribe()">Subscribe Now</button>
  </section>

  <footer>
    <p>© 2025 CatSnap. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
  color: #333;
  margin: 0;
  padding: 0;
}

header {
  background-color: #ff6f61;
  color: white;
  padding: 20px;
  text-align: center;
}

header nav a {
  margin: 0 15px;
  text-decoration: none;
  color: white;
}

section {
  padding: 20px;
  text-align: center;
}

h1, h2 {
  color: #333;
}

button {
  background-color: #ff6f61;
  color: white;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
  font-size: 18px;
}

button:hover {
  background-color: #e55b4e;
}

footer {
  background-color: #333;
  color: white;
  padding: 10px;
  text-align: center;
}
