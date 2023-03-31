

<html>
<head>
	<title>MY WORK 🚀</title>
	<style>
		body {
			background-color: #f7f7f7;
			margin: 0;
			padding: 0;
			font-family: Segoe, Arial, sans-serif;
                        
		}
		h1 {
			text-align: center;
			margin-top: 150px;
		}
		.container {
			display: flex;
			justify-content: center;
			align-items: center;
			margin-top: 50px;
		}
		.image-container {
			display: flex;
			flex-direction: column;
			align-items: center;
			margin: 20px;
      		}
		
		.image {
			width: 150px; /* changed width from 200px to 150px */
			height: 150px; /* changed height from 200px to 150px */
			border-radius: 20px;
			box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.3);
			transition: all 0.3s ease-in-out;
			cursor: pointer;
		}
		.image:hover {
			transform: scale(1.1);
			box-shadow: 1px 1px 20px rgba(0, 0, 0, 0.5);
		}
		.text {
			margin-top: 10px;
			text-align: center;
			font-size: 24px;
			font-family: Segoe Bold, Arial, sans-serif;
		
		}
		.about-me {
			background-color: #f7f7f7;
			height: 600px;
			display: flex;
			justify-content: center;
			align-items: center;
			color: #333333;
			font-size: 24px;
			text-align: center;
			position: relative;
			margin-top: 370px;
		}
		.about-me h2 {
			margin-top: -20px;
			font-size: 36px;
			font-weight: bold;
			text-shadow: 1px 1px 5px rgba(0,0,0,0.2);
		}
		.about-me p {
			margin: 20px;
			text-shadow: 1px 1px 5px rgba(0,0,0,0.2);
		}
		.about-me::before {
			content: "";
			position: absolute;
			top: 0;
			left: 0;
			height: 100%;
			width: 100%;
			background-color: rgba(0,0,0,0.1);
			z-index: -1;
			transform: translateZ(-1px) scale(2);
		}
	</style>
</head>
<body>
	<script>
  function playVideo(filename, container) {
    // Create the video element and set its attributes
    var video = document.createElement('video');
    video.src = filename;
    video.autoplay = true;
    video.controls = true;
    video.width = 150;
    video.height = 150;
    video.style.borderRadius = '20px';
    video.style.boxShadow = '1px 1px 10px rgba(0, 0, 0, 0.3)';
    video.style.transition = 'all 0.3s ease-in-out';
    video.style.cursor = 'pointer';
    video.style.transform = 'scale(1.1)';
    video.style.boxShadow = '1px 1px 20px rgba(0, 0, 0, 0.5)';

    // Replace the image element with the video element
    var image = container.querySelector('.image');
    container.replaceChild(video, image);
  }
</script>

	<h1>My Work 🚀</h1>
	<div class="container">
		<div class="image-container">
			<img src="python.png" alt="Python Logo" class="image" onclick="window.location.href='https://sergidataanalyst.github.io/'">
			<div class="text">
				<p>Python</p>
			</div>
		</div>
		<div class="image-container">
			<img src="powerbi.png" alt="Power BI Logo" class="image" onclick="window.location.href='https://sergidataanalyst.github.io/PowerBI/'">
			<div class="text">
				<p>Power BI</p>
			</div>
		</div>
		<div class="image-container">
			<img src="sql.png" alt="SQL Server Logo" class="image" onclick="window.location.href='https://count.co/report/mx3pf4bIZcu?frame=nX1StErbcFe'">
			<div class="text">
				<p>SQL</p> 
</div>
		</div>
	</div>
	<div class="about-me">
		<div class="about-me-content">
			<h2>About Me 🙋🏻‍♂️</h2>
			<p>I am an engineer with a hungry appetite for knowledge and a knack for analyzing data. Currently, I'm studying a Master of Science in Artificial Intelligence because I heard that robots are coming for our jobs, and I want to be the one pulling the strings.
</p>
<p>
When I'm not busy programming or learning German, you can find me on my paraglider soaring the skies, or hiking up mountains like a Sherpa. 
</p>
<p>

I've worked with small businesses before, analyzing their data and building custom business analysis reports to help them make sense of their operations. I love being able to take complicated data and turning it into something that everyone can understand. Think of me as the data whisperer, taming the wildest spreadsheets with just a few clicks.
</p>
<p>
In short, I'm a mad scientist with a passion for AI and Data Analytics and a love for nature and the outdoors. If you're looking for someone to help you make sense of your data, look no further.
</p>
<div style="display:flex; justify-content:center; gap:20px;">
	<div class="image-container" onmouseover="playVideo('video1.mp4', this)">
  <video width="315" height="560" controls>
    <source src="video.mp4" type="video/mp4">
  </video>
  <video width="315" height="560" controls>
    <source src="videon.mp4" type="video/mp4">
  </video>
  <video width="315" height="560" controls>
    <source src="video1.mp4" type="video/mp4">
  </video>
</div>

			
		</div>
	</div>
	<script>
		window.addEventListener("scroll", function() {
			var offset = window.pageYOffset;
			var aboutMe = document.querySelector(".about-me");
			aboutMe.style.transform = "translateY(" + offset * 0.5 + "px)";
		});
	</script>
</body>
</html>
