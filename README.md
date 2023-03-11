# medical-login-form
Using HTML and CSS to develop Login form
<!DOCTYPE html>
<html>
<head>
	<title>Medical Login Form</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<form>
		<h2>Medical Login</h2><u>
		<label for="username"><b>Username</b></label>
		<input type="text" placeholder="Enter Username" id="username" required>

		<label for="password"><b>Password</b></label>
		<input type="password" placeholder="Enter Password" id="password" required>

		<button type="submit">Login</button>
	</form>

	<script src="script.js"></script>
</body>
</html>

* {
	box-sizing: border-box;
}

body {
	margin: 0;
    background-color: khaki; 
	font-family: Arial, Helvetica, sans-serif;
}

form {
	margin: 20px auto;
	width: 400px;
	padding: 20px;
	border: 1px solid #ccc;
	border-radius: 10px;
	background-color: #f5f5f5;
}

h2 {
	margin-top: 0;
}

input[type=text], input[type=password] {
	width: 100%;
	padding: 12px 20px;
	margin: 8px 0;
	display: inline-block;
	border: 1px solid #ccc;
	border-radius: 4px;
	box-sizing: border-box;
}

button[type=submit] {
	background-color: darkblue;
	color: white;
	padding: 14px 20px;
	margin: 8px 0;
	border: none;
	border-radius: 4px;
	cursor: pointer;
	width: 100%;
}

button[type=submit]:hover {
	background-color: #45a049;
}

@media screen and (max-width: 600px) {
	form {
		width: 100%;
	}
}
