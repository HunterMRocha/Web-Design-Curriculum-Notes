# Form Notes

This is a readme file with all the form code we went over on wednesday (07/01/2020) If there are any issues with some of the code please let me know.

## Forms

### Text Input

```
	<!-- action is where the information is going to be sent -->
	<!-- method is what you are going to do with that information -->
	<form action="./board.html" method="POST">
		<!-- child elements -->
		<h1>Form One: </h1>
		<p>This is crucial information for your jop application. Please have this filled out by noon. </p>

		<!-- Text Input -->
		<!-- Label -->
		<label for="meal">What did you have for dinner?</label>
		<!-- "type"  specifies what type of data it is going to render on the webpage and what it is allowed to accept -->
		<!-- without the name attribute information won't be sent to the form -->
		<input type="text" name="first-text-box" value="pre-filled box">
	</form>
```


### Password Input

```
	<!-- NOW LET'S PASSWORD INPUT -->
	<form action="./board.html" method="POST">
		<label for="user-password">Password</label>
		<input type="Password" name="user-password" id="password">
	</form>
```

### Number Input
```
	<form>
		<label for="years">Age</label>
		<!-- By typing in number we're able to restrict what users are able to type in -->
		<input type="number" name="years" step="1">
	</form>
```

### Ranges
```
	<form>
		<label for="volume-level">Volume level: </label>
		<!-- include 'number' before 'range' if you don't want a slider to be displayed -->
		<input type = "number" name="volume-level" type="range" min="0" max="10" step="1">
	</form>
```

### Checkbox Input
```
	<form>
		<p>Forms we went over today: </p>
		<label for="topping">text input</label>
		<input type="checkbox" name="topping">
		<br>

		<label for="topping">radio buttons</label>
		<input type="checkbox" name="topping">
		<br>

		<label for="topping">checkboxes</label>
		<input type="checkbox" name="topping">
		<br>

		<label for="topping">ranges</label>
		<input type="checkbox" name="topping">
		<br>
	</form>
```

### Radio Buttons
```
	<form>
		<p>Gender</p>
		<label for=gender>Male</label>
		<input type="Radio" name="gender">

		<label for="gender">Female</label>
		<input type="Radio" name="gender">

		<label for="gender">Other</label>
		<input type="Radio" name="gender">
	</form>
```

### Dropdown list 
```
	<form>
		<label for="dinner">What do you want for Dinner</label>
		<select name="dinner">
			<option value="steak">Steak</option>
			<option value="ribs">Ribs</option>
			<option value="oc">Orange Chicken</option>
			<option value ="sw">Sandwhiches</option>
		</select>
	</form>

```

### Datalist
```
	<form>
		<label for="city">Ideal city to visit</label>
		<input type="text" name="city" list="cities">

		<datalist>
			<option value="New York City"></option>
			<option value="Tokyo"></option>
			<option value="Mexico City"></option>
		</datalist>
	</form>
```

### Text Area Input Box
```
	<form>
		<label for="posts">Write a post: </label><br>
		<textarea name="posts" rows="10" cols="100"></textarea>
	</form>
```

### Submit Form
```
	<form>
		<input type="submit" name="Send">
	</form>
```

### Required Form 
```
	<form action="./contact.html" method="POST">
		<label for="allergies">Do you have allergies? </label>
		<br>
		<!-- by using required the user has to insert something -->
		<input name="allergies" type="text" required>
		<br>
		<input type="submit" name="Submit">	
	</form>
```

### Minimum Character Input
```
	<form>
		<label for="bio">Create a bio with less than 10 characters:</label>
		<br>
		<!-- maxlength is total number of characters -->
		<input type="text" name="bio" min="1" maxlength="10" required>
	</form>
```

### Pattern Matching 
```
	<form>
		<label for="payment">Credit Card Number (no spaces)</label>
		<br>
		<!-- [0-9] indicate what values you are able to use -->
		<!-- {14,16} tell you that you have to submit a number between 14-16 -->
		<input type="text" name="payment" required pattern="[0-9]{14,16}">
		<input type="submit" value="submit">
	</form>
```

