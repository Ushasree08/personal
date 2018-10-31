<html>
<head><title>Tour and travel</title>
<style>
body{
background-image:url("world.jpg");
background-repeat:no repeat;
}
</style>
</head>
<body align="center" size="5">
<form name="personal" method="post" action="insert.php">
<table align="center" color="yellow">
<th colspan="2">Personal details</th>
<tr><td>Name</td><td><input type="text" name="name"></td></tr>
<tr><td>Age</td><td><input type="text" name="age"></td></tr>
<tr><td>Email-id</td><td><input type="text" name="email"></td></tr>
<tr><td>Gender</td><td><input type="radio" name="Female">Female
<input type="radio" name="male">Male</td></tr>
<tr><td>Phone no</td><td><input type="number" name="no"></td></tr>
<tr><td>Address</td><td><textarea name="addre"></textarea></td></tr>
<tr><td><input type="submit" name="submit" value="Submit"></td>
<td align="center"><input type="reset" name="reset" value="Reset"></td>
</table>
</form>
</br></br></br>
<a href="new.php"><font size="5">Back to previous page</font></a>
</body>
</html>
