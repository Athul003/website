# website

<!DOCTYPE html>
<html>
<head>
	<style type="text/css">
		body{
			background-color: #707070;
		}
		.textupper{
			text-transform: uppercase;
		}
	</style>
	<title>form</title>
</head>
<body>
	<form name="employ" action="send.php" method="post">

		<table width="100%" border="0" bgcolor="#c0c0c0">
			<tr>
				<td>First Name</td>
				<td><input type="text" name="fname" class="textupper" maxlength="50"></td>
				<td rowspan="6">
				<table width="100%" border="0" bgcolor="#c0c0c0" align="right">
				<tr>
					<td>Already have an account<br>
						<h3><font color="blue"><i>My account</i></font></h3>
					</td>
				</tr>
				<tr>
					<td align="center">
						<img src="unknown.jpg" width="50" height="50">
					</td>
				</tr>
				<tr>
					<td>Mail id</td>
					<td><input type="email" name="uname" maxlength="50"></td>
				</tr>
				<tr>
					<td>Password</td>
					<td><input type="Password" name="Password" minlength="8" maxlength="20"></td>

				</tr>
				<tr><td>
					<a href="#">
					<input type="submit" name="submit" value="Login"></a>
				</td></tr>
			</table></td>
		</tr>
			<tr>
				<td>Last Name</td>
				<td><input type="text" name="lname" class="textupper" maxlength="50"></td>
			</tr>
			<tr>
				<td>Stream</td>
				<td>
					<select name="Stream">
					<option value="me">Mechanical Engg</option>
					<option value="fs">Fire and Safety Engg</option>
					<option value="ce">Civil Engg</option>
					<option value="cs">Computer Science Engg</option>
					<option value="ee">Electrical Engg</option>
					<option value="ec">Electronic Engg</option>
					<option value="it">Information and Technology Engg</option>
				</select>
			</td>
			</tr>
			<tr>
				<td>Clubs</td>
				<td>
					<input type="checkbox" name="iee">IEE
					<input type="checkbox" name="nss">NSS
					<input type="checkbox" name="pm">PROGRAMMER ME

				</td>
			</tr>
			<tr>
				<td>Gender</td>
				<td><input type="radio" name="Gender" value="male">Male
					<input type="radio" name="Gender" value="female">Female
					<input type="radio" name="Gender" value="other">Other</td>
			</tr>
			<tr>
				<td>Suggestions</td>
				<td><textarea name="comments" cols="45" rows="5"></textarea>></td></tr>
				<tr>
					<td><input type="submit" name="submit" value="Submit">
						<input type="reset" name="reset" value="Reset">
					</td>
				</tr>
		</table><br>
		<b><h1>For more details</h1></b>
		<p>
			<iframe src="https://www.bing.com/" width="100%" height="300">
				<p>
					Your browser did not support this version
				</p>
			</iframe>
		</p>
	</form>
<table width="100%" height="60" border="0"  bgcolor="#000000" cellspacing="5" cellpadding="5">
	<tr>
		<td align="center">
			<font face="Verdana,Geneva,sans-serif" color="white">Home - About - Service - Contact<br>
				<br>
				©Athul Cp

			</font></td>
	</tr></table>
</table>
</body>
</html
