# Projects

<!DOCTYPE html>
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
      
      /* Add padding between images */
      .image-container img {
        padding: 10px;
      }
      
      /* Set cursor to pointer when hovering over images and add transition effect */
      .image-container img:hover {
        cursor: pointer;
        opacity: 0.7; /* Add opacity effect */
        transition: all 0.3s ease-in-out;
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
    </style>
  </head>
  <body>
    <!-- Display images aligned horizontally on center -->
    <div class="image-container">
      <a href="https://www.python.org/" target="_blank">
        <img src="python.png" alt="Python" width="150">
      </a>
      <a href="https://powerbi.microsoft.com/" target="_blank">
        <img src="powerbi.png" alt="Power BI" width="150">
      </a>
      <a href="https://www.microsoft.com/en-us/sql-server/" target="_blank">
        <img src="sql.png" alt="SQL Server" width="150">
      </a>
    </div>
  </body>
</html>
