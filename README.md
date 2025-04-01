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




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Web Page</title>
    <!-- Linking the external CSS file -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header id="main-header">
        <h1>Welcome to My Styled Page</h1>
    </header>
    
    <nav class="main-nav">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    
    <main>
        <section class="content-section">
            <h2>About Us</h2>
            <p>This is a demonstration of how CSS can improve the appearance of a web page.</p>
            <p class="highlight"> selectors, colors, fonts, and spacing to create a more visually appealing layout.</p>
        </section>
        
        <section class="content-section">
            <h2>Featured Image</h2>
            <img src="https://via.placeholder.com/400x300" alt="Placeholder image" class="featured-image">
            <p>This image has custom styling applied through CSS.</p>
        </section>
    </main>
    
    <footer id="main-footer">
        <p>&copy; 2023 Styled Web Page. All rights reserved.</p>
    </footer>
</body>
</html>



CSS

/* Element selector - styles all instances of this HTML element */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

/* ID selector - styles the element with this specific ID */
#main-header {
    background-color: #2c3e50;
    color: #ecf0f1;
    text-align: center;
    padding: 1.5rem;
    margin-bottom: 1.5rem;
}

/* Class selector - styles all elements with this class */
.content-section {
    background-color: white;
    border-radius: 5px;
    padding: 1.5rem;
    margin: 1rem auto;
    width: 80%;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.highlight {
    background-color: #fffde7;
    padding: 0.5rem;
    border-left: 4px solid #ffd600;
}

/* Styling the navigation */
.main-nav {
    background-color: #34495e;
    padding: 0.5rem;
}

.main-nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 0;
}

.main-nav li {
    margin: 0 1rem;
}

.main-nav a {
    color: #ecf0f1;
    text-decoration: none;
    font-weight: bold;
}

.main-nav a:hover {
    color: #f39c12;
}

/* Image styling */
.featured-image {
    display: block;
    margin: 1rem auto;
    border: 3px solid #3498db;
    border-radius: 8px;
    max-width: 100%;
    height: auto;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

/* Footer styling */
#main-footer {
    text-align: center;
    padding: 1rem;
    background-color: #2c3e50;
    color: #ecf0f1;
    margin-top: 2rem;
}

/* Using a different font for headings */
h1, h2 {
    font-family: 'Georgia', serif;
    color: #2c3e50;
}

h2 {
    border-bottom: 2px solid #eee;
    padding-bottom: 0.5rem;
}



