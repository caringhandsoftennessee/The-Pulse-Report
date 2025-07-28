# The-Pulse-Report
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Pulse Report</title>
  <style>
    /* Reset some default styles */
    body, html {
      margin: 0; padding: 0; height: 100%;
      font-family: Georgia, serif;
      background: #fff;
      color: #222;
    }
    .container {
      display: flex;
      height: 100vh;
    }
    nav {
      width: 250px;
      background: #f5f5f5;
      padding: 20px;
      box-sizing: border-box;
      border-right: 1px solid #ddd;
    }
    nav h1 {
      font-size: 1.8rem;
      margin-bottom: 1rem;
      font-weight: bold;
      letter-spacing: 1px;
    }
    nav a {
      display: block;
      margin: 10px 0;
      color: #333;
      text-decoration: none;
      font-weight: 600;
      font-size: 1rem;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      flex: 1;
      padding: 40px;
      overflow-y: auto;
    }
    article {
      max-width: 700px;
      margin-bottom: 40px;
      border-bottom: 1px solid #ddd;
      padding-bottom: 20px;
    }
    article h2 {
      font-size: 1.8rem;
      margin-bottom: 0.5rem;
      font-weight: bold;
    }
    article p {
      line-height: 1.6;
      font-size: 1.1rem;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #999;
      border-top: 1px solid #ddd;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <div class="container">
    <nav>
      <h1>Pulse Report</h1>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Archives</a>
      <a href="#">Subscribe</a>
      <a href="#">Contact</a>
    </nav>
    <main>
      <article>
        <h2>Headline Story Title</h2>
        <p>Intro paragraph of your first article goes here. This should be a strong, clear summary of the news or topic.</p>
      </article>
      <article>
        <h2>Another Article Title</h2>
        <p>Second article text goes here. Keep paragraphs clear and readable, with good line spacing.</p>
      </article>
      <footer>
        &copy; 2025 Pulse Report. All rights reserved.
      </footer>
    </main>
  </div>
</body>
</html>
