

<p style="text-align:center; font-size: 24px; font-family: Segoe Bold, Arial, sans-serif;">PROJECTS</p>

<html>
<head>
	<title>MY WORK</title>
	<style>
		body {
			background-color: #f7f7f7;
			margin: 0;
			padding: 0;
			font-family: Arial, sans-serif;
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
		}
		.image:hover {
			transform: scale(1.1);
			box-shadow: 1px 1px 20px rgba(0, 0, 0, 0.5);
		}
		.text {
			margin-top: 10px;
			text-align: center;
		}
		.about-me {
			background-color: #f7f7f7;
			height: 500px;
			display: flex;
			justify-content: center;
			align-items: center;
			color: #333333;
			font-size: 24px;
			text-align: center;
			position: relative;
			margin-top: 290px;
		}
		.about-me h2 {
			margin-top: -420px;
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
	<h1>My Work</h1>
	<div class="container">
		<div class="image-container">
			<a href="https://www.python.org/" target="_blank">
				<img src="python.png" alt="Python Logo" class="image">
				<div class="text">
					<p>Python</p>
				</div>
			</a>
		</div>
		<div class="image-container">
			<a href="https://powerbi.microsoft.com/" target="_blank">
				<img src="powerbi.png" alt="Power BI Logo" class="image">
				<div class="text">
					<p>Power BI</p>
				</div>
			</a>
		</div>
		<div class="image-container">
			<a href="https://www.microsoft.com/en-us/sql-server/" target="_blank">
				<img src="sql.png" alt="SQL Server Logo" class="image">
				<div class="text-container">
					<p>SQL</p> 
				</div>
			</a>
		</div>
	</div>
	<div class="about-me">
		<div class="about-me-content">
			<h2>About Me</h2>
			<p>I'm the super-powered engineer with an insatiable appetite for knowledge and a knack for analyzing data like nobody's business. Currently, I'm studying the Master of Science in Artificial Intelligence because I heard that robots are coming for our jobs, and I want to be the one pulling the strings.
			</p>
			<p>
			When I'm not busy coding, you can find me soaring through the skies like a majestic eagle with my trusty paraglider, or hiking up mountains like a modern-day Sherpa. So, you can say that I'm both a computer whiz and a mountain wizard.
			</p>
			<p>

			I've worked with small businesses before, analyzing their data and building custom business analysis reports to help them make sense of their operations. I love being able to take complicated data and turning it into something that everyone can understand. Think of me as the data whisperer, taming the wildest spreadsheets with just a few clicks.
			</p>
			<p>
			In short, I'm a mad scientist with a passion for AI and a love for the great outdoors. If you're looking for someone to help you make sense of your data and have a laugh along the way, look no further. I'm your guy!
			</p>
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
