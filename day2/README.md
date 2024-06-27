# Day 2 CSS Details

The body selector targets the entire body of the HTML document.
It sets the font family and the background color of the page.

    body {
        font-family: Arial, Helvetica, sans-serif;
        background-color: #FFCF;
    }

The img selector targets all image elements.
It sets a green border around images.

    img {
        border: 10px solid green;
    }

The blockquote selector targets all blockquote elements.
It sets the font family, font size, font style, and text alignment.

    blockquote {
        font-family: Georgia, 'Times New Roman', Times, serif;
        font-size: 3rem; 
        font-style: italic;
        text-align: center;
    }

The cite selector targets all cite elements.
It sets the font size and font weight.

    cite {
        font-size: 1.5rem;
        font-weight: bold;
    }

The .bigbold class can be applied to any element to make the text bold and slightly larger.

    .bigbold {
        font-weight: bold;
        font-size: 1.3rem;
    }

The h1 selector targets all h1 elements.
It sets the border, text color, background color, and text alignment.

    h1 {
        border: 5px dotted red;
        color: white;
        background-color: black;
        text-align: center;
    }

The h2 and h3 selectors target all h2 and h3 elements respectively.
They set the text color to orange.

    h2 {
        color: orange;
    }
    h3 {
        color: orange;
    }

The ol selector targets all ordered list elements.
It sets the text color to green.

    ol {
        color: green;
    }

The a:link selector targets all unvisited link elements.
It sets the font weight, removes the text decoration, and sets the text color.

    a:link {
        font-weight: bold;
        text-decoration: none;
        color: brown;
    }

The a:visited selector targets all visited link elements.
It sets the font weight, removes the text decoration, and sets the text color.

    a:visited {
        font-weight: bold;
        text-decoration: none;
        color: green;
    }

The a:hover selector targets all link elements when they are being hovered over.
It sets the font weight, adds an underline decoration, and sets the text color.

    a:hover {
        font-weight: bold;
        text-decoration: underline;
        color: orange;
    }