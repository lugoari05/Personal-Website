# Personal-Website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ariana Lugo Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Navigation -->
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
    </ul>
  </nav>

  <!-- Home Section -->
  <section id="home">
    <h1>Welcome to My Portfolio</h1>
    <p>Hi, I'm Ariana Lugo, a Government major at the University of Texas with a passion for corporate law and business foundations.</p>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>I am a hardworking Latina interested in corporate law, currently pursuing my undergraduate studies in Government at the University of Texas. I am also completing a minor in Business Foundations, along with two certificates in Law, Justice, and Society, and Spanish Business. I am motivated to explore opportunities that combine law, government, and international business.</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 Ariana Lugo. All rights reserved.</p>
  </footer>

  <!-- Minimal JavaScript -->
  <script>
    // Smooth scroll for navigation links
    document.querySelectorAll('nav a').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({ behavior: 'smooth' });
      });
    });
  </script>
</body>
</html>
