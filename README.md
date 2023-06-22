<html>
	<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>Recrutment</title>
		<link rel="stylesheet" href="style.css">
		<script type="text/javascript" src="js/script.js"></script>
	</head>
	<body class="bg">
		<form action="new.php" method="post">
			<h1>Enter following details</h1>

			<label for="name">Name</label><br>
			<input type="text" id="name" name="name" placeholder="Enter name" required  title="Enter your full name"><br><br>
			<label for="usn">USN</label><br>
			<input type="text" id="usn" name="usn" placeholder="Enter usn" title="Enter your valid USN" required ><br><br>
			<label for="phone">phone No</label><br>
			<input type="text" id="phone" name="phone" maxlength="10" pattern="[0-9]" placeholder="Enter phone No" title="Enter your Valid Mobile number" required ><br><br>
			<label for="email">E-Mail</label><br>
			<input type="email" id="name" name="email" placeholder="Enter E-Mail" required ><br><br>
			<label for="gender">Gender</label><br>
			<input type="radio" name="gender" id="male" value='male'>male
			<input type="radio" name="gender" id="female" value='female'>female
			<input type="radio" name="gender" id="others" value='others'>others <br><br>

			<label for="sem" title="slect your semester">Semester</label>
			<select name="sem" id="sem"  required>
				<option value="0">select</option>
				<option value="I">I</option>
				<option value="III">III</option>
				<option value="V">V</option>
				<option value="VII">VII</option>
			</select><br><br>
			<label for="lang" class="la">Select programming language :</label><br>
			<table class="Skill">
				<tbody>
				<tr>
					<td>C/C++</td>
					<td>Java</td>
					<td>Python</td>
					<td>HTML</td>
					<td>CSS</td>
					<td>JS/JavaScript</td>
					<td>DBMS/SQL</td>
					<td>Bootstrap</td>
					<td>ReactJS</td>
					<td>MS-Office Skills</td>
				</tr>
				<tr class="check">
					<td><input type="checkbox" name="skills[]" id="C" value='C/C++'></td>
					<td><input type="checkbox" name="skills[]" id="java"value='Java'></td>
					<td><input type="checkbox" name="skills[]" id="python" value='Python'></td>
					<td><input type="checkbox" name="skills[]" id="HTML" value='HTML'></td>
					<td><input type="checkbox" name="skills[]" id="CSS" value='CSS'></td>
					<td><input type="checkbox" name="skills[]" id="JS" value='JS/JavaScript'></td>
					<td><input type="checkbox" name="skills[]" id="DBMS" value='DBMS/SQL'></td>
					<td><input type="checkbox" name="skills[]" id="Boot" value='BootStrap'></td>
					<td><input type="checkbox" name="skills[]" id="React" value='ReactJs'></td>
					<td><input type="checkbox" name="skills[]" id="MS-office"></td>
				</tr>
			</tbody>
			</table><br><br>
			<textarea name="area" id="are" cols="50" rows="3" placeholder="Any additional skills" title="If you have any Additional skills please type here"></textarea><br><br>
			<div class="button">
			<button type="submit" title="Submit your all filled details">Submit</button>
			<button type="reset" title="Clear the all field">Reset</button></div>
		</form>
	</body>
</html>
