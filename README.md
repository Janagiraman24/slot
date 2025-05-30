# Ex03 Time Table
## Date:14.05.2025

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
<title>Slot Timetable</title>
</head>
<body>
    <center>
        <img src="/static/logo.png" height="100" width="540">
    </center>
    <br>
    <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="Skyblue">
    <caption><b>SLOT TIME TABLE-JANAGIRAMAN.M(212224230101)</b></caption>
    <tr align="center">
        <th style="background-color: blue; color: white;">Day/Time</th>
        <th style="background-color: blue; color: white;">Monday</th>
        <th style="background-color: blue; color: white;">Tuesday</th>
        <th style="background-color: blue; color: white;">Wednesday</th>
        <th style="background-color: blue; color: white;">Thursday</th>
        <th style="background-color: blue; color: white;">Friday</th>
        <th style="background-color: blue; color: white;">Saturday</th>
    </tr>
    <tr align="center">
        <th style="background-color: blue; color: white;">8-10</th>
        <td>Web development</td>
        <td>Task completion</td>
        <td>Assessment hour</td>
        <td>Task presentation</td>
        <td>Task completion</td>
        <td rowspan="6" style="text-align:center;">Module<br>assessment<br>completion</td>
    </tr>
    <tr align="center">
        <th style="background-color: blue; color: white;">10-12</th>
        <td>Task assignment</td>
        <td>Web development</td>
        <td>Task presentation</td>
        <td>Module completion</td>
        <td>Web development</td>
    </tr>
    <tr align="center">
        <th style="background-color: blue; color: white;">12-1</th>
        <td colspan="5" style="text-align:center;">Lunch Hour</td>
    </tr>
    <tr align="center">
        <th style="background-color: blue; color: white;">1-3</th>
        <td>Fundamentals of AI</td>
        <td>Module completion</td>
        <td>Mentors meet</td>
        <td>Fundamentals of AI</td>
        <td>Task completion</td>
    </tr>
    </table>

    <br>

    <table align="center" cellspacing="2" cellpadding="4" border="2" style="margin-top:20px;">
        <tr align="center">
            <th>S.No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td align="center">1.</td>
            <td align="center">19AI414</td>
            <td align="center">Fundamentals of web development</td>
        </tr>
        <tr>
            <td align="center">3.</td>
            <td align="center">19EE305</td>
            <td align="center">Basi Electrical, Electronics and Measurement Engineering</td>
        </tr>
        <tr>
            <td align="center">4.</td>
            <td align="center">19AI305</td>
            <td align="center">Advanced c programming</td>
        </tr>
        <tr>
            <td align="center">5.</td>
            <td align="center">19MA222</td>
            <td align="center">Probability and Queueing Models</td>
        </tr>
        <tr>
            <td align="center">6.</td>
            <td align="center">19PH214</td>
            <td align="center">Physics for Quantum computing</td>
        </tr>
        <tr>
            <td align="center">7.</td>
            <td align="center">19CS305</td>
            <td align="center">Computer Architecture</td>
        </tr>
        <tr>
            <td align="center">8.</td>
            <td align="center">19AI410</td>
            <td align="center">Introduction to Machine Learning</td>
        </tr>
        <tr>
            <td align="center">9.</td>
            <td align="center">19AI403</td>
            <td align="center">Introduction to data science</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-05-14 175741.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
