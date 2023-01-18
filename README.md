# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE :
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>SAVEETHA ENGINEERING COLLEGE </title>
        <style>
        table{
            width: 750px;
            border-spacing: 10px;
            border: 3px solid;
        }
        td,th {
            border: 3px solid;
            padding: 10px;
        }
        </style>
    </head>
    <body>
        <img src="/static/image/logo.png" alt="saveethalogo" height="150" width ="1000"/>
         <table>
            <tr>
                <td colspan="10">Time-Table</td>
            </tr>
            <tr>
                <td colspan="5">REG NUMBER : 22002003</td>
                <td colspan="5">NAME : VARSHA</td>
            </tr>
            <tr>
                <td>DAYS</td>
                <td>1</td>
                <td>2</td>
                <td>3</td>
                <td>4</td>
                <td>5</td>
                <td>6</td>
                <td>7</td>
                <td>8</td>
                <td>9</td>   
            </tr>
            <tr>
                <td>MONDAY</td>
                <td>19MA220 - ARCHANA</td>
                <td>19MA220 - ARCHANA</td>
                <td>19AI414 - GOWRIGANESH</td>
                <td>19AI414 - GOWRIGANESH</td>
                <td>LUNCH</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                
            </tr>
            <tr>
                <td>TUESDAY</td>
                <td>-</td>
                <td>-</td>
                <td>19EN610 - MARIYANA</td>
                <td>19EN610 - MARIYANA</td>
                <td>LUNCH</td>
                <td>19AI414 - GOWRIGANESH</td>
                <td>19AI414 - GOWRIGANESH</td>
                <td>19EN101 - HEMALATHA</td>
                <td>19EN101 - HEMALATHA</td>
            </tr>
            <tr>
                <td>WEDNESDAY</td>
                <td>19PH205-</td>
                <td>19PH205-</td>
                <td>19EY701 - PANDIYAN</td>
                <td>19EY701 - PANDIYAN</td>
                <td>LUNCH</td>
                <td>19AI414 - GOWRIGANESH</td>
                <td>19AI414 - GOWRIGANESH</td>
                <td>19MA220 - ARCHANA</td>
                <td>19MA220 - ARCHANA</td>
            </tr>
            <tr>
                <td>THURSDAY</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>19PH214 - RAMKI</td>
                <td>LUNCH</td>
                <td>19MA220 - ARCHANA</td>
                <td>19MA220 - ARCHANA</td>
                <td>19EN101 - HEMALATHA</td>
                <td>19EN101 - HEMALATHA</td>
            </tr>
            <tr>
                <td>FRIDAY</td>
                <td>19EN610 - MARIYANA</td>
                <td>19EN610 - MARIYANA</td>
                <td>19PH214 - RAMKI</td>
                <td>19PH214 - RAMKI</td>
                <td>LUNCH</td>
                <td>19MA220 - ARCHANA</td>
                <td>19MA220 - ARCHANA</td>
                <td>-</td>
                <td>-</td>
            </tr>
        </table>


        <ol type="I">
            <li>19AI414 - Fundamentals Of Web Application Development</li>
            <li>19EN610 - French Basic</li>
            <li>19MA220 - Mpl</li>
            <li>19PH214 - Physics for quantum computing</li>
            <li>19EN101 - Communicative English</li>
            <li>19EY701 - Soft Skill</li>

        </ol>
    </body>
</html>
```

# OUPUT :
## Webpage :

![timetable](https://user-images.githubusercontent.com/119288183/213187861-ddd55a35-2346-40fa-8093-5e28f001de3b.png)


## html validator :

![aaa](https://user-images.githubusercontent.com/119288183/213188073-c3d68c8d-e361-45c1-9242-6aa0d917ea61.png)
