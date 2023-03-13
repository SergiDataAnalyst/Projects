
##           Projects
<p style="text-align:center; font-size: 24px; font-family: Segoe Bold, Arial, sans-serif;">PROJECTS</p>


<html>
  <head>
    <title>My Website</title>
    <style>
      /* Set background color to white */
      body {
        background-color: #ffffff;
      }

      /* Set up background effect */
      .background-effect {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        z-index: -1;
        background-image: linear-gradient(to right, #000000, #434343);
      }
      .background-effect::before {
        content: "";
        position: absolute;
        top: 0;
        left: 0;
        width: 20px;
        height: 20px;
        background-image: radial-gradient(#e1e1e1 50%, transparent 0);
        background-position: 0 0;
        background-repeat: repeat;
        transform: scale(15);
        z-index: -1;
      }
      .background-effect::after {
        content: "";
        position: absolute;
        top: 0;
        left: 0;
        width: 20px;
        height: 20px;
        background-image: radial-gradient(#000000 50%, transparent 0);
        background-position: 0 0;
        background-repeat: repeat;
        transform: scale(15);
        z-index: -1;
        animation: animate 10s linear infinite;
      }
      @keyframes animate {
        from {
          transform: translate(-100px, -100px) scale(15);
        }
        to {
          transform: translate(200px, 200px) scale(15);
        }
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
    <div class="background-effect"></div>
    <div class="image-container">
      <div>
        <a href="https://sergidataanalyst.github.io/" target="_blank">
          <img src="python.png" alt="Python" width="150">
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
  <script>
    // Interactive background effect
    document.addEventListener("mousemove", function(e) {
      const body = document.querySelector("body");
      const centerX = window.innerWidth / 2;
      const centerY = window.innerHeight / 2;
      const deltaX = e.clientX - centerX;
      const deltaY = e.clientY - centerY;
      const percentX = deltaX / centerX;
      const percentY = deltaY / centerY;
      const deg = 10;
      const offsetX = percentX * deg;
      const offsetY = percentY * deg;
      body.style.backgroundPositionX = `${offsetX}px`;
      body.style.backgroundPositionY = `${offsetY}px`;
    });
  </script>
</html>
       
