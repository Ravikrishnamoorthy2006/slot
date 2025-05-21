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
    <table border="4">
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
            <td>Web Development</td>
            <td>Python Programming</td>
            <td>Module Completion</td>
            <td>Assessment Hour</td>
            <td>Module Completion</td>
        </tr>
        <tr>
            <th>10-12</th>
            <td>Module Completion</td>
            <td>Web Development</td>
            <td>Python Programming</td>
            <td>Advanced C Programming</td>
            <td>Web Development</td>
        </tr>
        <tr>
            <th>12-1</th>
            <td colspan="6">L U N C H</td>
        </tr>
        <tr>
            <th>1-3</th>
            <td>Artificial Intelligence</td>
            <td>Advanced C Programming</td>
            <td>Mentor Meet</td>
            <td>Artificial Intelligence</td>
            <td>Assessment Hour</td>
        </tr>
    </table>
</body>
</html>
```


## OUTPUT

![image](https://github.com/user-attachments/assets/20ed3bf5-f386-438f-a6d0-0048182c3769)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
