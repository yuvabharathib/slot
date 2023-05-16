# Ex03 Time Table

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## CODE
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
<caption><b>SLOT TIME TABLE - YUVABHARATHI>B(22002787)</b></caption>
<tr align="center">
<th bgcolor="red">Day/Time</th>
<th bgcolor="red">Monday</th>
<th bgcolor="red">Tuesday</th>
<th bgcolor="red">Wednesday</th>
<th bgcolor="red">Thursday</th>
<th bgcolor="red">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>Digital electronics</td>
<td>Physics</td>
<td>FREE SLOT</td>
<td>WEB</td>
<td>WEB</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>FREE SLOT</td>
<td>DATA SCIENCE</td>
<td>OS</td>
<td>DIGITAL ELECTRONICS</td>
<td>DATA SCIENCE</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>OS</td>
<td>FREE SLOT</td>
<td>WEB</td>
<td>PHYSICS</td>
<td>FREE SLOT</td>

</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>STATISTICS</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>STATISTICS</td>
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
<td align="center">19AI403</td>
<td>INRODUCTION TO DATA SCIENCE</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19PH214</td>
<td>PHYSICS FOR QUANTUM COMPUTING</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19MA211</td>
<td>STATISTICS AND NUMERICAL METHODS</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EE404</td>
<td>DIGITAL ELECTRONICS (ENG)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19CS405</td>
<td>OPERATING SYSTEM (SS)</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![WhatsApp Image 2023-05-15 at 9 46 44 PM](https://github.com/yuvabharathib/slot/assets/113497404/4065d728-d7f0-4374-883f-c86d4330ddd1)





## HTML VALIDATOR
![image](https://github.com/yuvabharathib/slot/assets/113497404/2760548f-6d49-462c-af8e-0c7b6381b6d8)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
