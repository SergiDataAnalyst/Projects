
## Projects
#
# ## Projects

<html>
  <head>
    <title>My Website</title>
    <style>
      /* Set background color to white */
      body {
        background-color: #ffffff;
      }
      
      /* Center the images */
      .image-container {
        display: flex;
        justify-content: center;
      }

      /* Add margin between images */
      .image-container a:not(:last-child) {
        margin-right: 20px;
      }

      /* Add padding between images */
      .image-container img {
        padding: 10px;
      }
      
      /* Set cursor to pointer when hovering over images and add transition effect */
      .image-container a:hover img {
        cursor: pointer;
        opacity: 0.7; /* Add opacity effect */
        transition: all 0.3s ease-in-out;
        transform: translateY(-5px) scale(1.05);
        box-shadow: 0 8px 10px rgba(0, 0, 0, 0.2);
      }
      
      /* Make images responsive */
      .image-container img {
        max-width: 100%;
        height: auto;
        border-radius: 20px; /* Round the corners */
      }
      
      /* Add visual appeal to images */
      .image-container img {
        border: 3px solid #f5f5f5;
        box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.1);
      }

      /* Style the text elements */
      .image-container p {
        margin-top: 20px;
        font-family: Segoe Bold, Arial, sans-serif;
        text-align: center;
      }
    </style>
  </head>
  <body>
    <!-- Display images aligned horizontally on center -->
    <div class="image-container">
      <div>
        <a href="https://sergidataanalyst.github.io/" target="_blank">
          <img src="python.png" alt="Python" width="150">
        </a>
        <p>Python</p>
      </div>
      <div>
        <a href="https://sergidataanalyst.github.io/PowerBI/" target="_blank">
          <img src="powerbi.png" alt="Power BI" width="150">
        </a>
        <p>Power BI</p>
      </div>
      <div>
        <a href="https://count.co/report/mx3pf4bIZcu?frame=nX1StErbcFe" target="_blank">
          <img src="sql.png" alt="SQL Server" width="150">
        </a>
        <p>SQL</p>
      </div>
    </div>
  </body>
</html>
