# Ex03 Time Table
## Date:26.09.25

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

## PROGRAM
```
<body>
        <center><img src="logo.png" height="100px" width="650px"></center>
        <h3 align="center"> SLOT TIME-TABLE : NIRUDHI (25018753)</h3>
        <table border="1px" align="center" bgcolor="skyblue">
            <tr bgcolor="yellow"><th>DAY/TIME</th><th>MONDAY</th><th>TUESDAY</th><th>WEDNESDAY</th><th>THURSDAY</th><th>FRIDAY</th><th>SATURDAY</th></tr>
            <tr><td align="center" bgcolor="yellow">8-10</td><td align="center">WEB</td><td align="center">-</td><td align="center">-</td><td align="center">DE</td><td align="center">-</td><td align="center">-</td></tr>
            <tr><td align="center" bgcolor="yellow">10-12</td><td align="center">AI</td><td align="center">SE</td><td align="center">WEB</td><td align="center">SE</td><td align="center">-</td><td align="center">ML</td></tr>
            <tr><td align="center" bgcolor="yellow">12-1</td><td align="center" colspan="6">LUNCH BREAK</td>
            <tr><td align="center" bgcolor="yellow">1-3</td><td align="center">CA</td><td align="center">PHY</td><td align="center">MENTOR</td><td align="center">C</td><td align="center">C</td><td align="center">-</td></tr>
            <tr><td align="center" bgcolor="yellow">3-5</td><td align="center">-</td><td align="center">-</td><td align="center">PHY</td><td align="center">-</td><td align="center">WEB</td><td align="center">-</td></tr>
       </table>
       <br>
       <hr>
       <br>
       <table border="1px" align="center">
        <tr><th>S.No</th><th>SUB CODE</th><th>SUBJECT NAME</th></tr>
        <tr><td align="center">01.</td><td align="center">19AI401</td><td align="center">FUNDAMENTAL OF C PROGRAMMING (C)</td></tr>
        <tr><td align="center">02.</td><td align="center">19AI410</td><td align="center">INTRODUCTION TO MACHINE LEARNING (ML)</td></tr>
        <tr><td align="center">03.</td><td align="center">19AI414</td><td align="center"> FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (WEB) </td></tr>
        <tr><td align="center">04.</td><td align="center">19CY205</td><td align="center">PRINCIPLE OF CHEMISTRY IN ENGINEERING (CHE)</td></tr>
        <tr><td align="center">05.</td><td align="center">19CS408</td><td align="center">SOFTWARE ENGINEERING (SE)</td></tr>
        <tr><td align="center">06.</td><td align="center">19EE404</td><td align="center">DIGITAL ELECTRONICS (DE)</td></tr>
        <tr><td align="center">07.</td><td align="center">19PH814</td><td align="center">PHYSICS FOR QUANTUM COMPUTING (PHY)</td></tr>

        </table>
    </body>
</html>
```
## OUTPUT
![Output](png)<img width="1920" height="1200" alt="Screenshot (45)" src="https://github.com/user-attachments/assets/3fa53f7d-2cea-4965-80df-c4ee4e70cffb" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
