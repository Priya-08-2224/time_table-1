# Ex03 Time Table
# Date: 07/10/2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using ```<table>``` tag in html.

## STEP 4
Add header row using ```<th>``` tag.

## STEP 5
Add your timetable using ```<td>``` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en-us">
    <center>
        <img src="download.png">
    </center>


<head>
        <title> time table </title>
        <style>
         table,th,td{
        text-align: center;
        border: 3px solid rgb(9, 9, 9);
       }
        </style>
    </head>
    <body>
        <center>
        <h2 style="text-align: center;">time table-priyadharshini J 24901116</h2>
       <table>
        
        <tr>
            <th style="background-color: rgb(0, 255, 208);">day</th> 
            <th style="background-color: rgb(0, 255, 208);" >8-10</th>
            <th style="background-color: rgb(0, 255, 208);">10-12</th>
            <th rowspan=7>l<br>u<br>n<br>c<br>h<br></th>
            <th style="background-color: rgb(0, 255, 208);" >1-3</th>                    
            <th style="background-color: rgb(0, 255, 208);">3-5</th>
        </tr>
        <tr>
            <td style="background-color: rgb(232, 157, 132);">monday</td>
            <td style="background-color: bisque;"></td>
            <td style="background-color: bisque;">19AI414 </td>
            <td style="background-color: bisque;"></td>
            <td style="background-color: bisque;"></td>
        </tr>
        <tr>
            <td style="background-color:rgb(232, 157, 132) ;">tuesday</td>
            <td style="background-color: bisque;"></td>
            <td style="background-color: bisque;">19AI403</td>
            <td style="background-color: bisque;">19AI301C</td>
            <td style="background-color: bisque;"></td>
        </tr>
        <tr>
            <td style="background-color: rgb(232, 157, 132);">wednesday</td>
            <td style="background-color: bisque;">19AI301C</td>
            <td style="background-color: bisque;">19EE404</td>
            <td style="background-color: bisque;">mentor meet</td>
            <td style="background-color: bisque;">19CY205</td>
        </tr>
        <tr>
            <td style="background-color: rgb(232, 157, 132);">thursday</td>
            <td style="background-color: bisque;"></td>
            <td style="background-color: bisque;">19AI301C</td>
            <td style="background-color: bisque;">19AI414</td>
            <td style="background-color: bisque;"></td>
        </tr>
        <tr>
            <td style="background-color: rgb(232, 157, 132);">friday</td>
            <td style="background-color: bisque;"></td>
            <td style="background-color: bisque;"></td>
            <td style="background-color:bisque ;">19AI403</td>
            <td style="background-color: bisque;"></td>
        </tr>
        <tr>
            <td style="background-color: rgb(232, 157, 132);">saturday</td>
            <td style="background-color: bisque;">19EE404</td>
            <td style="background-color: bisque;">19AI301C</td>
            <td style="background-color: bisque;">19CY205</td>
            <td style="background-color: bisque;">19AI414</td>
        </tr>
    </table>
</center>

<br>
<br>

<center>                                                                                 
<table>
    <tr>
        <th style="background-color: rgb(27, 173, 158);">s.no</th>
        <th style="background-color: rgb(27, 173, 158);">subject code</th>
        <th style="background-color: rgb(27, 173, 158);">subject name</th>
    </tr>
    <tr>
        <th style="background-color: rgb(209, 146, 177);">1</th>
        <th style="background-color:olivedrab ;">19AI301C</th>
        <TH style="background-color: olivedrab;">python and linear algebra</TH>
    </tr>
    <tr>
        <th style="background-color:rgb(209, 146, 177);">2</th>
        <th style="background-color: olivedrab;">19AI403</th>
        <TH style="background-color: olivedrab;">introduction to data science</TH>
    </tr>
    <tr>
        <th style="background-color: rgb(209, 146, 177);">3</th>
        <th style="background-color: olivedrab;">19AI414</th>
        <th style="background-color: olivedrab;">fundamentals of web application development</th>
    </tr>
    <tr>
        <th style="background-color: rgb(209, 146, 177);">4</th>
        <th style="background-color: olivedrab;">19CY205</th>
        <th style="background-color: olivedrab;">principles of chemistry in engineering</th>
    </tr>
    <tr>
        <th style="background-color: rgb(209, 146, 177);">5</th>
        <th style="background-color: olivedrab;">19EE404</th>
        <th style="background-color: olivedrab;">digital electronics</th>
    </tr>
    <tr>
        <th style="background-color: rgb(209, 146, 177);">6</th>
        <th style="background-color: olivedrab;">ECA-M-SCOFT</th>
        <th style="background-color: olivedrab;">mentor meet</th>
    </tr>
</table>
</center>
</body>
</html>
```
# OUTPUT
![alt text](<Screenshot (24).png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
