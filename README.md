# Projects

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My Portfolios</title>
    <style>
      body {
        background-color: #f8f8f8;
        font-family: Arial, sans-serif;
      }
      .container {
        max-width: 800px;
        margin: 0 auto;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        height: 100vh;
      }
      h1 {
        font-size: 48px;
        text-align: center;
        margin-bottom: 50px;
        color: #303030;
      }
      .card {
        width: 200px;
        margin: 20px;
        background-color: #fff;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        border-radius: 10px;
        overflow: hidden;
        transition: all 0.3s ease-in-out;
      }
      .card:hover {
        transform: translateY(-5px);
        box-shadow: 0 0 20px rgba(0, 0, 0, 0.4);
      }
      .card img {
        width: 100%;
        height: 200px;
        object-fit: cover;
      }
      .card h2 {
        font-size: 24px;
        text-align: center;
        margin: 20px;
        color: #303030;
      }
      .button {
        display: block;
        width: 100%;
        padding: 10px;
        text-align: center;
        background-color: #4CAF50;
        color: #fff;
        text-decoration: none;
        border-radius: 5px;
        transition: all 0.3s ease-in-out;
      }
      .button:hover {
        background-color: #3e8e41;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
      }
    </style>
  </head>
  <body>
    <div class="container">
      <h1>My Portfolios</h1>
      <div class="card">
        <a href="https://my-python-portfolio.com">
          <img src="https://raw.githubusercontent.com/SergiDataAnalyst/Prison-Escape-Data-Analysis-/main/reddit.png" alt="Python Portfolio">
        </a>
        <h2>Python</h2>
        <p>Explore my Python portfolio</p>
        <a href="https://my-python-portfolio.com" class="button">Go to portfolio</a>
      </div>
      <div class="card">
        <a href="https://my-powerbi-portfolio.com">
          <img src="https://raw.githubusercontent.com/SergiDataAnalyst/Prison-Escape-Data-Analysis-/main/reddit.png" alt="Power BI Portfolio">
        </a>
        <h2>Power BI</h2>
        <p>Explore my Power BI portfolio</p>
        <a href="https://my-powerbi-portfolio.com" class="button">Go to portfolio</a>
      </div>
      <div class="card">
        <a href="https://my-sql-portfolio.com">
          <img src="https://raw.githubusercontent.com/SergiDataAnalyst/Prison-Escape-Data-Analysis-/main/reddit.png" alt="SQL Portfolio">
        </a>
        <h2>SQL</h2>
        <p>Explore my SQL portfolio</p>
        <a href="https://my-sql-portfolio.com" class="button">Go to portfolio</a>
      </div>
    </div>
  </body>
</html
