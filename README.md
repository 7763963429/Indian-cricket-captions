!doctype html>
<html>
<head>
</head>
<body>
<h1>Online Job Registration Portal</h1>
<b>Register yourself to get new job updates</b><hr>
<table cellspacing="20">
<form action="success.html" method="post">
<tr>
<th><label for="fn">Full Name:</label></th><td><input type="text" id="fn" placeholder="First Name" required></td>
<td><input type="text" id="fn" name="last name" placeholder="Last Name" required></td></tr>
<tr><th><label for="ad">Address:</label></th><td colspan="2"><input type="text" id="ad" placeholder="street Address"required maxlength="25" size="64"></td></tr>
<tr><td></td><td colspan="2"><input type="text" id="ad" placeholder="street Address Line 2" required maxlength="25" size="64"></td></tr>
<tr><td></td><td><input type="text" id="ad" placeholder="City"required ></td>
<td><input type="text" id="ad" placeholder="State" required></td></tr>
<tr><td></td><td><input type="text" id="ad" placeholder="Pincode" required></td>
<td><select required>
<option value="">Please Select your Country</option>
<option>India</option>
</select></td></tr>
<tr><th><label for="pn">Phone Number:</label></th><td><input type="text" id="pn" placeholder="Area Code"></td><td><input type="text" id="fn"
 placeholder="Phone Number"></td></tr>
<tr><th><label for="mb">Mobile:</label></th><td><input type="text" id="mb" maxlength="10" required></td></tr
<tr><th><label for="em">E-mail:</label></th><td><input type="email" id="em" placeholder="ex:myname@example.com" required></td></tr>
<tr><th>Area Of Interest:</th>
<td><input type="checkbox">Account Manager</td></tr>
<tr><td></td><td><input type="checkbox">Administrative</td></tr><br>
<tr><td></td><td><input type="checkbox">Human Resources</td></tr>
<tr><td></td><td><input type="checkbox">sales</td></tr>
<tr><td></td><td><input type="checkbox">Information Technology</td></tr>
<tr><th>Desired Nature of Job:</th>
<td><input type="radio" name="rad1">Full time</td></tr>
<tr><td></td><td><input type="radio" name="rad1">Part time</td></tr>
<tr><th>skill Level:</th><td><select required>
<option value=""></option>
<option>Undergraduate</option>
<option>Graduate</option>
<option>Post-graduate</option>
<option>Diploma/Technical</option>
</select></td></tr>
<tr><th>Cover Letter:</th>
<td><textarea rows="8" cols="35" placeholder="Describe yourself in brief(max.450 chracters)" maxlength="450"></textarea></td></tr>
<tr><th>Resume:</th><td><input type="file"></td></tr>
<tr><td></td><td><input type="submit" value="Submit Form"></td><td><input type="reset" value="Reset"></td></tr>
</form></table>
</body>
</html>
