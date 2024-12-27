# Ex.06 Book Front Cover Page Design
## Date:06.12.24

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
    
    <style>
        .container {
            position: relative;
            margin-left: 40%;
            margin-right: 60%;
            width: 300px;
            height: 300px;
            
        }

        .expert-insight {
            position: absolute;
            top: 30px;
            left: 40px;
            color:  red;
            font-style: italic;
            font-size: 16px;

        }
        .background-image
        {
            width: 200%;
            height: 270%;
        }

        .main-title {
            position: absolute;
            top: 115px;
            left: 40px;
            color: red;
            font-style: italic;
            font-size: 36px;
        }
        .photo {
            position: absolute;
            bottom: -440px;
            right: -270px;
            width: 120px;
            height: auto;
        }

        .subtitle {
            position: absolute;
            font-style: italic;
            font-size: 16px;
            top: 300px;
            left: 40px;
            font-weight: lighter;
            color: red;
        }

        .edition {
            position: absolute;
            bottom: -450px;
            left: 40px;
            color: brown;
            font-style: italic;
            font-size: 20px
        }


        .author {
            position: absolute;
            bottom: -520px;
            left: 40px;
            color: brown;
            font-style: italic;
            font-size: 30px;
            
        }
        .SEC{
            position:absolute;
            bottom: -490px;
            right: -220px;
            font-style: italic ;
            font-size: 16px;
            color: pink;
        }
        
    </style>
</head>
<body>
    <div class="container">
        <img  class="photo" src="hemanath.jpg" >
        <img class="background-image" src="web background.avif">
        <p class ="expert-insight"> Be a Brilliant</p>
        <h1 class="main-title" >guide to develop the knowledge</h1>
        <h2 class="subtitle">Step by Step procedure</h2>
        <p class="edition" >second Edition</p>
        <p class="author" >HEMANATH S</p>
        <p class="SEC" >SAVEETHA COLLEGE</p>
    </div>
</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot (20).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
