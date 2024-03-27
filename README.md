# Ex03 Time Table
## Date:25.03.2024

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
<head>
    <title>SEC SLOT TIMETABLE</title>
</head>
<center>
<img src="/static/logo.png" width='600'align="center">
</center>
<body>
    <table BORDER='3' width='600'bgcolor='white' cellspacing='3' align="center">
        <CAPTION align="above">SLOT TIMETABLE- AISHWARYA V(212223220003)</CAPTION>
        <tr>
            <th align="center" bgcolor="lightblue">Day/Time</th>
            <th align="center" bgcolor="lightblue">Monday</th>
            <th align="center" bgcolor="lightblue">Tuesday</th>
            <th align="center" bgcolor="lightblue">Wednesday</th>
            <th align="center" bgcolor="lightblue">Thursday</th>
            <th align="center" bgcolor="lightblue">Friday</th>
            <th align="center" bgcolor="lightblue">Saturday</th>
        </tr>

        <tr>
            <th align="center" bgcolor="lightblue">8-10</th>
            <td align="center" bgcolor="lightpink" colspan="2">Digital Electronics</td>
            <td align="center" bgcolor="lightpink">Fundamentals of Web Development</td>
            <td align="center" bgcolor="lightpink">Free slot</td>
            <td align="center" bgcolor="lightpink">Algebra and number theory</td>
            <td align="center" bgcolor="lightpink">Principles of Chemistry</td>
        </tr>

        <tr>
            <th align="center" bgcolor="lightblue">10-12</th>
            <td align="center" bgcolor="lightpink">Creative Skills</td>
            <td align="center" bgcolor="lightpink">Fundamentals of Web Development</td>
            <td align="center" bgcolor="lightpink">Free slot</td>
            <td align="center" bgcolor="lightpink">Python Programming</td>
            <td align="center" bgcolor="lightpink">Digital Electronics</td>
            <td align="center" bgcolor="lightpink">Free slot</td>
        </tr>

        <tr>
            <th align="center" bgcolor="lightblue">12-1</th>
            <td align="center" bgcolor="lightpink" colspan="6">LUNCH</td>
        </tr>

        <tr>
            <th align="center" bgcolor="lightblue">1-3</th>
            <td align="center" bgcolor="lightpink">Fundamentals of Web Development</td>
            <td align="center" bgcolor="lightpink">Principles of Chemistry</td>
            <td align="center" bgcolor="lightpink">Python Programming</td>
            <td align="center" bgcolor="lightpink">Algebra and number theory</td>
            <td align="center" bgcolor="lightpink">Operating System</td>
            <td align="center" bgcolor="lightpink">Free slot</td>
        </tr>


        <tr>
            <th align="center" bgcolor="lightblue">3-5</th>
            <td align="center" bgcolor="lightpink">Operating System</td>
            <td align="center" bgcolor="lightpink">Free Slot</td>
            <td align="center" bgcolor="lightpink">Digital Electronics</td>
            <td align="center" bgcolor="lightpink">Computer Networks</td>
            <td align="center" bgcolor="lightpink" >Free slot</td>
            <td align="center" bgcolor="lightpink" >Computer Networks</td>
        </tr>
    </table>

    <table border="3" width="600" cellspacing="3" cellpaddling="3" align="center">

        <tr>
            <th align="center">S.NO</th>
            <th align="center">SUBJECT CODE</th>
            <th align="center">subject name</th>
        </tr>

        <tr>
            <td align="center">1</td>
            <td align="center">19AI414</td>
            <td align="center">Fundamental of Web Application Development(FWAD)</td>
        </tr>

        <tr>
            <td align="center">2</td>
            <td align="center">19AI301</td>
            <td align="center">Python Programming</td>
        </tr>

        <tr>
            <td align="center">3</td>
            <td align="center">19EY702</td>
            <td align="center">Creative Skills</td>
        </tr>

        <tr>
            <td align="center">4</td>
            <td align="center">19AI521</td>
            <td align="center">Computer Networks</td>
        </tr>

        <tr>
            <td align="center">5</td>
            <td align="center">19CY205</td>
            <td align="center">Principles of Chemistry</td>
        </tr>

        <tr>
            <td align="center">6</td>
            <td align="center">19MA212</td>
            <td align="center">Algebra and number theory</td>
        </tr>
        <tr>
            <td align="center">6</td>
            <td align="center">19EE404</td>
            <td align="center">Digital Electronics</td>
        </tr>
        <tr>
            <td align="center">6</td>
            <td align="center">19CS405</td>
            <td align="center">Operating System</td>
        </tr>
    </body>
    </html>
```

## OUTPUT
![Screenshot 2024-03-27 162558](https://github.com/aishaishwaryav/slot/assets/151565589/565cd717-ce4a-4cc8-a1b3-e58de21b7519)

![Screenshot 2024-03-27 162131](https://github.com/aishaishwaryav/slot/assets/151565589/11442c82-b16d-46de-8061-78659bd42d04)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
