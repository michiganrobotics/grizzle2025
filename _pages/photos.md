---
title: "Photos"
permalink: /photos/
author_profile: true
---


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery</title>
    <style>
        .gallery {
            display: grid;
            grid-template-columns: repeat(3, 1fr); /* Creates three columns */
            gap: 10px; /* Space between the grid items */
            max-width: 360px; /* Adjust the maximum width as needed */
            margin: auto; /* Center align the gallery */
        }

        .gallery div {
            text-align: center; /* Center-align text and images within each div */
        }

        .gallery img {
            width: auto; /* Set the width of images */
            height: 150px; /* Maintain aspect ratio */
        }
    </style>
</head>
<body>
    <div class="gallery">
        <div>
            <a href="/images/1998.jpg" target="_blank">
                <img src="/images/1998.jpg" alt="Jessy Grizzle profile 1998">
            </a>
            <p>Circa 1998</p>
        </div>
        <div>
            <a href="/images/1999.jpg" target="_blank">
                <img src="/images/1999.jpg" alt="Jessy Grizzle profile 1999">
            </a>
            <p>Circa 1999</p>
        </div>
        <div>
            <a href="/images/2004.jpg" target="_blank">
                <img src="/images/2004.jpg" alt="Jessy Grizzle profile 2004">
            </a>
            <p>Circa 2004</p>
        </div>
        <div>
            <a href="/images/2008.jpg" target="_blank">
                <img src="/images/2008.jpg" alt="Jessy Grizzle profile 2008">
            </a>
            <p>Circa 2008</p>
        </div>
        <div>
            <a href="/images/2013.png" target="_blank">
                <img src="/images/2013.png" alt="Jessy Grizzle profile 2013">
            </a>
            <p>Circa 2013</p>
        </div>
        <div>
            <a href="/images/2020.jpg" target="_blank">
                <img src="/images/2020.jpg" alt="Jessy Grizzle profile 2020">
            </a>
            <p>Circa 2020</p> <!-- Corrected the caption year -->
        </div>
    </div>
</body>
</html>




<!-- ![Jessy Grizzle profile 1998](/images/1998.jpg)  
Circa 1998

![Jessy Grizzle profile 1999](/images/1999.jpg)  
Circa 1999

![Jessy Grizzle profile 2004](/images/2004.jpg)  
Circa 2004

![Jessy Grizzle profile 2008](/images/2008.jpg)  
Circa 2008

![Jessy Grizzle profile 2013](/images/2013.png)  
Circa 2013 -->