<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>The Mystery Box</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body {
      margin: 0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "SF Pro Text", sans-serif;
      background: radial-gradient(circle at top, #020617 0, #020617 40%, #000 100%);
      color: #e5e7eb;
    }
    header {
      padding: 20px;
      text-align: center;
      border-bottom: 1px solid #1f2937;
      background: #020617;
    }
    header h1 {
      margin: 0;
      font-size: 28px;
      letter-spacing: 0.08em;
      text-transform: uppercase;
    }
    .page {
      max-width: 960px;
      margin: 0 auto;
      padding: 40px 16px 60px;
    }
    .hero {
      text-align: center;
      margin-bottom: 40px;
    }
    .hero h2 {
      font-size: 32px;
      margin-bottom: 12px;
    }
    .hero p {
      font-size: 16px;
      color: #9ca3af;
      max-width: 640px;
      margin: 0 auto 20px;
    }
    .hero-cta {
      margin-top: 24px;
    }
    .hero-cta a {
      display: inline-block;
      padding: 14px 26px;
      border-radius: 999px;
      background: linear-gradient(135deg, #f97316, #ec4899);
      color: white;
      text-decoration: none;
      font-weight: 600;
      font-size: 15px;
    }
    .hero-cta a:hover {
      opacity: 0.9;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
      margin-top: 40px;
    }
    .card {
      background: rgba(15, 23, 42, 0.96);
      border-radius: 16px;
      border: 1px solid #1f2937;
      padding: 18px 18px 20px;
    }
    .card h3 {
      margin-top: 0;
      margin-bottom: 8px;
      font-size: 18px;
    }
    .card p {
      margin: 0;
      font-size: 14px;
      color: #9ca3af;
    }
    .footer {
      margin-top: 40px;
      text-align: center;
      font-size: 12px;
      color: #6b7280;
    }
  </style>
</head>
<body>
  <header>
    <h1>THE MYSTERY BOX</h1>
  </header>

  <div class="page">
    <section class="hero">
      <h2>One Box. Infinite Questions.</h2>
      <p>
        A stranger left you a sealed box and a single rule: <em>“Open it only if you’re willing to know what you can’t forget.”</em><br>
        Every visit reveals more of the story. Every choice takes you deeper. Most people never reach the end.
      </p>
      <div class="hero-cta">
        <a href="mystery-1.html">Enter the Mystery</a>
      </div>
    </section>

    <section class="grid">
      <div class="card">
        <h3>Not a game. A test.</h3>
        <p>
          Each chapter gives you a clue, a riddle, or a decision. Your answers shape what you see next.
        </p>
      </div>
      <div class="card">
        <h3>Come back or get left behind.</h3>
        <p>
          New layers unlock over time. If you stop, the story moves on without you. The box doesn’t wait.
        </p>
      </div>
      <div class="card">
        <h3>Some doors are free. Some are not.</h3>
        <p>
          The first layer is free. Deeper access requires a small payment to unlock the next sealed compartment.
        </p>
      </div>
    </section>

    <div class="footer">
      The box remembers who tried to open it.
    </div>
  </div>
</body>
</html>

