# Ex.06 Book Front Cover Page Design
## Date: 09-12-2024

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

book.html
```html
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .bookpage {
            width: 400px;
            height: 600px;
            color: #FFFFFF; /* Light font color for better contrast */
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            background-image: url('file:///C:/college/web/bground.jpg');
            background-size: cover;
            background-position: center;
        }

        .insight {
            color: #FFD700; /* Gold for highlighting */
        }

        .hrstyle {
            width: 100px;
        }

        .author {
            display: inline;
            position: relative;
            color: #D3D3D3; /* Light gray for subtle text */
            top: 230px;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: medium;
        }

        .booktitle {
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
            white-space: nowrap; /* Prevents wrapping */
        }

        .id {
            width: 400px;
            position: relative;
            top: 50px;
        }

        .pub {
            font-size: medium;
            position: relative;
            top: 230px;
            left: 315px;
        }

        .ed {
            color: #D3D3D3; /* Light gray */
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top: 150px;
        }

        .subtitle {
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: large;
            position: relative;
            top: 40px;
        }

        .mypic {
            position: relative;
            top: 230px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
    </style>
    <title>BOOK COVER</title>
</head>
<body>
    <div class="bookpage">
        <div class="insight">INSIGHT</div>
        <div class="hrstyle">
            <hr style="color: white">
        </div>
        <div class="booktitle">
            "The Grace of Waiting"
        </div>
        <div class="subtitle">
            <center>
                Moments That Shape the Soul
            </center>
        </div>
        <div class="mypic">
            <img src="C:\back up\important documents\Passport size photo.jpg" width="125" height="140" alt="">
        </div>
        <div class="id">
            <hr style="color: wheat">
        </div>
        <div class="author">
            <p><b> K S VINAY SUHIRTHAN</b></p>
        </div>
        <div class="pub">
        </div>
        <div class="ed">
            <b>LIMITED EDITION</b>
        </div>
    </div>
</body>
</html>

```
## OUTPUT:

![alt text](<Screenshot 2024-12-09 192051.png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
