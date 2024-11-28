---
layout: page
title: Open Clusters
description: The Milky Way structure using Open Clusters with Machine Learning
img: assets/img/OCs_image.jpg
importance: 1
category: astronomy
---


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image with Caption and Wrapped Text</title>
    <style>
        .wrapped-image {
            float: left; /* Positions the image and caption to the left */
            margin-right: 15px; /* Adds space between the image and text */
            margin-bottom: 10px; /* Adds space below the image and caption */
            width: 600px; /* Example width for the image */
            text-align: center; /* Centers the caption text */
        }
        .wrapped-image img {
            max-width: 100%; /* Ensures the image fits the container */
            height: auto; /* Maintains the aspect ratio */
        }
        .wrapped-image figcaption {
            font-size: 0.9em; /* Adjusts caption font size */
            color: #555; /* Sets a neutral color for the caption */
        }
    </style>
</head>
<body>
    <figure class="wrapped-image">
    <img src="/assets/img/OC_NGC_2164.jpg" alt="Description of the image">
    <figcaption>Open Cluster NGC 2164 observed by Hubble. Credit: ESA/Hubble & NASA, J. Kalirai, A. Milone  </figcaption>
    </figure>
    <p>
        Open clusters (OCs) are groups of stars that share age, chemical composition, and dynamics, having formed together and
        being bound by gravity (De Silva et al., 2006). As natural examples of simple stellar populations, their age, metallicity,
        and distance can be more accurately determined with photometry (through their colour-magnitude diagrams) compared
        to individual stars. You might ask... what is a color-magnitude diagram? 
    </p>
    <p>
        Fusce ut placerat orci nulla pellentesque. Faucibus ornare suspendisse sed nisi lacus sed viverra tellus. Commodo elit at imperdiet dui accumsan sit amet. Vitae sapien pellentesque habitant morbi tristique senectus et netus et. Tellus integer feugiat scelerisque varius morbi enim nunc faucibus a.
        <br><br>
        <br><br>
        <br><br>
        <br><br>
        <br><br>
        <br><br>
    </p>
</body>






<!-- OCs serve as valuable laboratories for studying key questions such as the formation and structure
of the Galactic disk, stellar migration, stellar associations formation mechanisms, and the origin of close binary systems
and their connections with black holes. Additionally, OCs are used to validate large astronomical datasets, such as Gaia
(Gaia Collaboration et al., 2023), tune stellar evolution models, and even test gravity theories (Kroupa et al., 2022). -->

    ---
    sss
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
