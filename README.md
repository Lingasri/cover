# Ex.06 Book Front Cover Page Design
## Date: 28/04/2024

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cover</title>
    <style>
        main{
            height: 100vh;
            width: 35%;
            margin: auto;
            background-color: #c5e06f;
            position: relative;
            
            /* #93c36d */
        }
        section{
            color: #1d4724;
            position: absolute;
            bottom: 10%;
            right: 5%;
        }
        section h1{
            font-family: 'Copperplate Gothic Light';
            font-size: 4rem;
            margin: 12px;
            margin-left: 0%;
            font-weight:lighter;
        }
        section p{
            font-family: sans-serif;
            font-size: 1.25rem;
            margin: 2px;
            margin-left: 0%;
        }
        #auth{
            font-style: italic;
        }
        .rect{
            background-color: #37de53;
            height: 30px;
            margin-top: 20px;
            width: 100%;
        }
        img{
            height: 200px;
            position: absolute;
            top: 8%;
            right: 10%;
        }
    </style>
</head>
<body>
    <main>
        <img style="border-radius: 50%" src="linga.jpg" alt="">

        <section>
            <p id="auth">By Lingasri</p>
            <h1>THE</h1>
            <h1>DESIGN</h1>
            <h1>HUSTLE</h1>
            <p>Tips & Tricks For</p>
            <p>Design Enterpreneurs</p>
            <div class="rect"></div>
        </section>
    </main>
</body>
</html>
```

## OUTPUT:
![image](https://github.com/Lingasri/cover/assets/143391929/245b7cfa-0df4-41fe-8734-f6bad510d6f0)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
