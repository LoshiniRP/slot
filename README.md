# Ex03 Time Table
## Date: 20.09.2025

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
<html>
    <head>
        <title>SLOT TIMETABLE</title>
    </head>

    <body bgcolor="pink">
        <img src="logo.png" width="1500" height="100">
        <h1 align="center">SLOT TIME TABLE - R P LOSHINI(25002119)</h1>

        <table bgcolor="orange" border="3" cellspacing="10" cell padding="5" >
            <tr bgcolor="purple">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <th bgcolor="purple">8-10</th>
                <td colspan="2">Free Period</td>
                <td>Web</td>
                <td colspan="2">Free Period</td>
                <td>Web</td>
            </tr>
            <tr>
                <th bgcolor="purple">10-12</th>
                <td>Pyt</td>
                <td>Eng</td>
                <td>Web</td>
                <td>Eng</td>
                <td colspan="2">Free Period</td>
            </tr>
            <tr>
                <th bgcolor="purple">12-1</th>
                <td colspan="6" align="center">Lunch</td>
            </tr>
            <tr>
                <th bgcolor="purple">1-3</th>
                <td>Pyt</td>
                <td>Pyt</td>
                <td>Mentor meet</td>
                <td>Pyt</td>
                <td>Web</td>
                <td>Web</td>
            </tr>
            <tr>
                <th bgcolor="purple">3-5</th>
                <td>Eng</td>
                <td>Eng</td>
                <td>Eng</td>
                <td>Pyt</td>
                <td>Free Period</td>
                <td>Eng</td>
            </tr>
        </table>

        <br>

        <table bgcolor="red" border="3" cellspacing="10" cell padding="5">
            <tr bgcolor="blue">
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development(Web)</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI301</td>
                <td>Python Programming</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (28).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
