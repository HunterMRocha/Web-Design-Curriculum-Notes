# Bootstrap Grid Notes

Below are some basic level notes on how to create a grid using bootstrap

### Make sure you link bootstrap css into your file 
```
	<link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">

```

### Step 1: Create a Container 
```
	<!-- Add all of your grid content inside of this container -->
	<div class = "container">
		
	</div>
```


### Step 2: Create a Row
```
	<div class = "container">
		<!-- This is going to create a single row -->
		<div class="row">
			
		</div>
	</div>
```


### Step 3: Create a Column 
```
	<div class = "container">
		<div class="row">
			<!-- Experiment with your sizing to get the proper dimensions -->
			<div class="col-lg-4">First Column</div>
			<div class="col-md-3">Second Column</div>
			<div class="col-sm-2">Third Column</div>
		</div>
	</div>
```
