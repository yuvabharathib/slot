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
<html>
     <head>
              <title> ex3 </title>
     </head>
     <body bgcolor="purple" TEXT="white">
<center>
     <img src="/static/images/sec.png"  height="100" width="900" align="center" /></center>
          
          <table border= "5" cellspacing="1px" cellpadding="12px" bgcolor=green" align="center" >
          <CAPTION align=“top”> SLOT TIME TABLE - PANIMALAR P(22009107) </CAPTION>
          <br>
          <br>
               <tr> 
               <th bgcolor="purple">DAY/TIME </th>
               <th bgcolor="dark pink">MONDAY </th>
               <th bgcolor="dark pink">TUESDAY </th>
               <th bgcolor="dark pink">WEDNESDAY </th>
               <th bgcolor="dark pink">THURSDAY </th>
               <th bgcolor="dark pink">FRIDAY </th>
               </tr>
               <tr>
                <th bgcolor="dark pink"> 8-10 </th>
                <td> -- </td>
                <td> PHYSICS </td>
                <td> -- </td>
                <td> FWAD </td>
                <td> FWAD </td>
               </tr>
               <tr>
                <th bgcolor="dark pink"> 10-12 </th>
                <td> -- </td>
                <td> -- </td>
                <td> -- </td>
                <td> -- </td>
                <td> -- </td>
               </tr>
               <tr>
                <th bgcolor="dark pink"> 12-1 </th>
                 <td colspan="5" align="center">LUNCH TIME</td>
               </tr>
               <tr>
                <th bgcolor="dark pink"> 1-3 </th>
                <td> STATISTICS </td>
                <td> -- </td>
                <td> FWAD </td>
                <td> PHYSICS </td>
                <td> C NETWORK </td>
               </tr>
               
              
              <tr>
               <th bgcolor="dark pink"> 3-5 </th>
               <td> C PROGRAMMING </td>
               <td> STATISTICS</td>
               <td> C NETWORK</td> 
               <td> C PROGRAMMING </td> 
               <td> -- </td>
              </tr>
           </table>
            <table border= "4" cellspacing="2px" cellpadding="12px"  align="center" >
           <tr>
           <th> S.No </th>
           <th> SUBJECT CODE </th>
           <th> SUBJECT NAME </th>
           </tr>
           <tr> 
           <td> 1. </td>
           <td> 19AI414 </td>
           <td> FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT </td>
           </tr>
           <tr>
           <td> 2. </td>
           <td> 19AI303 </td>
           <td> ENGINEERING MECHANICS AND PRODUCT DEVELOPMENT </td>
           </tr>
           <tr>
           <td> 3. </td>
           <td> 19AI304 </td> 
           <td> FUNDAMENDALS OF C PROGRAMMING </td>
           </tr>
           <tr>
           <td> 4. </td>
           <td> 19PH214 </td>
           <td> PHYSICS FOR QUANTUM COMPUTING </td>
           </tr>
           <tr>
           <td> 5. </td>
           <td> 19CS406 </td>
           <td> COMPUTER NETWORK</td>
           </tr>
           <tr>
           <td> 6. </td>
           <td> 19MA211 </td>
           <td> STATISTICS AND NUMERICAL METHODS</td>
           </tr>
           </table>
              
        </body>
</html>
```
## OUTPUT




## HTML VALIDATOR



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
