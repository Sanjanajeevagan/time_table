# Ex03 Time Table
# Date:1.04.25
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>slot timtable</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <center>
        <img src="/static/logo.png" height="100" width="540">
    </center>
    <h3>Slot timetable</h3>
    <table allign="center" cellspacing="2" cellpadding="4" border="4"> 
        <tr>
            <th bgcolour="yellow"time</th>
            <th bgcolour="yellow"monday</th>
            <th bgcolour="yellow"tuesday</th>
            <th bgcolour="yellow"wednesday</th>
            <th bgcolour="yellow"thursday</th>
            <th bgcolour="yellow"friday</th>
            <th bgcolour="yellow"saturday</th>
        </tr>
        <tr>
            <td>8-10</td>
            <td>Beee</td>
            <td>ui&ux</td>
            <td>free slot </td>
            <td>ui&ux</td>
            <td>free slot</td>
            <td>free slot</td>
        </tr>
        <tr> 
            <td>10-12</td>
            <td>fwad</td>
            <td>software engineering</td>
            <td>computer networks</td>
            <td>beee</td>
            <td>human values</td>
        </tr>
        <tr>
            <td colspan="7" style="font-size: x-large;">L U N C H </td>
        </tr>
        <tr>
            <td>1-3</td>
            <td>software engineering</td>
            <td>fundamentals of c</td>
            <td>mentor meet</td>
            <td>beee</td>
            <td colspan="2">fwad</td>
        </tr>

    </table>
    <br>
    <table allign="center" cellspacing="2" cellpadding="6" border="4" class="a">
        <tr>
            <th>S.NO</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>
        <tr> 
            <td>1</td>
            <td>19AI414</td>
            <td>fundamentals of web application development</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI304</td>
            <td>fundamentals of c programming </td>
        </tr>
        <tr>
            <td>3</td>
            <td>19EE305</td>
            <td>BEEE</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19CS406</td>
            <td>computer networks</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19HS801</td>
            <td>Human values and professional ethics</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19CS408</td>
            <td>software engineering</td>
        </tr>
        <tr>
            <td>7</td>
            <td>19CS549</td>
            <td>ui & ux design</td>
        </tr>
    </table>
    
</body>
</html>

CSS

body{
    background-color:hsl(310, 15%, 68%);
}
table{
    width:80%;
    height:300px;
    border:10px solid #4ad1afe7;
    border-collapse:collapse;
    margin:auto;
    background-color: blanchedalmond ;
}
th,td{
    border:5px solid rgb(50, 4, 4);
    padding:30px;
    text-align:center;
    font-style: oblique;
    font-family: Georgia, 'Times New Roman', Times, serif;

}
th{
    background-color: hsl(71, 55%, 62%);
    font-style:italic;
    font-weight: 900;
    font-size:large;
}
h3{
    font-weight: bolder;
    font-size:xx-large;
    color: rgb(0, 0, 0);
    text-align: center;
}
.a{
    width:50%;
    height:200px;
    border:10px solid rgba(0, 0, 0, 0.907);
    border-collapse:collapse;
    margin:auto;
    background-color: hsl(335, 62%, 56%)

}
.a th{
    background-color: hsl(183, 72%, 37%);

}
```
# OUTPUT
![Screenshot 2025-04-02 220329](https://github.com/user-attachments/assets/7e0f8af9-94a3-4b43-b32b-a7e4a57b0743)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
