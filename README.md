<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<title>S.I.T.;A. Simulation Integrated Technologies</title>
	<!-- Include the flipbook.js library -->
	<script src="https://cdn.jsdelivr.net/npm/flipbookjs@3.0.0/dist/flipbook.min.js"></script>
	<!-- Define the styles for the flipbook container -->
	<style>
		#flipbook {
			width: 840px;
			height: 1200px;
			background-color: #f9f9f9;
			margin: auto;
		}
	</style>
</head>
<body>
	<!-- Define the container for the flipbook -->
	<div id="flipbook"></div>
	<!-- Initialize the flipbook -->
	<script>
		// Replace "path/to/your/pdf/file.pdf" with the path to your PDF file
		var flipbook = new flipbook({
			pages: "EBook.pdf",
			container: "#flipbook",
			width: 840,
			height: 1200,
			scale: "auto",
		});
	</script>
</body>
</html>
