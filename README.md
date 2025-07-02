<!DOCTYPE html>
phoenixashindustries.github.io

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Phoenix Industries</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background: #f4f4f4;
      color: #EB9E10;
    }

    header {
      background: #333;
      color: #fff;
      padding: 1rem 0;
      text-align: center;
    }

    nav {
      background: #444;
      padding: 0.5rem;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
    }

    main {
      padding: 2rem;
    }

    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 1rem 0;
      position: relative;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to the store!</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="shop.html">Shop</a>
    <a href="#">Contact</a>
  </nav>

  <main>
    <h2>Hello World</h2>
    <p>This is a simple webpage hosted on GitHub Pages.</p>
    <p>You can customize this content to fit your needs.</p>
  </main>

  <footer>
    <p>&copy; 2025 Phoenix Industries</p>
  </footer>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Client Website</title>
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>
  <header>
    <nav>
      <a href="index.html">Home</a>
      <a href="shop.html">Shop</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
      <a href="privacy.html">Privacy Policy</a>
      <a href="cookie-policy.html">Cookie Policy</a>
      <a href="terms.html">Terms & Conditions</a>
    </nav>
  </header>

  <main>
    <h1>Welcome to Your New Website</h1>
    <p>This is a clean, professional starter template for your website.</p>
  </main>

  <footer>
    <p>© 2025 Client Name. All rights reserved.</p>
  </footer>

  <!-- Cookie Consent Banner -->
  <div id="cookieConsent" style="position: fixed; bottom: 0; left: 0; right: 0; background: #222; color: white; padding: 15px; text-align: center; font-family: Arial, sans-serif; z-index: 9999;">
    This website uses cookies to ensure you get the best experience. 
    See our <a href="cookie-policy.html" style="color: #4CAF50; text-decoration: underline;">Cookie Policy</a>.
    <button id="acceptCookies" style="margin-left: 15px; padding: 5px 10px; background: #4CAF50; border: none; color: white; cursor: pointer; font-weight: bold;">
      Accept
    </button>
  </div>

  <script>
    document.getElementById('acceptCookies').onclick = function() {
      localStorage.setItem('cookieConsent', 'true');
      document.getElementById('cookieConsent').style.display = 'none';
    };

    window.onload = function() {
      if (localStorage.getItem('cookieConsent') === 'true') {
        document.getElementById('cookieConsent').style.display = 'none';
      }
    };
  </script>
</body>
</html>

</body>
</html>
