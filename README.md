# Ex.06 Book Front Cover Page Design
## Date:30.11.2023

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
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:purple;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(./back.jpg);
            background-size: cover;
        }
            

        .insight{
            color: blueviolet;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:yellowgreen;
            top:320px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        
        .id {
            width:400px;
            position: relative;
            top:320px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:285px;
            left:370px;
        }
        .ed{
            color: red;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:220px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 230px;
            left: 260px;
            width: 100px;
            height: 90px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color:grey">
            </div>
            <div class="booktitle">
                <h1>CLOUD COMPUTING</h1></div>
            <div class="subtitle">
                with Google G app
            </div>
            <div class="mypic">
                <img src="mypic.jpg"  width="130" height="170" alt="">
            </div>
            <div class="id">
                <hr style="color: black;">
            </div>
            <div class="author">
               <p><b>SWATHI.S</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Extended Edition</b>
            </div>
        </div>
    </body>
</html>        
```

## OUTPUT:
![Alt text](<Screenshot (47).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
