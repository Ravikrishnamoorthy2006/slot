# Ex03 Time Table
## Date -14-05-2025

NAME-RAVIKRISHNAMOORTHY D

REG NO-212224040271

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
<!DOCTYPE html>
<html>
<head>
    <title>SLOT TIME TABLE</title>
    <style>
        body {
            text-align: center;
        }
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 20px auto;
        }
        th, td {
            border: 2px solid black;
            padding: 12px;
            text-align: center;
        }
        th {
            background-color: yellow;
            font-weight: bold;
        }
        td {
            background-color: cyan;
        }
        caption {
            font-size: 20px;
            font-weight: bold;
            margin: 10px;
        }
    </style>
</head>
<body>
    <img src="sec-logo-01as.png" alt="" width="645">
    <table>
        <caption>SLOT TIME TABLE - Ravikrishnamoorthy D (212224040271)</caption>
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr>
            <th>8-10</th>
            <td colspan="3">FREE SLOT</td>
            <td>PHY</td>
            <td>CHE</td>
        </tr>
        <tr>
            <th>10-12</th>
            <td>GER</td>
            <td >FREE SLOT</td>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>PHY</td>
        </tr>
        <tr>
            <th>12-1</th>
            <td colspan="5">L U N C H</td>
        </tr>
        <tr>
            <th>1-3</th>
            <td colspan="2">FREE SLOT</td>
            <td>MAT</td>
            <td>MAT</td>
            <td>SS</td>
        </tr>
        <tr>
            <th>3-5</th>
            <td colspan="2">FREE SLOT</td>
            <td>GER</td>
            <td>CHE</td>
            <td>FWAD</td>
        </tr>
    </table>
</body>
</html>
```


## OUTPUT

![Screenshot (276)](https://github.com/user-attachments/assets/47ea7ea2-13b1-4c68-b0c2-6a1828698440)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
