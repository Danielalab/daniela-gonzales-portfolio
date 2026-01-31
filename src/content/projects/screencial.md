---
title: "Rippling Lights"
description: "This project is a web application designed to simulate a mesmerizing rippling effect on a string of virtual Christmas lights. It showcases advanced front-end skills in managing animation timing, user input, and dynamic styling using pure CSS and JavaScript."
image: "https://private-user-images.githubusercontent.com/32286663/543159733-d4ed7bf1-ed6f-4e16-8422-c2baddb00356.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Njk4MjgxMTMsIm5iZiI6MTc2OTgyNzgxMywicGF0aCI6Ii8zMjI4NjY2My81NDMxNTk3MzMtZDRlZDdiZjEtZWQ2Zi00ZTE2LTg0MjItYzJiYWRkYjAwMzU2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjAxMzElMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwMTMxVDAyNTAxM1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTNiMWNiOWI3MmI3NDQ1MDhlMWIxMjA0ZjI5MTc5OGQ3NGJmZGMzZWM3YzkwMjI5ZmExY2FkYTY1N2NkYmY1YjYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.v7agYQVvqHXguU87xdixKCEZs7sXAuyesU3fPohridw"
skills: ["CSS", "DOM", "HTML", "JavaScript"]
demoLink: "https://danielalab.github.io/Christmas-Lights/index.html"
sourceLink: "https://github.com/Danielalab/Christmas-Lights"
---

## Overview

This project is a web application designed to simulate a mesmerizing rippling effect on a string of virtual Christmas lights. It showcases advanced front-end skills in managing animation timing, user input, and dynamic styling using pure CSS and JavaScript.

### Core Functionality

- Rippling Animation: The application draws a sequence of circles (lights) and dynamically changes their intensity in a continuous, sequential pattern. When one circle brightens, its immediate predecessor returns to its standard intensity, creating the visual effect of light "traveling" down the string.
- Start/Stop Control: The user has control over the animation via a dedicated button to start or pause the display.
- Adjustable Timing: The user can specify the time interval (in milliseconds) that controls the speed of the intensity change, allowing for faster or slower rippling.

#### 🌟 Bonus Features Implemented

- Intensity Control: Users can specify the exact brightness value (e.g., a CSS filter or opacity value) when a light is "on."
- Dynamic Count: The application allows the user to specify the number of "GLOVES" (lights) included in the display, making the array length flexible.

### Technology
- HTML5 / DOM:	Used to structure the light components. The application dynamically generates the specified number of "lights" based on user input (the "GLOVES" feature).
- JavaScript (ES6+):	Manages the core logic, including the timer function (setInterval), handling user input, and updating the state of each light in the sequence. Directly manipulates the light elements' classes or inline styles to trigger the intensity changes.
- CSS3 Animation:	Used to create the smooth transition effect when a light brightens or dims.