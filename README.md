# google-homepage

# google-homepage
<!DOCTYPE html>
<html>
<head> 
<title>The Google Homepage</title>
<link rel="stylesheet" href="style.css">
</head>

<body>
	<div class="container">

		<div class="header"
			<ul class="nav">

			<li><a hreflk="#">+Buck</a></li>
			<li><a href="#">Mail</a></li>
			<li><a href="#">Images</a></li>

			<li><a class="apps" href="#"></a></li>
			<li><a class="bell" href="#"></a></li>
			<li><a class="share" href="#">Share</a></li>
			<li><a class="face" href="#"></a></li>

			</ul>

		</div>
		
<div class="cf"></div>
	<div class="google-search">

	<center>
	<img src="https://raw.githubusercontent.com/n8sb/odin-project/master/google-homepage/images/google.png" alt="google">
	<form action="POST">	

		<div class="search-bar">
			<div class="mic"><img src="https://raw.githubusercontent.com/n8sb/odin-project/master/google-homepage/images/mic.gif" alt=""></div>
			<input type="text" name="search"><br>
			</div>

			<div class="cf"></div>

		<input class="search" type="submit" value="Google Search">
		<input class="lucky" type="submit" value="I'm Felling Lucky">

		</form>

	</center>

	</div>

	<footer>
		
		<ul class="footer-left">

			<li><a class="name" href="#">Advertising</a></li>
			<li><a class="mail" href="#">Business</a></li>
			<li><a class="images" href="#">About</a></li>

			</ul>

		<ul class="footer-right">
		
			<li><a href="#">Privacy &amp; Terms</a></li>
			<li><a href="#">Settings</a></li>

			</ul>

		</footer>
		
	</div>
	
	<script type="text/javascript">
	$('input[type=text]').focus(function){
		$('.mic').css('border-color','#DCDCDC');
	});

	</script>			 



</body>
</html>	
