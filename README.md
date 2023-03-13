
##           Projects
<p style="text-align:center; font-size: 24px; font-family: Segoe Bold, Arial, sans-serif;">PROJECTS</p>


<!DOCTYPE html>
<html>
<head>
	<title>MY WORK</title>
	<style>
		body {
			background-color: #f9f9f9;
			margin: 0;
			padding: 0;
			font-family: Arial, sans-serif;
		}
		h1 {
			text-align: center;
			margin-top: 50px;
		}
		.container {
			display: flex;
			justify-content: center;
			align-items: center;
			margin-top: 50px;
		}
		.image {
			width: 200px;
			height: 200px;
			border-radius: 20px;
			margin: 20px;
			transition: all 0.3s ease-in-out;
		}
		.image:hover {
			transform: scale(1.3);
		}
		.about-me {
			background-image: url('https://i.imgur.com/NVxzds2.png');
			background-size: cover;
			background-position: center;
			height: 500px;
			display: flex;
			justify-content: center;
			align-items: center;
			color: white;
			font-size: 24px;
			text-align: center;
			position: relative;
			background-attachment: fixed;
			background-position: center;
			background-repeat: no-repeat;
			background-size: cover;
			overflow: hidden;
			margin-top: 50px;
		}
		.about-me h2 {
			margin-top: 0;
			font-size: 36px;
			font-weight: bold;
			text-shadow: 1px 1px 5px rgba(0,0,0,0.5);
		}
		.about-me p {
			margin: 20px;
			text-shadow: 1px 1px 5px rgba(0,0,0,0.5);
		}
		.about-me::before {
			content: "";
			position: absolute;
			top: 0;
			left: 0;
			height: 100%;
			width: 100%;
			background-color: rgba(0,0,0,0.5);
			z-index: -1;
			transform: translateZ(-1px) scale(2);
		}
	</style>
</head>
<body>
	<h1>My Images</h1>
	<div class="container">
		<img src="python.png" alt="Python Logo" class="image">
		<img src="powerbi.png" alt="Power BI Logo" class="image">
		<img src="sql.png" alt="SQL Server Logo" class="image">
	</div>
	<div class="about-me">
		<div class="about-me-content">
			<h2>About Me</h2>
			<p>Hi, my name is ChatGPT and I'm a language model trained by OpenAI. I'm designed to answer your questions and help you with your tasks. I'm constantly learning and improving, so feel free to ask me anything!</p>
		</div>
	</div>
	<script>
		window.addEventListener("scroll", function() {
			var offset = window.pageYOffset;
			var aboutMe = document.querySelector(".about-me");
			aboutMe.style.backgroundPositionY = offset * 0.5 + "px";
		});
	</script>
</body>
</html>
