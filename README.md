
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Decorated Content Card</title>
  <style>
    body {
      background: #f2f4f8;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .card {
      width: 320px;
      background: linear-gradient(to bottom right, #ffffff, #f9f9f9);
      border-radius: 20px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      cursor: pointer;
    }

    .card:hover {
      transform: scale(1.05);
      box-shadow: 0 12px 24px rgba(0, 0, 0, 0.2);
    }

    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .card-content {
      padding: 20px;
    }

    .card h3 {
      margin: 0 0 10px;
      font-size: 1.4rem;
      color: #333;
    }

    .card p {
      margin: 0;
      color: #666;
      font-size: 0.95rem;
    }

    .card-icon {
      width: 40px;
      height: 40px;
      background-color: #4f46e5;
      color: #fff;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.2rem;
      margin-bottom: 12px;
    }
  </style>
</head>
<body>

  <div class="card">
    <img src="https://cdn.pixabay.com/photo/2015/04/23/22/00/new-year-background-736885_1280.jpg" alt="Card Image">
    <div class="card-content">
      <div class="card-icon">🌿</div>
      <h3>Explore Nature</h3>
      <p>Discover beautiful landscapes and connect with the outdoors in a whole new way.</p>
    </div>
  </div>

</body>
</html>
