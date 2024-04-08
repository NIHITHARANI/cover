# Ex.06 Book Front Cover Page Design
## Date:08-04-2024

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
```
bookc.html

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
            background-image: url(book.jpg);
            background-size: cover;
        }
            
        
        .insight{
            color:blue;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:darkblue;
            top:240px;
            
            font-family:Arial, Helvetica, sans-serif;
            font-size: medium;
        }
        .booktitle{
            color:darkmagenta;
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:darkred;
            font-size: medium;
            position: relative;
            top:180px;
            left:330px;
        }
        .ed{
            color:brown;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:150px;
        
        }
        .subtitle{
            color:darkred;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:60px;
        }
        .mypic{
            position: relative;
            top: 180px;
            left: 260px;
            width: 80px;
            height: 90px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
            
            </div>
            <div class="hrstyle">
                <hr style="color:blueviolet">
            </div>
            <div class="booktitle">
                <h1>FUNDAMENTALS OF PYTHON LANGUAGE</h1></div>
            <div class="subtitle">
                 books for beginners
            </div>
            <div class="subtitle">
                 Top seller of 2024
            </div>

            <div class="mypic">
                <img src="WhatsApp Image 2024-04-08 at 13.52.17_dbdd035e.jpg" width="120" height="100" >
            </div>
            <div class="id">
                <hr style="color:blueviolet">
            </div>
            <div class="author">
               <p><b>NIHITHA RANI B(212223040131)</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION(LIMITED STOCK)</b>
            </div>
        </div>
        </body>
</html>


```


## OUTPUT:
![alt text](co.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
