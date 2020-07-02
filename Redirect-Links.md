# Redirect Links

## Below is an few examples on how to add a hyperlink reference AKA href to a navigation bar, so you can click each href and have it redirect you to a different portion of your page.

### Example 1
```
<!-- 'Navigation Bar' -->
		<div>
			<ul>
				<li> <a href="#top"> Top of Page </a> </li>
				<li> <a href="#bottom"> Bottom of Page </a> </li>
				<li> <a href="#step1"> Step 1</a> </li>
				<li> <a href="#step2"> Step 2</a> </li>
				<li> <a href="#step3"> Step 3</a> </li>
			</ul>
		</div>
		
		<!-- Contact page (in another html file) -->
		<h1 id = "top">Contact</h1>

		<!-- add the id 'step1' so when you click the link at the top of the page it will redirect you to this portion of the site -->
		<h1 id = "step1">Step 1</h1>
		<h2>You have been redirected to step1 of the page</h2>
		
		
		<h1 id = "step2">Step 2</h1>
		<h2>You have been redirected to Step 2 of the page</h2>

		<br>
		<h1 id = "step3">Step 3</h1>
		<h2>You have been redirected to step 3 of the page</h2>
	
		<h2 id = "bottom">You have been redirected to the bottom of the page</h2>
```