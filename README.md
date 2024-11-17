# Ex03 Time Table
## Date:12-11-2024

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
        <title>
            TIMETABLE
        </title>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="540">
        </center>
        <h1align ="center">SLOT TIME TABLE SAVISH (24900837)
            <table border="1" cellspacing="15" cellpadding="2">
            <tr bgcolor="purple">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wedsday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>saturday</th>
            </tr>
            <tr>
                <td>8-10</td>
                <td> -- </td>
                <td> --</td>
                <td> --</td>
                <td>-- </td>
                <td>WEB</td>
                <td>-- </td>
                
            </tr>
            <tr>
                <td>10-12</td>
                <td>CARDEV</td>
                <td>DIGELC</td>
                <td>FCPRO</td>
                <td>-- </td>
                <td> --</td>
                <td>STATISTIC</td>

            </tr>
            <tr>
                <td>12-1</td>
                <td colspan="6"> LUNCH</td>
            </tr>
            <tr>
                <td>1-3</td>
                <td>FWEB</td>
                <td>FWEB</td>
                <td>-- </td>
                <td>FCPRO</td>
                <td>DIGIELC</td>
                <td>statistic</td>
            </tr>
            <tr>
                <td>3-5</td>
                <td>--</td>
                <td>--</td>
                <td>CHE</td>
                <td>CHE</td>
                <td>-- </td>
                <td> --</td>
            </tr>
            </table>
        </h1>
    </body>
</html>
<br>
<html>
    <body>
        <table border="1" cellspacing="15" cellpadding="2">
            <caption>SUBJECTS</caption>
            <tr bgcolor="green">
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19MA211</td>
                <td>Statistics and Numerical Methods</td>
            </tr>
            <TR>
                <td>2</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming</td>
            </TR>
            <tr>
                <td>3</td>
                <td>19AI414</td>
                <td>Fundamendal of Web Application Development</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19CY205</td>
                <td>Principle of Chemistry in Engineering</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19EE404</td>
                <td>Digital Electranics</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19EY708</td>
                <td>Career Development Skill</td>
            </tr>
        </table>
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot (35).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
