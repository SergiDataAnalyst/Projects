# Projects


<html>
<head>
	<title>My Website</title>
	<style>
		body {
			background-color: white;
			margin: 0;
			padding: 0;
		}
		
		.container {
			display: flex;
			justify-content: center;
			align-items: center;
			height: 100vh;
		}
		
		.image {
			width: 200px;
			height: 200px;
			margin: 0 20px;
			border-radius: 10px;
			cursor: pointer;
			background-image: url("image1.jpg");
			background-size: cover;
			background-position: center;
			transition: transform 0.2s ease-in-out;
		}
		
		.image:hover {
			transform: scale(1.1);
		}
	</style>
</head>
<body>
	<div class="container">
		<a href="https://www.example.com"><div class="image"></div></a>
		<a href="https://www.example.com"><div class="image"></div></a>
		<a href="https://www.example.com"><div class="image"></div></a>
	</div>
</body>
</html>
