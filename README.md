<!DOCTYPE html>
<html>
	<head>
		<title>Github API</title>
	</head>
	<body>
		<canvas id="canvas"></canvas>
		<script type='module'>
			import { Octokit } from "https://cdn.skypack.dev/octokit";

			const canvas = document.getElementById("canvas");
			const ctx = canvas.getContext('2d');
			ctx.font = '400 24px Arial';
			ctx.fillText("Loading...", 0, 18);
		</script>
	</body>
</html>
