# PNWprogrammer-PNWprogrammer.github.io-
<!DOCTYPE html>
<html>

<!-- Head -->
	<head>
		<meta charset="UTF-8">
		<title>&#x1F332; Austin Davis &#x1F332;</title>
		<link rel="stylesheet" type="text/css" href="../CSS/Austin_Davis.css">
	</head>

<!-- Body -->
<body class="Background"> 

<!-- Navbar -->
	<div class="Navbar">
		<a class="active" href="#Home">Home</a> 
		<a href="#About">About</a>
		<a href="#Profiles">Profiles</a>
		<a href="#Contact">Contact</a>
	</div>

<!-- Home -->
		<br> <!-- Breaks inserted to add space between navbar and first heading -->
		<br>

<!-- Video -->
	<div id="Home">
		<video autoplay muted loop id="Typing_Video"> <!-- Makes the video play automatically, on a loop and with no sound -->
			<source src="../Stylesheet/Video/Typing.mp4" type="video/mp4">
			Your browser does not support HTML5 video. <!-- Display message if video fails to run -->
		</video>
	</div>

<!-- Video text --> 
	<div class="Video_Text"> 
		<h1 style="color:white;">Austin Davis' Portfolio</h1>
			<p> 
				<strong>
					<center>
						<q>If you're going to try, go all the way.
						<br>otherwise, don't even start.
						</q>	
						<br>An excerpt from Roll the Dice by Charles Bukowski<br>
						<br>
						My name is Austin. Welcome to my website.<br>
						<br>Thank you for stopping by! 
					</center>	
				</strong>
			</p> 
	</div>

<!-- About section -->
	<div class="Row" id="About"> 
		<div class="Column_2"> <!-- Left column -->
			<img src="../Stylesheet/Images/pdx copy.jpg" alt="pdx">
		</div>
  
		<div class="Column_1"> <!-- Right column -->
			<h1>About</h1>
				<p>I am a software developer with a focus in the field of data science. As a Pacific Northwest native, I enjoy all things related to the outdoors. <br><br>I am a graduate of <a href="https://www.learncodinganywhere.com" target="_blank">The Tech Academy</a>’s Data Science Boot Camp, trained and experienced in the following web and programming languages: HTML, CSS, JavaScript, SQL, and Python. <br><br>I am an analytical data enthusiast with an MBA who would enjoy working with you on any project you may have. <a href="#Contact">Connect</a> with me below!</p>
		</div>
	</div>

<!-- GitHub section -->
	<div class="Row" id="Profiles">
		<div class="Column_1"> <!-- Left column -->
			<h1>GitHub &amp; Linkedin</h1>
				<p>Below you can access my GitHub and Linkedin Profiles:<br>
					<center><a href="https://github.com/PNWprogrammer?tab=repositories" target="_blank">GitHub Profile</a></center></p>
					<center><a href="https://www.linkedin.com/in/daviswaustin/" target="_blank">Linkedin Profile</a></center></p>
	
		</div>
		
		<div class="Column_2"> <!-- Right column -->
			<a href="../Stylesheet/Images/" target="_blank"><img src="../Stylesheet/Images/Boat Dock.jpeg" alt="Boat Dock"></a>
		</div>
	</div>

<!-- Contact section -->
	<div class="Row" id="Contact"> 
		<div class="Column_3"> <!-- Contact image, left column -->
			<img src="../Stylesheet/Images/Smith Rock.jpeg" alt="Smith Rock">
		</div>
	
		<div class="Column_1"> <!-- Contact form, right "column" -->
			<h1>Contact</h1> 
				<form action="" method="get"> <!-- This specifies where to send the form data and how; it is left blank -->
					<label>Name:</label>
						<input type="text" placeholder="Please enter your name here">
					<label>Email:</label>
						<input type="text" id="Email" name="Email" placeholder="Please enter your email here">
					<label>Message:</label>
						<input type="text" id="Message" name="Message" placeholder="Please write your message here">
						<input type="submit" value="Submit">
				</form>
		</div>
	</div>
	
<!-- Footer section -->
	<footer>
		<p>
			<center>&copy Austin Davis.</center><br>
		</p>
	</footer>

		</body>

</html>
