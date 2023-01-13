# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/images/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - ARYA BAISAKHIYA(22006077)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>FREE SLOT</td>
<td>PYTHON</td>
<td>PHYSICS</td>
<td>FREE SLOT</td>
<td>CHEMISTRY</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>FREE SLOT</td>
<td>FWAD</td>
<td>PYTHON</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td> FREE SLOT</td>
<td>MATH</td>
<td>FREE SLOT</td>
<td>FWAD</td>
<td>MATH</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td> FREE SLOT </td>
<td>PHYSICS</td>
<td>FWAD</td>
<td>CHEMISTRY</td>
<td>FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19CY205</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING(CHEMISTRY)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19PH205</td>
<td>COMPUTATIONAL PHYSICS(PHYSICS)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA201</td>
<td>Calculus and Matrix Algebra (MATHS)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19CS301</td>
<td>PYTHON PROGRAMMING(PYTHON)</td>
</tr>
</table>
</body>
</html>
```
# OUPUT
![OUTPUT](./timetable.png)

# HTML VALIDATOR
![HTML VALIDATOR](./validator.png)

# RESULT
Program is executed successfully