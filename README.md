<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Personal Portfoliyo</title>
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
	<link rel="stylesheet" type="text/css" href="./CSS/style.css">
</head>
<body>

	<div id="menu-bars" class="fas fa-bars"></div>




	<header>

		<div class="user">
			<img src="./Images/Profile_Picture.jpeg" alt="">
			<h3 class="name">Radha Jangid</h3>
			<p class="post">Data Analyst</p>
		</div>
		<nav class="navbar">
			<a href="#Home">Home</a>
			<a href="#About">About</a>
			<a href="#Skills">Skills</a>
			<a href="#Projects">Projects</a>
			<a href="#Contact">Contact</a>
			
		</nav>
		<div class="follow">
			<a href="https://www.instagram.com/radha.jangid.16121/" class="fab fa-instagram"></a>
			<a href="https://github.com/RadhaJangid" class="fab fa-github"></a>
			<a href="https://www.linkedin.com/in/radha-jangid-a0669a22a/" class="fab fa-linkedin"></a>
			
		</div>
	</header>

	<section class="Home" id="Home">
		<h3>Hi... </h3>
		<h1>My name is <span>Radha Jangid</span></h1>
		<p>I am Seeking for the position of Data Analyst where I can efficiently contribute my skills and abilities!</p>
		<a href="#"download><button class="btn">Resume<i class="fas fa-download"></i></button></a>    
	</section>

	<section class="About" id="About">
		<h1 class="heading"><span>about</span> me </h1>
		<div class="about">
		<div class="container">
			<div class="row">
				<div class="About-col-1">
					<img src="./Images/Profile_Picture_About.jpeg">
				</div>
				<div class="About-col-2">
					<h3></h3>
					<p>Analytically minded entry-level data analyst with a strong background in data 		manipulation  and reporting. 
						Proficient in SǪL, Excel, and Python, adept at creating dashboards and visualizations to present key findings. 
						Motivated to leverage data-driven insights to optimize processes and enhance decision- making.</p>
					<div class="tab-titles">
						<p class="tab-links active-link" onclick="opentab('hobbies')">Hobbies</p>
						<p class="tab-links" onclick="opentab('language')">Language</p>
						<p class="tab-links" onclick="opentab('interest')">Interest</p>
					</div>
					<div class="tab-contents active-tab" id="hobbies"> 
				
						<ul>
							<li><span>Reading spritual books</span></li>
							<li><span>Listening speritual music</span></li>
						</ul>
					</div>
					<div class="tab-contents" id="language">
						<ul>
							<li><span>English</span></li>
							<li><span>Hindi</span></li>
							<li><span>Marwari</span></li>
						</ul>
					</div>
					<div class="tab-contents" id="interest">
						<ul>
							<li><span>AI/ML</span></li>
							<li><span>Data Science</span></li>
						</ul>
					</div>
					
				</div>
				
			</div>
		</div>
	</div>
	</section>
	<section class="Skills" id="Skills">
		<h1 class="heading"> my <span>Skills</span></h1>
		<div class="box-container">
			<div class="box">
				<abbr title="Python">
					<img src="./Images/Python.png" alt="Python"></abbr>
			</div>

			<div class="box">
				<abbr title="SQL">
					<img src="./Images/SQL.png" alt="">
				</abbr>
			</div>

			<div class="box">
				<abbr title="PowerBI">
					<img src="./Images/PowerBI.png" alt=""></abbr>
			</div>
			<div class="box">
				<abbr title="Tableau">
					<img src="./Images/Tableau.png" alt=""></abbr>
			</div>

			<div class="box">
				<abbr title="MySQL">
					<img src="./Images/MySQL.png" alt=""></abbr>
			</div>
			<div class="box">
				<abbr title="Excel">
					<img src="./Images/Excel.png" alt=""></abbr>
			</div>
			<div class="box">
				<abbr title="MongoDB">
					<img src="./Images/MongoDB.png" alt=""></abbr>
			</div>
			<div class="box">
				<abbr title="Data_Modeling">
					<img src="./Images/Data_Modeling.png" alt=""></abbr>
			</div>
			<div class="box">
				<abbr title="Data_Preparation">
					<img src="./Images/Data_Preparation.png" alt=""></abbr>
			</div>
			<div class="box">
				<abbr title="ML">
					<img src="./Images/ML.png" alt=""></abbr>
			</div>
			<div class="box">
				<abbr title="Statistics">
					<img src="./Images/Stastics.png" alt=""></abbr>
			</div>
			<div class="box">
				<abbr title="DAX">
					<img src="./Images/DAX.png" alt="">
					</abbr>
			</div>
		
			<div class="box">
				<abbr title="Seaborn">
					<img src="./Images/Seaborn.png" alt=""></abbr>
			</div>
			<div class="box">
				<abbr title="	Matplotlib">
					<img src="./Images/Matplotlib.png" alt=""></abbr>
			</div>
			<div class="box">
				<abbr title="Pandas">
					<img src="./Images/Pandas.png" alt=""></abbr>
			</div>
			
		</div>
	</section>
		
		
		
	<section class="Education" id="Education">
		<h1 class="heading"> my <span>education</span></h1>
		<div class="box-container">
			<div class="box">
				<i class="fas fa-graduation-cap"> </i>
				<span>2023</span>
				<h3>MCA</h3>
				<p>Banaras Hindu University Varanasi, Uttar Pradesh</p>
	            <p>Master of Computer Applications 2021 – 2023</p>
				
			</div>

			<div class="box">
				<i class="fas fa-graduation-cap"> </i>
				<span>2020</span>
				<h3>BCA</h3>
				<p>G.D. Memorial College Jodhpur, Rajasthan</p>
	            <p>Bachelor of Computer Applications 2017 – 2020</p>
				
			</div>

			<div class="box">
				<i class="fas fa-graduation-cap"> </i>
				<span>2017</span>
				<h3>HSC : PCM</h3>
				<p>Agarwal Jamna Devi Girls SEN. SEC School Jodhpur, Rajasthan</p>
	            <p>Higher Secondary Certificate</p>
	            <p>RBSE – 2017</p>
				
			</div>

			<div class="box">
				<i class="fas fa-graduation-cap"> </i>
				<span>2015</span>
				<h3>SSC</h3>
				<p>K.R. Public SEN. SEC School Jodhpur, Rajasthan</p>
	            <p>Secondary School Certificate </p>
	            <p>RBSE – 2015</p>
			</div>
		</div>
	</section>
	<section class="Projects" id="Projects">
		<h1 class="heading"> my <span>personal projects</span></h1>
		<div class="box-container">
			<div class="box">
				<img src="./Images/Credit_Card_Project1.png" alt="">
			</div>

			<div class="box">
				<img src="./Images/Image_Scrapper.png" alt="">
			</div>

			<div class="box">
				<img src="./Images/OnlineShoppingDataAnalysis.png" alt="">
			</div>

			<div class="box">
				<img src="./Images/Acqusition_Product.png" alt="">
			</div>
			
		</div>
	</section>

	<section class="Contact" id="Contact">
		<h1 class="heading"> contact <span> me </span></h1>
		<div class="row">
			<div class="content">
				<h3 class="title">contact info</h3>
				<div class="info">
					<h3><i class="fas fa-envelope"></i>jangidradha1299@gamil.com</h3>

					<h3><i class="fas fa-phone"></i>+91-9588847950</h3>

					<h3><i class="fas fa-map-marker-alt"></i>jodhpur, rajasthan, india - 342001.</h3>
					
				</div>

				
			</div>
			<form action="" name="submit-to-google-sheet">
				<input type="text" name="Name" placeholder="name" class="box">
				<input type="email" name="Email" placeholder="email" class="box">
				<textarea name="Message" id="" cols="30" rows="10" class="box message" placeholder="message"></textarea>
				<button type="submit" class="btn"> send <i class="fas fa-paper-plane"></i></button>
			</form>
			<span id="msg"></span>
		</div>
	</section>




<script src="./JS/script.js"></script>
<script>
	var tablinks = document.getElementsByClassName("tab-links");
  var tabcontents = document.getElementsByClassName("tab-contents");

  function opentab(tabname){
  	for(tablink of tablinks){
  		tablink.classList.remove("active-link");

  	}

  	for(tabcontent of tabcontents){
  		tabcontent.classList.remove("active-tab");
  		
  	}
  	event.currentTarget.classList.add("active-link");
  	document.getElementById(tabname).classList.add("active-tab");
  }
</script>
</body>
</html>
