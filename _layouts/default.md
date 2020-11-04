<!DOCTYPE html>
	<html>
		<head>
			<title>{{ page.title }}</title>
			<!-- link to main stylesheet -->
			<link rel="stylesheet" type="text/css" href="/css/main.css">
			<!-- set meta viewport--this helps with responsive design, keeping the text size readable across different devices.-->
			<meta name="viewport" content="width=device-width, initial-scale=1">
			<!-- google fonts -->
			<link href="https://fonts.googleapis.com/css2?family=Cormorant+Infant:wght@600&family=Roboto:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">
			<!-- favicon -->
			<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
			<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
			<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
			<link rel="manifest" href="/site.webmanifest">
		</head>
		<body>
			<nav>
	    		<ul>
	        		<li><a href="/">Archive</a></li>
		        	<li><a href="/about">About</a></li>
	    		</ul>
			</nav>
			<div class="container">
			{{ content }}
			</div><!-- /.container -->
			<footer>
	    		<ul>
	        		<li><a href="mailto:marinakittaka@gmail.com">email me!</a></li>
					<li><a href="https://zone.marinakittaka.com/atom.xml">RSS</a></li> 
				</ul>
			</footer>
		</body>
	</html>
