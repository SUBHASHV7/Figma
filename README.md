# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:

~~~
HTML Code:

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DRESTEIN '25</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<div class="container">

    <!-- LEFT PANEL -->
    <div class="panel bg1">
        <img src="logo.png" class="college-logo">
        <h1>DRESTEIN '25</h1>
        <button class="btn">LOGIN</button>
        <p class="footer-text">DREAM DESIGN COMPETE WIN 2025</p>
    </div>

    <!-- EVENTS PANEL -->
    <div class="panel bg2">
        <h2>TECHNICAL EVENTS:</h2>
        <ul>
            <li>➤ Web Nova</li>
            <li>➤ UXellence</li>
            <li>➤ No Code Rush</li>
        </ul>

        <h2>NON - TECHNICAL EVENTS:</h2>
        <ul>
            <li>➤ Logo Rush</li>
            <li>➤ Meme Masters</li>
            <li>➤ BPL Auction</li>
        </ul>
    </div>

    <!-- FORM PANEL -->
    <div class="panel bg3">
        <h2>EVENT REGISTRATION FORM</h2>

        <form>
            <input type="text" placeholder="Name :">
            <input type="text" placeholder="Reg. No. :">
            <input type="text" placeholder="Dept. :">
            <input type="text" placeholder="Event :">
            <button class="btn">REGISTER</button>
        </form>
    </div>

    <!-- THANK YOU PANEL -->
    <div class="panel bg4">
        <div class="thank-box">
            <h3>“Thanks for registering<br>the countdown begins now!”</h3>
            <p>“Get ready — something exciting is waiting for you.”</p>

            <h4>CONTACT US:</h4>
            <p>Email: saveetha123@gmail.com<br>
               Ph: 9845352638, 9346284762</p>
        </div>
    </div>

</div>

</body>
</html>

CSS Code:

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #000;
}

.container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    height: 100vh;
}

.panel {
    position: relative;
    padding: 20px;
    color: #fff;
}

.bg1 { background: url('bg1.jpg') center/cover no-repeat; }
.bg2 { background: url('bg2.jpg') center/cover no-repeat; }
.bg3 { background: url('bg3.jpg') center/cover no-repeat; }
.bg4 { background: url('bg4.jpg') center/cover no-repeat; }

/* Left Panel */
.college-logo {
    width: 200px;
}

h1 {
    font-size: 40px;
    margin: 40px 0;
}

.btn {
    padding: 10px 30px;
    border: none;
    background: #fff;
    color: #000;
    font-weight: bold;
    cursor: pointer;
    border-radius: 5px;
}

/* Events Panel */
h2 {
    margin-bottom: 10px;
    margin-top: 20px;
}

ul {
    list-style: none;
    line-height: 30px;
}

/* Form Panel */
form {
    display: flex;
    flex-direction: column;
    gap: 15px;
    margin-top: 20px;
}

input {
    padding: 10px;
    border-radius: 5px;
    border: none;
    width: 80%;
}

/* Thank You Panel */
.thank-box {
    background: rgba(0,0,0,0.5);
    padding: 20px;
    border-radius: 10px;
    margin-top: 50px;
}


~~~

## OUTPUT:

<img width="1917" height="1198" alt="image" src="https://github.com/user-attachments/assets/5b707476-78a0-4ab6-9951-57e071a5af4f" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
