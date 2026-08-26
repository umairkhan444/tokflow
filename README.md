<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tokflow - Watch Videos</title>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tokflow - Watch Videos</title>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Tokflow - Watch Videos</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f5f5f5;
    }

    /* Header */
    header {
      background: #ffffff;
      padding: 15px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #ddd;
      position: sticky;
      top: 0;
    }

    .logo {
      font-size: 28px;
      font-weight: bold;
      color: #ff0050;
    }

    nav a {
      text-decoration: none;
      color: #333;
      margin-left: 20px;
      font-weight: bold;
    }

    nav a:hover {
      color: #ff0050;
    }

    /* Hero */
    .hero {
      text-align: center;
      padding: 80px 20px;
      background: linear-gradient(135deg, #111, #333);
      color: white;
    }

    .hero h1 {
      font-size: 50px;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 20px;
      margin-bottom: 25px;
    }

    .btn {
      background: #ff0050;
      color: white;
      padding: 13px 25px;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }

    /* Videos */
    .videos {
      padding: 50px 8%;
    }

    .videos h2 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 32px;
    }

    .video-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .video-card {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      transition: 0.3s;
    }

    .video-card:hover {
      transform: translateY(-5px);
    }

    .thumbnail {
      height: 180px;
      background: #ddd;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 50px;
    }

    .video-card h3 {
      padding: 15px;
    }

    .video-card p {
      padding: 0 15px 15px;
      color: gray;
    }

    /* Footer */
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 25px;
      margin-top: 30px;
    }

    @media(max-width: 600px) {
      header {
        padding: 15px;
      }

      .hero h1 {
        font-size: 35px;
      }

      nav a {
        margin-left: 10px;
        font-size: 14px;
      }
    }

  </style>
</head>

<body>

  <header>
    <div class="logo">Tokflow</div>

    <nav>
      <a href="#">Home</a>
      <a href="#videos">Videos</a>
      <a href="#">About</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Welcome to Tokflow</h1>

    <p>Watch and enjoy amazing videos.</p>

    <a href="#videos" class="btn">Watch Videos</a>
  </section>


  <section class="videos" id="videos">

    <h2>Trending Videos</h2>

    <div class="video-grid">

      <div class="video-card">
        <div class="thumbnail">▶️</div>
        <h3>Funny Cartoon Video</h3>
        <p>Watch the latest funny cartoon.</p>
      </div>

      <div class="video-card">
        <div class="thumbnail">▶️</div>
        <h3>AI Video</h3>
        <p>Creative videos made with AI.</p>
      </div>

      <div class="video-card">
        <div class="thumbnail">▶️</div>
        <h3>Trending Video</h3>
        <p>Watch popular videos on Tokflow.</p>
      </div>

      <div class="video-card">
        <div class="thumbnail">▶️</div>
        <h3>New Video</h3>
        <p>Discover something new today.</p>
      </div>

    </div>

  </section>


  <footer>
    <p>© 2026 Tokflow. All Rights Reserved.</p>
  </footer>

</body>
</html>

