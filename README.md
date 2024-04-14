# Ex.06 Book Front Cover Page Design
## Date:14.04.2024

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
<html>

<head>
    <title>IT</title>
    <style>
        .bookpage{

            width: 400px;
            height: 650px;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Roquen';
            background-image: url("360_F_265323269_QoipYNMdd97ZbQJGlSN5TLBXxRUoe0ju.jpg");
            background-size: cover;
        }
            
        
        .insight{
            color:white;
        
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
            font-family: 'sans-serif';
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
            top:90px;
        
        }
        .subtitle{
            color:white);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 145px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
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
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>HTML5 and CSS3 Essentials: Building Modern Websites</h1></div>
            <div class="subtitle">
                Learn the fundamentals of HTML5 and CSS3 to create visually stunning and responsive websites.
            </div>
            <div class="subtitle">
                <h1 align="center">Top seller of 2024</h1>
            </div>

            <div class="mypic">
                <img src="my photo.jpg" width="100" height="120" >
            </div>
            <div class="id">
                <hr style="color:rgb(12, 132, 217)">
            </div>
            <div class="author">
               <p><b>Hafeezul Deen S</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Extended EDITION</b>
            </div>
        </div>
        </body>
        

</html>
```

## OUTPUT:
![Screenshot 2024-04-15 013601](https://github.com/Hafeezuldeen/cover/assets/144979314/53219a15-945b-4de7-b718-3fbdef7d1018)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
