# Ex09 Event Registration Web Application
# Date:23/12/2025
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
~~~
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-small">
      <img class="image" src="img/image-1.png" />
      <img class="img" src="img/image-2.png" />
      <img class="rectangle" src="img/rectangle-1.svg" />
      <div class="text-wrapper">login/Register</div>
      <img class="image-2" src="img/image-4.png" />
      <div class="div">cricket registration</div>
    </div>
  </body>
</html>


@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

.android-small {
  background-color: #15ff04;
  overflow: hidden;
  width: 100%;
  min-width: 360px;
  min-height: 640px;
  position: relative;
}

.android-small .image {
  top: 104px;
  left: -890px;
  width: 540px;
  height: 109px;
  aspect-ratio: 4.97;
  position: absolute;
  object-fit: cover;
}

.android-small .img {
  top: 0;
  left: 4px;
  width: 356px;
  height: 71px;
  aspect-ratio: 4.97;
  position: absolute;
  object-fit: cover;
}

.android-small .rectangle {
  position: absolute;
  top: 301px;
  left: 105px;
  width: 149px;
  height: 37px;
}

.android-small .text-wrapper {
  position: absolute;
  top: 312px;
  left: 143px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.android-small .image-2 {
  top: 312px;
  left: 0;
  width: 360px;
  height: 328px;
  aspect-ratio: 1;
  position: absolute;
  object-fit: cover;
}

.android-small .div {
  position: absolute;
  top: 113px;
  left: 25px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}
~~~
# OUTPUT:

![alt text](<Screenshot 2025-12-23 102150.png>)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
