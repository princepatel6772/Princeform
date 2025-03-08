<html>

<head>

<title> Registration Form </title>

</head>

<body bgcolor = "aqua">

<h1> <center> Registration Form </center> </h1>

<form name="frmRegistration" action="form.html">

<center>

<table border="0">

<tr>

<td width="20%"> First Name </td>

<td width="5%"> &nbsp; </td>

<td> <input type="textbox" name="txtFirstName"> </td>

</tr>

<tr>

<td> Middle Name </td>

<td>&nbsp; </td>

<td> <input type="textbox" name="txtMiddleName"> </td>

</tr>

<tr>

<td> Last Name </td>

<td>&nbsp; </td>

<td> <input type="textbox" name="txtLastName"> </td>

</tr>

-<tr>

<td> Gender </td>

<td> &nbsp; </td>

<td>

<input type="radio" name="Gender" value="male" Checked> Male

<input type="radio" name="Gender" value="female"> Female

</td>

</tr>

-<tr>
-<tr>

<td> Hobby </td>

<td> &nbsp; </td>

<td>

<input type="checkbox" name="chkSinging" value="Sing" checked> Singing

<input type="checkbox" name="chkDancing" value="Dance "> Dancing

<<input type="checkbox" name="chkReading" value="Read"> Reading

</td>

</tr>

<tr>

<td> Address </td>

<td> &nbsp; </td>

<td>

<textarea name="txtAdd" rows="5" cols="70"> Insert Address </textarea>

</td>

</tr>

<tr>

<td> City </td>

<td> &nbsp; </td>

<td>

<select Name="cmbCity">

<option selected> Ahmedabad </option>

<option> Baroda </option>

<option> Rajkot </option>

<option> Surat </option>

</select>

</td>

</tr>

-<tr>

<td> &nbsp; </td>

<td> &nbsp; </td>

<td>

<input type="submit" name="cmdSubmit" value="Submit">

<input type="reset" name="cmdReset" value="Reset">

</td>

</tr>

</table>

</center>

</form>

</body>

</html>
