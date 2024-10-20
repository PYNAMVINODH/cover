# Ex.06 Book Front Cover Page Design
## Date:20/10/2024

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
 
<head>
    <title>

        Book Cover
    </title>
    <style>
    .book
        {
            width: 450px;
            height: 600px;
            color:rgb(235, 234, 235);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            background-image: url("6007822.jpg");
            background-size: cover;
        }    
        .insight
        {
            color: silver;
            margin-left: 80px;
            margin-top: 70px;

        }
        .hrstyle
        {
            width:98px;
            margin-left: 70px;

        }
        .booktitle
        {
            font-size: larger;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
            position: relative;
            top: 30px;
            margin-top: 20px;
        }
        .subtitle
        {
            font-family: sans-serif;
            font-size: large;
            position: relative;
            top:50px;
            margin-left: 100px;
            margin-top: 30px;
        }
        .mypic
        {
            position: relative; 
            top: 135px; 
            left: 260px; 
            width: 100px; 
            height: 100px; 
            background-size: cover;
        }
        .id { 
            width:350px; 
            position: relative; 
            margin-left: 30px;
            top:180px;
           
        }
        .author
        {
             display: inline; 
             position: relative; 
             color: rgb(109, 239, 9); 
             top:190px; 
             left:155px;
             font-family:Georgia; 
             font-size: medium;
        }
        .pub
        {
            font-size: medium; 
            position: relative; 
            top:155px; 
            left:330px;
        }
        .ed
        {
            color: silver; 
            font-size: medium; 
            font-family: Verdana;
            position:relative; 
            margin-left: 30px;
            top:85px;
        }

    </style>
</head>
<body>
    <div class="book">
        <div class="insight">
             
        </div>
        <div class="hrstyle"> 
            <hr style="color: red;">
         </div>
        <div class="booktitle">
            FUNDAMENTALS OF WEB APPLICATION
        </div>
        <div class="subtitle">
            RESPONSIVE WEB DESIGN WITH HTML5 AND CSS
        </div>
        <div class="mypic">
            <img src=  "Screenshot 2024-10-21 030851.png" height="140" width="125">
        </div>
        <div class="id">
            <hr style="color: orange;">
        </div>
        <div class="author">
            <p><b>PYNAM VINODH💲</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>🕸️ NO.1 EDITION 👀</b>
        </div>
    </div>
</body>
```


## OUTPUT:
![Screenshot 2024-10-21 031035](https://github.com/user-attachments/assets/c4d947f5-d3a6-47bb-ac6c-98c95ddc9790)




## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
