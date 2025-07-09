# Styled_Profile_Card
## Date: 08/07/2025

## Objective:
To practice HTML and CSS fundamentals by designing a visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques.

## Tasks:
#### 1. Create the HTML Structure:
Use ```<!DOCTYPE html>, <html>, <head>, and <body>``` to define the structure.
Add a ```<title>``` like "My Profile Card".

#### 2. Add Content:
Include name, title (e.g., Developer, Student), and a short bio using semantic tags such as ```<h1>```, ```<h2>```, and ```<p>```.

#### 3. Add a Profile Image:
Use the ```<img>``` tag to include a profile picture with appropriate alt, width, and height attributes.

#### 4. Apply Background Color:
Use a CSS class to style the card with a background color.

#### 5. Style Typography:
Use CSS to apply different font families, sizes, and text colors for the name and bio.

#### 6. Add Spacing:
Apply margin and padding to improve spacing between elements using CSS.

#### 7. Center the Card:
Use flexbox or margin: auto to center the card vertically and horizontally on the page.

#### 8. Add Hover Effects:
Enhance interactivity with simple hover effects like border changes or background transition using CSS.

## HTML Code:
/* style.css */

body {
    background-color: #f0f2f5;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: #333;
}

h1 {
    color: #2c3e50;
    font-size: 2.8em;
    text-align: center;
    border-bottom: 2px solid #3498db;
    padding-bottom: 10px;
    margin-bottom: 20px;
}

h2 {
    color: #3498db;
    font-size: 2em;
    text-align: center;
    margin-top: 20px;
    margin-bottom: 15px;
}

img {
    border-radius: 50%;
    height: 200px;
    width: 200px;
    object-fit: cover;
    display: block;
    margin: 20px auto;
    border: 5px solid #3498db;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
}

h3 {
    padding-left: 25px;
    padding-bottom: 5px;
    font-size: 1.6em;
    color: #2c3e50;
}

p {
    padding: 20px 35px;
    line-height: 1.8;
    font-size: 1.1em;
    background-color: #ecf0f1;
    border: 1px solid #bdc3c7;
    border-radius: 8px;
    margin: 20px 0;
    color: #555;
}

ul {
    line-height: 1.6;
    font-size: 1.1em;
    padding-left: 50px;
    list-style-type: square;
    color: #444;
}

footer {
    text-align: center;
    margin-top: 40px;
    padding: 20px;
    background-color: #34495e;
    color: white;
    font-size: 0.9em;
    border-radius: 8px;
}

section {
    margin: 30px auto;
    padding: 20px;
    max-width: 800px;
    background-color: white;
    border-radius: 10px;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
    transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
}

section:hover {
    transform: translateY(-5px);
    box-shadow: 0 12px 25px rgba(0, 0, 0, 0.25);
}


## Output:
![image](https://github.com/user-attachments/assets/38c3af91-8ae4-40f1-b7be-14ec3012361e)


## Result:
A visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques is designed.
