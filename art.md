---
title: Art
layout: page
icon: fa-palette
order: 4
published: true
---
Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@ami-az 
Learn Git and GitHub without any code!
Using the Hello World guide, you’ll start a branch, write comments, and open a pull request.


taras-d
/
images-grid
5
5218
 Code Issues 0 Pull requests 0 Actions Projects 0 Wiki Security Insights
images-grid/test.html
@taras-d taras-d Remove tabs
c4e8746 on Feb 2, 2017
81 lines (62 sloc)  2.04 KB
  
<!DOCTYPE html>
<html>
    <head>

        <title>Images grid test</title>

        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">

        <!-- jQuery -->
        <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/1.12.3/jquery.min.js"></script>
        <!--<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.0/jquery.min.js"></script>-->
        <!--<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>-->
        <script>console.log('jQuery: ' + $.fn.jquery);</script>

        <!-- Imageg grid -->
        <script src="src/images-grid.js"></script>
        <link rel="stylesheet" href="src/images-grid.css">

        <style>
            body {
                font-family: sans-serif;
            }
            p {
                text-align: center;
                margin: 10px;
                font-weight: bold;
                font-size: 12px;
            }
        </style>

    </head>
    <body>

        <p>1 image</p>
        <div id="gallery-1"></div>

        <p>2 images</p>
        <div id="gallery-2"></div>

        <p>3 images</p>
        <div id="gallery-3"></div>

        <p>4 images</p>
        <div id="gallery-4"></div>

        <p>5 images</p>
        <div id="gallery-5"></div>

        <p>6 images</p>
        <div id="gallery-6"></div>

        <p>More than 6 images</p>
        <div id="gallery-7"></div>

        <script>
            // Change default cells count from 5 to 6
            $.fn.imagesGrid.defaults.cells = 6;
            var images = [
                'https://ami-az.github.io/assets/images/pricetable.PNG',
                'https://ami-az.github.io/assets/images/pricetable.PNG',
                'https://ami-az.github.io/assets/images/pricetable.PNG',
                'https://ami-az.github.io/assets/images/pricetable.PNG',
                'https://ami-az.github.io/assets/images/pricetable.PNG',
                'https://ami-az.github.io/assets/images/pricetable.PNG',
                'https://ami-az.github.io/assets/images/pricetable.PNG',
            ];
            for (var i = 0; i < images.length; ++i) {
                $('#gallery-' + (i + 1)).imagesGrid({
                    images: images.slice(0, (i + 1)),
                    align: true
                });
            }
        </script>

    </body>
</html>
© 2020 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
