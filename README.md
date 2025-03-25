# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Webpage</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking the external CSS file -->
</head>
<body>
    <h1 class="title">Welcome to My Styled Page</h1>
    <p id="intro">This page demonstrates the use of external CSS.</p>
    <img src="https://via.placeholder.com/400" alt="Placeholder Image" class="styled-image">
    
    <div class="content">
        <p>Enjoy exploring the various styles applied here!</p>
    </div>
</body>
</html>
/* General body styling */
body {
    font-family: 'Arial', sans-serif; /* Different font */
    background-color: #f0f8ff; /* Light blue background for aesthetics */
    margin: 0;
    padding: 20px;
}

/* Selector 1: Class */
.title {
    color: #2e8b57; /* Sea green text color */
    text-align: center;
    font-size: 32px;
    margin-bottom: 20px;
}

/* Selector 2: ID */
#intro {
    color: #4682b4; /* Steel blue text color */
    font-size: 20px;
    margin: 10px 0;
    padding: 10px;
    border: 2px solid #87ceeb; /* Sky blue border */
    border-radius: 5px; /* Rounded corners */
}

/* Selector 3: Class for the image */
.styled-image {
    display: block;
    margin: 20px auto;
    border: 4px solid #ff4500; /* Orange red border */
    border-radius: 10px; /* Rounded corners */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Drop shadow */
}

/* Additional styling for content */
.content {
    margin: 20px auto;
    padding: 15px;
    border: 2px dashed #2f4f4f; /* Dark slate gray dashed border */
    max-width: 600px;
    background-color: #ffffff; /* White background */
    color: #000000; /* Black text */
}
