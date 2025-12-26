# Ex03 Time Table
## Date:12.12.2025

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
        <img src="logo.png" height="100" width="800">
    </center>    
    <table border="4" cellpadding="10" cellspacing="0" bgcolor="cyan" align="center">
        <tr>
            <th bgcolor="cyan">Day/Time</th>
            <th bgcolor="yellow">8-10</th>
            <th bgcolor="yellow">10-12</th>
            <th bgcolor="yellow">12-1</th>
            <th bgcolor="yellow">1-3</th>
            <th bgcolor="yellow">3-5</th>
        </tr>
        <tr>
            <td bgcolor="yellow">Monday</td>
            <td>Public Speaking</td>
            <td>WEB</td>
            <td  rowspan="6">Break</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td bgcolor="yellow">Tuesday</td>
            <td>-</td>
            <td>-</td>
            
            <td>Public Speaking</td>
            <td>Python Programming</td>
        </tr>
        <tr>
            <td bgcolor="yellow">Wednesday</td>
            <td>Public Speaking</td>
            <td>Python Programming</td>
            
            <td>Mentor Meet</td>
            <td>WEB</td>
        </tr>
        <tr>
            <td bgcolor="yellow">Thursday</td>
            <td>WEB</td>
            <td>-</td>   
        
            <td>Public Speaking</td>
            <td>Python Programming</td>

            
        </tr>
        <tr>
            <td bgcolor="yellow">Friday</td>
            <td>-</td>
            <td>-</td>
            
            <td>WEB</td>
            <td>WEB</td>
            
        </tr>
        <tr>
            <td bgcolor="yellow">Saturday</td>
            <td>-</td>
            <td>-</td>
            <td>Python Programming</td> 
            <td>Python Programming</td>
        </tr>
            
            

            

        
        

       

        
    </table>
</body>
</html>
```


## OUTPUT
<img width="1281" height="768" alt="Screenshot 2025-12-12 142001" src="https://github.com/user-attachments/assets/51b28d10-7fb4-4c2b-b369-2d6d8b05df4a" />



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
