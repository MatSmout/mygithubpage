mygithubpage
============
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<!-- saved from url=(0037)http://users.aber.ac.uk/dkm2/cs15020/ -->
<html xmlns="http://www.w3.org/1999/xhtml"><!--

	http://www.aber.ac.uk/~dcswww/Dept/Teaching/CourseNotes/current/CS15020/assignments/CS15020-assignment-2.pdf

	--><head><meta http-equiv="Content-Type" content="text/html; charset=ISO-8859-1">
		
		<link rel="stylesheet" type="text/css" href="./CS15020 Assignment 2_files/style.css">
		<title>CS15020 Assignment 2</title>


		<script type="text/javascript">
		//<![CDATA[
		function displayName(){
			name = document.getElementById("name").value;
			
			var d = new Date();
			var hours = d.getHours();

			if (hours >= 3 && hours < 12){
				// Morning
				alert("Good morning, " + name);
			}

			if (hours >= 12 && hours < 18){
				// Afternoon
				alert("Good afternoon, " + name);
			}

			if (hours >= 18 || hours < 3){
				// Evening
				alert("Good evening, " + name);
			}


		}

		function lastMod(){
			document.getElementById("lastModified").innerHTML = document.lastModified.toLocaleString();
		}
		//]]>
		</script><style type="text/css"></style>

	</head>

	<body onload="lastMod();">

		<div id="wrapper">


			<div id="header">
				<h2>DKM2's CS15020 - Assignment 2</h2>
			</div>

			<div id="content">
				<h3>Welcome</h3>
				<p>
					<input type="text" id="name" name="name" value="Enter your name...">
					<input type="submit" onclick="displayName();">
				</p>

				<h4>Declaration of Originality</h4>
				<p>
					<em>I declare that the contents of this site are entirely my own work, except for the ideas behind layout CSS obtained from <a href="http://www.456bereastreet.com/lab/developing_with_web_standards/csslayout/2-col/">456bereastreet.com</a></em>
				</p>
			</div>

			<div id="sidemenu">
				<ul>
					<li><a href="http://users.aber.ac.uk/dkm2/wordpress/">Wordpress Blog</a></li>
					<li><a href="http://users.aber.ac.uk/dkm2/webshop/catalog/">OSCommerce</a></li>
					<li><a href="http://users.aber.ac.uk/dkm2/cs15020/cv.html">CV</a></li>
					<li><a href="http://users.aber.ac.uk/dkm2/cs15020/about.html">CS1520 Assignment 2 Write-up</a></li>
				</ul>
			</div>

			<div id="footer">
				<hr>
				<p>
					The information provided on this and other pages by me, Daniel Monaghan (dkm2@aber.ac.uk), is under my own personal responsibility and not that of Aberystwyth University. Similarly, any opinions expressed are my own and are in no way to be taken as those of A.U.

					<br><br>
					<em>This page was last modified on: <span id="lastModified">11/06/2014 15:10:18</span></em>
					<br><br>
				    <a href="http://validator.w3.org/check?uri=referer"><img src="./CS15020 Assignment 2_files/valid-xhtml10" alt="Valid XHTML 1.0 Strict" height="31" width="88"></a>
				      <a href="http://jigsaw.w3.org/css-validator/check/referer">
					    <img style="border:0;width:88px;height:31px" src="./CS15020 Assignment 2_files/vcss-blue" alt="Valid CSS!">
					</a>
				</p>
			</div>


		</div>
	

	
</body></html>
