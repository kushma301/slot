# Ex03 Time Table
## Date: 14.03.2025

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <center>
    <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2025-03-14 154148.png"></center>
    <center><h1>SLOT TIME TABLE - KUSHMA (24013666)</h1></center>
    <center> <table border ="8"></center>
      <tr bgcolor="yellow">
            <td>Day/Time</td>
            <td> Monday</td>
            <td>Tuesday</td>
            <td>Wednesday</td>
            <td>Thursday</td>
            <td>Friday</td>
        </tr>
        <tr bgcolor="aquamarine">
            <td>8-10</td>
            <th colspan="3"> FREE SLOT</th>
            <td>BEEE</td>
            <td>CHE</td>
        </tr>
        <tr bgcolor="pink">
            <td>10-12</td>
            <td>GER</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>BEEE</td>
        </tr>
        <tr bgcolor="blue">
            <td>12-1</td>
            <th colspan="6">LUNCH</th>
        </tr>
        <tr bgcolor="purple">
            <td>1-3</td>
            <th colspan="2"> FREE SLOT</th>
            <td>MAT</td>
            <td>MAT</td>
            <td>C PROGRAM</td>
        </tr>
        <tr bgcolor="green">
            <td>3-5</td>
            <th colspan="2"> FREE SLOT</th>
            <td>GER</td>
            <td>CHE</td>
            <td>FWAD</td>
        </tr>
    </table></center>
    <br>
        <center> <table border ="6"></center>
            <tr>
                <td>S.NO</td>
                <td>Subject code</td>
                <td>Subject name</td>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of web application</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19EN612</td>
                <td>German basic</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19PH206</td>
                <td>Basic electrical and electronics engineering</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19CY205</td>
                <td>Principles of chemistry in engineering</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19MA201</td>
                <td>Calculus and matrix algebra</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19EY701</td>
                <td>Fundamentals of c program</td>
            </tr>
</table>
</body>
</body>
</html>
```

## OUTPUT
![Screenshot 2025-03-14 161902](https://github.com/user-attachments/assets/8ea8e320-2601-4bb8-ba14-a2adb696aae3)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
