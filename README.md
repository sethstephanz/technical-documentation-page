# technical-documentation-page
From FreeCodeCamp's "Build a Technical Documentation Page" challenge 
<html lang="en">
<!--Head
--————————————————————————————————————————————————————————————————————————————————————————————-->
<head>
	 <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
  <style>
    /*User Story #15: My Technical Documentation page should use at least one media query.*/
@media all and (min-width: 1000px) {
	#box-container {
		display: flex;
		width: 100%;
		height: 1000px;
		flex-direction: column;
	}
	#navbar {
		display: flex;
		background-color: lightgray;
		height: 100%;
		width: 100px;
		justify-content: center;
		position: fixed;
		display: block;
	}
	#body {
		background-color: white;
		display: flex;
		height: 100%;
		width: 100%;
		justify-content: left;
		margin-left: 110px;
	}
}
/*Below 1000px——————————————————————————————————————————————————————————————————————————————————————————————————————*/
@media all and (min-width: 0px) and (max-width: 1000px) {
	#box-container {
		display: flex;
		width: 100%;
		height: 1000px;
		flex-direction: column;
	}
	/*User Story #14: On regular sized devices (laptops, desktops), the element with id="navbar" should be shown on the left side of the screen and should always be visible to the user.*/
	#navbar {
		display: flex;
		background-color: lightgray;
		height: 100%;
		width: 10%;
		justify-content: center;
		min-width: 100px;
		position: fixed;
		display: block;
	}
	#body {
		background-color: white;
		display: flex;
		height: 100%;
		width: 100%;
		justify-content: left;
		margin-left: 110px;
	}
}
  </style>
</head>
<!--Navbar/Header
--————————————————————————————————————————————————————————————————————————————————————————————-->
<div id="box-container">
	<div class="navbar">
		<nav id="navbar"><!--User Story #8: I can see a nav element with a corresponding id="navbar". User Story #12: Each element with the class of nav-link should contain text that corresponds to the header text within each section (e.g. if you have a "Hello world" section/header, your navbar should have an element which contains the text "Hello world")-->
			<header><h1>Steps</h1><br><!--User Story #11: The header element in the navbar must come before any link (a) elements in the navbar.-->
				<a href="#Introduction" class="nav-link" id="Introduction">Introduction</a>
				<a href="#Step_1" class="nav-link" id="Step_1">Step 1</a><!--User Story #10: Additionally, the navbar should contain link (a) elements with the class of nav-link. There should be one for every element with the class main-section. User Story #13: When I click on a navbar element, the page should navigate to the corresponding section of the main-doc element (e.g. If I click on a nav-link element that contains the text "Hello world", the page navigates to a section element that has that id and contains the corresponding header.-->
				<a href="#Step_2" class="nav-link" id="Step_2">Step 2</a>
				<a href="#Step_3" class="nav-link" id="Step_3">Step 3</a>
				<a href="#Step_4" class="nav-link" id="Step_4">Step 4</a>
				<a href="#Step_5" class="nav-link" id="Step_5">Step 5</a>
			</header><!--User Story #9: The navbar element should contain one header element which contains text that describes the topic of the technical documentation.-->
		</nav>
	</div><!--End of navbar div-->
<!--Body
--————————————————————————————————————————————————————————————————————————————————————————————-->
<div id="body"><!--Begin body div-->
<body>
	<main id="main-doc"> <!--User Story #1: I can see a main element with a corresponding id="main-doc", which contains the page's main content (technical documentation).-->
		<h1>Let's Do the Time Warp!</h1>
	<section class="main-section" id="Introduction">
		<header><h2>Introduction</h2></header>
			<p>It's astounding. Time is fleeting. Madness takes its toll. But listen closely—not for very much longer. I've got to keep control.</p>
			<p>I remember doing the Time Warp. Drinking those moments when the blackness would hit me, and a void would be calling.</p>
		<ul><label><h3>Some Quick Things You'll Need/To Be Prepared For:</h3></label> <!--User Story #7: The .main-section elements should contain at least 5 li items total (not each).-->
				<li>A Jump to the Left</li>
				<li>A Step to the Right</li>
				<li>Hands, prefereably on</li>
				<li>Hips, and</li>
				<li>The Pelvic Thrust</li>
		</ul>
	<section class="main-section" id="Step_1"> <!--User Story #2: Within the #main-doc element, I can see several section elements, each with a class of main-section. There should be a minimum of 5. User Story #4: Each section element with the class of main-section should also have an id that corresponds with the text of each header contained within it. Any spaces should be replaced with underscores (e.g. The section that contains the header "Javascript and Java" should have a corresponding id="Javascript_and_Java").-->
		<header><h2>Step 1</h2></header><!--User Story #3: The first element within each .main-section should be a header element which contains text that describes the topic of that section.-->
		<p>It’s just a jump...</p><!--User Story #5: The .main-section elements should contain at least 10 p elements total (not each).-->
		<p>...to the left.</p>
		<code>
		</code>
	</section>
	<section class="main-section" id="Step_2">
		<header><h2>Step 2</h2></header>
		<p>And then a step... </p>
		<p>...to the right.</p>
		<code>
		</code>
	</section>
	<section class="main-section" id="Step_3">
		<header><h2>Step 3</h2></header>
		<p>With your hands... </p>
		<p>...on your hips...</p>
		<code>
		</code>
	</section>
	<section class="main-section" id="Step_4">
		<header><h2>Step 4</h2></header>
		<p>You bring you knees...</p>
		<p>...in tight.</p>
		<code>
		</code>
	</section>
	<section class="main-section" id="Step_5">
		<header><h2>Step 5</h2></header>
		<p>But it’s the pelvic thrust...</p>
		<p>...that really drives you insane.</p>
		<code>
		</code>
		<h2>Let's Do the Time Warp Again!</h2>
	</section>
</div><!--End body div-->
<!--End Document
--————————————————————————————————————————————————————————————————————————————————————————————-->
</div> <!--End of box container-->
</body>
</html>
