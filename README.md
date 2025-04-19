# Ex03 Time Table
## Date: 19.04.2025

NAME : YASHWANTH K

REG NO : 212224040369

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


<!DOCTYPE html>
<html>
<head>
    <title>SLOT TIME TABLE - your name , reg no</title>
    <style>
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 5px auto;
        }

        table + table {
            margin-top: 20px;
        }

        th, td {
            border: 5px solid Black;
            text-align: center;
            padding: 8px;
        }

        img {
            width: 100%;
            height: 15%;
        }

        .center-text {
            text-align: center;
        }
        
        strong {
            font-weight: bold;
            font-size: 30px;
        }
    </style>
</head>
<body>
    <img src="logo.png">
    <div class="center-text">
        <p><strong>SLOT TIME TABLE - YASHWANTH K (212224040369) </strong></p>
    </div>
    <table>
        <tr>
            <th colspan="1" bgcolor="Yellow">Day/Time</th>
            <th colspan="1" bgcolor="Yellow">Monday</th>
            <th colspan="1" bgcolor="Yellow">Tuesday</th>
            <th colspan="1" bgcolor="Yellow">Wednesday</th>
            <th colspan="1" bgcolor="Yellow">Thursday</th>
            <th colspan="1" bgcolor="Yellow">Friday</th>
            <th colspan="1" bgcolor="Yellow">Saturday</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">8-10</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">FOC</th>
            <th colspan="1" bgcolor="Cyan">FOC</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">10-12</th>
            <th colspan="1" bgcolor="Cyan">CS</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
            <th colspan="1" bgcolor="Cyan">GDT</th>
            <th colspan="1" bgcolor="Cyan">EDM</th>
            <th colspan="1" bgcolor="Cyan">GDT</th>
            <th colspan="1" bgcolor="Cyan">QA-I</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">12-1</th>
            <th colspan="6" bgcolor="Cyan">LUNCH</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">1-3</th>
            <th colspan="1" bgcolor="Cyan">EDM</th>
            <th colspan="1" bgcolor="Cyan">PQM</th>
            <th colspan="1" bgcolor="Cyan">MENTOR MEET</th>
            <th colspan="1" bgcolor="Cyan">CS</th>
            <th colspan="1" bgcolor="Cyan">PQM</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
        </tr>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">3-5</th>
            <th colspan="1" bgcolor="Cyan">CHEM</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">CHEM</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
        </tr>
    </table>

    <table>
        <tr>
            <th colspan="1" bgcolor="White">S. No.</th>
            <th colspan="1" bgcolor="White">Subject Code</th>
            <th colspan="2" bgcolor="White">Subject Name</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">1.</th>
            <th colspan="1" bgcolor="White">19AI41</th>
            <th colspan="2" bgcolor="White">Fundamentals of Web Application Development(FWAD)</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">2.</th>
            <th colspan="1" bgcolor="White">19AI302</th>
            <th colspan="2" bgcolor="White">ENGINEERING DESIGN AND MODELLING (EDM)</th>        
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">3.</th>
            <th colspan="1" bgcolor="White">19AI304</th>
            <th colspan="2" bgcolor="White">FUNDAMENTALS OF C PROGRAMMING (FOC)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">4.</th>
            <th colspan="1" bgcolor="White">19CY205</th>
            <th colspan="2" bgcolor="White">Principles of Chemistry in Engineering (CHE)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">5.</th>
            <th colspan="1" bgcolor="White">19MA222</th>
            <th colspan="2" bgcolor="White">PROBABILITY AND QUEUEING MODELS (PQM)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">6.</th>
            <th colspan="1" bgcolor="White">19IT402</th>
            <th colspan="2" bgcolor="White">GAME DEVELOPMENT TECHNOLOGIES (GDT)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="white">7.</th>
            <th colspan="1" bgcolor="white">19EY710</th>
            <th colspan="2" bgcolor="white">QUANTITATIVE ABILITY - I (QA- I)</th>
        </tr>
    </table>
</body>
</html>


## OUTPUT

![Screenshot 2025-04-19 144852](https://github.com/user-attachments/assets/6d113288-e4a7-4a80-b05f-683246cb8c00)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
