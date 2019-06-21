# tetris
<html>
<head>
	<title>Tetris</title>
</head>
<body>
	<canvas id="tetris" width="240" height="400"></canvas>
	<script src="tetris.js"></script>
</body>
</html>
const canvas = document.getElementById('tetris');
const context = canvas.getContext('2d');

context.fillStyle = '#000';
context.fillRect(0, 0, canvas.width, canvas.height);
