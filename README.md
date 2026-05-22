# Ex02 Time Table
## Date:

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
```html
<!DOCTYPE html>
<html>
<head>
    <title>SLOT TIMETABLE</title>

    <style>

        body{
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            text-align: center;
        }

        h1{
            color: rgb(0, 109, 139);
        }

        h2{
            color: green;
        }

        table{
            margin: auto;
            border-collapse: collapse;
            background-color: white;
        }

        th{
            background-color: #af4c8c;
            color: white;
        }

        th, td{
            border: 2px solid black;
            padding: 10px;
        }

    </style>

</head>

<body>

    <center>
        <img src="image.png" height="100" width="500">
    </center>

    <h1>SAVEETHA ENGINEERING COLLEGE</h1>

    <h2>SLOT TIMETABLE - CHEVURU KOUSHIK (212225240028)</h2>

    <table cellpadding="8" cellspacing="0">

        <tr>
            <th>Day / Time</th>
            <th>8 - 10</th>
            <th>10 - 12</th>
            <th>1 - 3</th>
            <th>3 - 5</th>
        </tr>

        <tr>
            <td>MONDAY</td>
            <td>WEB APPLICATION DEVELOPMENT</td>
            <td>C PROGRAMMING</td>
            <td>COMPUTER NETWORKS</td>
            <td>FREE</td>
        </tr>

        <tr>
            <td>TUESDAY</td>
            <td>CAREER DS</td>
            <td>COMPUTER NETWORKS</td>
            <td>COMPUTER NETWORKS</td>
            <td>FREE</td>
        </tr>

        <tr>
            <td>WEDNESDAY</td>
            <td>COMPUTER NETWORKS</td>
            <td>FREE</td>
            <td>MENTOR MEET</td>
            <td>FREE</td>
        </tr>

        <tr>
            <td>THURSDAY</td>
            <td>WEB</td>
            <td>WEB</td>
            <td>FREE</td>
            <td>FREE</td>
        </tr>

        <tr>
            <td>FRIDAY</td>
            <td>WEB</td>
            <td>FREE</td>
            <td>CAREER DS</td>
            <td>C PROGRAMMING</td>
        </tr>

        <tr>
            <td>SATURDAY</td>
            <td>FREE</td>
            <td>C PROGRAMMING</td>
            <td>FREE</td>
            <td>C PROGRAMMING</td>
        </tr>

    </table>

    <br><br>

    <table cellspacing="2" cellpadding="8">

        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>

        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development</td>
        </tr>

        <tr>
            <td>2</td>
            <td>19AI304</td>
            <td>Fundamentals of C Programming</td>
        </tr>

        <tr>
            <td>3</td>
            <td>19CS406</td>
            <td>Computer Networks</td>
        </tr>

        <tr>
            <td>4</td>
            <td>19EY708</td>
            <td>Career Development Skills</td>
        </tr>

    </table>

</body>
</html
```


## OUTPUT
<img width="1268" height="938" alt="image" src="https://github.com/user-attachments/assets/d49dbb49-a45a-424b-aafb-974d3c0c308d" />



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
