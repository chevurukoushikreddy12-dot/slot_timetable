# Ex02 Time Table
## Date:22-05-2026

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
    <title>Neon Timetable Design</title>

    <style>

        body{
            margin: 0;
            padding: 20px;
            font-family: Arial, sans-serif;
            background-color: #0f172a;
            color: white;
            text-align: center;
        }

        h1{
            color: #00ffff;
            font-size: 42px;
            text-shadow: 0px 0px 10px cyan;
        }

        h2{
            color: #ff66ff;
            margin-bottom: 30px;
            text-shadow: 0px 0px 8px pink;
        }

        img{
            border-radius: 15px;
            box-shadow: 0px 0px 20px cyan;
            margin-bottom: 20px;
        }

        table{
            width: 90%;
            margin: auto;
            border-collapse: collapse;
            margin-bottom: 40px;
            background-color: #111827;
            box-shadow: 0px 0px 20px rgba(0,255,255,0.4);
            border-radius: 15px;
            overflow: hidden;
        }

        th{
            background-color: #06b6d4;
            color: black;
            padding: 15px;
            font-size: 18px;
        }

        td{
            padding: 14px;
            border: 1px solid #334155;
            font-weight: bold;
        }

        tr:hover{
            background-color: #1e293b;
            transition: 0.3s;
            transform: scale(1.01);
        }

        /* Day Colors */

        .monday{
            color: #ff4d4d;
        }

        .tuesday{
            color: #ffb84d;
        }

        .wednesday{
            color: #ffff66;
        }

        .thursday{
            color: #66ff99;
        }

        .friday{
            color: #66ccff;
        }

        .saturday{
            color: #d580ff;
        }

        /* Subject Colors */

        .sub1{
            background-color: #1e293b;
            color: #ff6666;
        }

        .sub2{
            background-color: #1e293b;
            color: #66ff99;
        }

        .sub3{
            background-color: #1e293b;
            color: #66ccff;
        }

        .sub4{
            background-color: #1e293b;
            color: #ffff66;
        }

    </style>

</head>

<body>

    <img src="image.png" height="120" width="550">

    <h1>SAVEETHA ENGINEERING COLLEGE</h1>

    <h2>SLOT TIMETABLE - CHEVURU KOUSHIK (212225240028)</h2>

    <table>

        <tr>
            <th>Day / Time</th>
            <th>8 - 10</th>
            <th>10 - 12</th>
            <th>1 - 3</th>
            <th>3 - 5</th>
        </tr>

        <tr class="monday">
            <td>MONDAY</td>
            <td>WEB</td>
            <td>C PROGRAMMING</td>
            <td>COMPUTER NETWORKS</td>
            <td>FREE</td>
        </tr>

        <tr class="tuesday">
            <td>TUESDAY</td>
            <td>CAREER DEVELOPMENT SKILLS</td>
            <td>COMPUTER NETWORKS</td>
            <td>COMPUTER NETWORKS</td>
            <td>FREE</td>
        </tr>

        <tr class="wednesday">
            <td>WEDNESDAY</td>
            <td>COMPUTER NETWORKS</td>
            <td>FREE</td>
            <td>MENTOR MEET</td>
            <td>FREE</td>
        </tr>

        <tr class="thursday">
            <td>THURSDAY</td>
            <td>WEB</td>
            <td>WEB</td>
            <td>FREE</td>
            <td>FREE</td>
        </tr>

        <tr class="friday">
            <td>FRIDAY</td>
            <td>WEB</td>
            <td>FREE</td>
            <td>CAREER DEVELOPMENT SKILLS</td>
            <td>C PROGRAMMING</td>
        </tr>

        <tr class="saturday">
            <td>SATURDAY</td>
            <td>FREE</td>
            <td>C PROGRAMMING</td>
            <td>FREE</td>
            <td>C PROGRAMMING</td>
        </tr>

    </table>

    <table>

        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>

        <tr class="sub1">
            <td>1</td>
            <td>19AI414</td>
            <td>WEB</td>
        </tr>

        <tr class="sub2">
            <td>2</td>
            <td>19AI304</td>
            <td>Fundamentals of C Programming</td>
        </tr>

        <tr class="sub3">
            <td>3</td>
            <td>19CS406</td>
            <td>Computer Networks</td>
        </tr>

        <tr class="sub4">
            <td>4</td>
            <td>19EY708</td>
            <td>Career Development Skills</td>
        </tr>

    </table>

</body>
</html>
```


## OUTPUT
<img width="1303" height="953" alt="{E6B59B09-96EA-4C8A-A408-313B9B2E6A94}" src="https://github.com/user-attachments/assets/a15c2a79-e96a-4aef-b57c-3b980984b149" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
