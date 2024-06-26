# Ex.06 Book Front Cover Page Design
## Date:28-04-24

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
<!DOCTYPE html>
<html>
<head>
    <title>CSE</title>
    <style>
        .bookpage{
            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url(p2.jpg);
            background-size: cover;
        }
        .insight{
            color:darkturquoise;
        }
        .hrstyle{
            width:100px;
        }
        .author{
            display: inline;
            position: relative;
            color:white;
            top:190px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:white;
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 10px;
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
        }
        .pub{
            color:white;
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:white;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        }
        .subtitle{
            color:darkturquoise;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:200px;
        }
        .mypic{
            position: relative;
            top: 105px;
            left: 280px;
            width: 80px;
            height: 80px;
            background-size:contain;
            shape-rendering: crispEdges;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage" style="background-image: url('backpage\ ex-6.webp');">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color:red">
            </div>
            
                    
            
            <div class="id">
                <hr style="color:red">
            </div>
            <div class="author">
               <p><b>Maheswar Reddy</b></p>
            </div>
            <div class="ed">
                <b>Third Edition</b>
            </div>
        </div>
        </body>
</html>

## OUTPUT:
![alt text](ex-06.png)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
