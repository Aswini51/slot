# Ex03 Time Table
## Date:1/04/2025

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
<body>
    <img src="logo.png">
        <table border="1" cellspacing="10" cellpadding="2">
            <caption>SLOT TIME TABLE - G ASWINI(24000247)</caption>
            <tbody><tr bgcolor="lavender">
               <th bgcolor="violet">DAY/TIME</th>
               <th>Monday</th>
               <th>Tuesday</th>
               <th>Wednesday</th>
               <th>Thursday</th>
               <th>Friday</th>
               <th>Saturday</th>
            </tr>
                <tr bgcolor="beige">
                    <td bgcolor="violet">8-10</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td>ML</td>
                    <td>FREE SLOT</td>
                    <td>FREE SLOT</td>
                </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">10-12</td>
                <td>ADV.C</td>
                <td>CA</td>
                <td>EVS</td>
                <td>MATH</td>
                <td>RA</td>
                <td>MATH</td>
            </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">12-1</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
            </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">1-3</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>SCOFT MM</td>
                <td>ADV.C</td>
                <td>FWAD</td>
                <td>ML</td>
            </tr>
            <tr bgcolor="beige">
                <td bgcolor="violet">3-5</td>
                <td>CHEM</td>
                <td>FREE SLOT</td>
                <td>CA</td>
                <td>CHEM</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
            </tr>
        </tbody></table>
        <table border="1" cellspacing="10" cellpadding="2">
            <tbody><tr bgcolor="sky blue">
                <th bgcolor="sky blue">S.NO</th>
                <th>Course code</th>
                <th>Course name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI305</td>
                <td>ADVANCED C PROGRAMMING</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19AI410</td>
                <td>INTRODUCTION TO MACHINE LEARNING </td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19CS305</td>
                <td>COMPUTER ARCHIETURE</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19CY205</td>
                <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19CY801</td>
                <td>ENVIRONMENTAL SCIENCES AND SUSTAINABILITY</td>
            </tr>
            <tr>
                <td>7.</td>
                <td>19EY709/td>
                <td>REASONING ABILITY</td>
            </tr>
            <tr>
                <td>8.</td>
                <td>ECA-M-SCOFT</td>
                <td>MENTOR MEET</td>
            </tr>
        </body></table>
    
</body></html>
```


## OUTPUT
![alt text](<Screenshot (13).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
