# Ex09 Event Registration Web Application
## Date:12-10-2025

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
```

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Saveetha College Event</title>
<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        font-family: Arial, sans-serif;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: flex-start;
        background-color: #000;
    }

    .phone {
        width: 360px;
        height: 760px;
        border: 2px solid #333;
        border-radius: 30px;
        overflow: hidden;
        margin: 20px;
        position: relative;
    }

    .screen {
        width: 100%;
        height: 100%;
        text-align: center;
        color: white;
        display: flex;
        flex-direction: column;
        justify-content: center;
        background-size: cover;
        background-position: center;
    }

    /* EVENTS SCREEN */
    .events {
        background-image: url('Screenshot 2025-10-10 211344.png');
    }

    .events h1 {
        margin-top: 30px;
        font-size: 28px;
        color: white;
    }

    .events p {
        font-size: 22px;
        color: red;
        font-weight: bold;
        margin: 15px 0;
    }

    /* COMPETITIONS SCREEN */
    .competitions {
        background-image: url('Screenshot 2025-10-10 211405.png');
    }

    .competitions h1 {
        font-size: 26px;
        color: deeppink;
        font-weight: bold;
        margin-top: 40px;
    }

    .competitions p {
        font-size: 22px;
        color: blue;
        font-weight: bold;
        margin: 12px 0;
    }

    /* THANK YOU SCREEN */
    .thankyou {
        background-image: url('Screenshot 2025-10-10 211418.png');
    }

    .thankyou h2 {
        font-size: 26px;
        color: white;
        margin-bottom: 20px;
    }

    .thankyou p {
        font-size: 20px;
        color: white;
        margin: 10px 0;
        font-weight: bold;
    }
</style>
</head>
<body>

<!-- EVENTS SCREEN -->
<div class="phone">
    <div class="screen events">
        <h1>EVENTS</h1>
        <p>Dance</p>
        <p>Music</p>
        <p>DJ</p>
        <p>Competitions</p>
        <p>Prize distributions</p>
    </div>
</div>

<!-- COMPETITIONS SCREEN -->
<div class="phone">
    <div class="screen competitions">
        <h1>COMPETITIONS</h1>
        <p>Football</p>
        <p>Basketball</p>
        <p>Volleyball</p>
        <p>Cricket</p>
        <p>Badminton</p>
        <p>Chess</p>
    </div>
</div>

<!-- THANK YOU SCREEN -->
<div class="phone">
    <div class="screen thankyou">
        <h2>Thank you</h2>
        <p>We are waiting for your participation</p>
        <p>Come soon and join....</p>
    </div>
</div>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Saveetha Engineering College Event</title>
<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: black;
        font-family: Arial, sans-serif;
    }

    .phone {
        width: 360px;
        height: 760px;
        border: 2px solid #333;
        border-radius: 30px;
        overflow: hidden;
        position: relative;
        background-color: #fff;
    }

    .screen {
        width: 100%;
        height: 100%;
        background-image: url('Screenshot 2025-10-10 211329.png');
        background-size: cover;
        background-position: center;
        text-align: center;
        position: relative;
    }

    .college-header {
        width: 100%;
        padding: 10px;
        background: white;
    }

    .register-btn {
        position: absolute;
        top: 45%;
        left: 50%;
        transform: translate(-50%, -50%);
        background-color: #2b56e0;
        color: white;
        padding: 15px 40px;
        font-size: 20px;
        border: none;
        border-radius: 4px;
        cursor: pointer;
        font-weight: bold;
        letter-spacing: 1px;
    }

    .register-btn:hover {
        background-color: #1f3cb8;
    }
</style>
</head>
<body>

<div class="phone">
    <div class="screen">
        <div class="college-header">
            <img src="https://www.saveetha.ac.in/images/sec_logo.png" alt="Saveetha Engineering College Logo" width="100%">
        </div>

        <button class="register-btn">REGISTER</button>
    </div>
</div>

</body>
</html>


```
## OUTPUT:
![alt text](<Screenshot 2025-10-10 211344.png>)
![alt text](<Screenshot 2025-10-10 211405.png>)
![alt text](<Screenshot 2025-10-10 211418.png>)
<img width="355" height="763" alt="Screenshot 2025-10-10 211329" src="https://github.com/user-attachments/assets/b157fc8a-b0f8-45b0-a004-34ec06f07b1d" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
