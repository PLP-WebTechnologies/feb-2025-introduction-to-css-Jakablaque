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

Happy Coding! 💻✨


body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}


main-header {
    background-color: #007bff;
    color: lightblue;
    text-align: center;
    padding: 20px;
    border-bottom: 5px solid #0056b3;
}


/* Style paragraphs using a class */
.text-box {
    color: #333;
    font-size: 18px;
    padding: 15px;
    margin: 20px;
    border: 2px solid #ccc;
    background-color: #ffffff;
    border-radius: 5px;
}

/* Style an image */
.img-style {
    width: 300px;
    height: auto;
    border: 5px solid #007bff;
    border-radius: 10px;
    display: block;
    margin: 20px auto;
    padding: 5px;
    background-color: white;
}


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header id="main-header">
        <h1>Welcome to My Styled Page</h1>
    </header>

    <section>
        <p class="text-box">
            This is a paragraph styled using a CSS class. It has padding, margin, a border, and a background color.
        </p>

        <p class="text-box">
            Another paragraph styled with the same class. Notice the spacing and consistent design.
        </p>

        <img src="image.jpg" alt="Styled Image" class="img-style">
    </section>

</body>
</html>



