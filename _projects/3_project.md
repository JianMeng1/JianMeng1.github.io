---
layout: page
title: Bilinbgual Lexical Entrainment
description:
img: assets/img/entrainment.jpg
redirect: https://unsplash.com
importance: 3
category: Past
---

<strong>What is lexical entrainment?</strong>
Lexical entrainment is a dialogue phenomenon that speakers adopt their interlocutors’ word choice [1]. As we see from the picture below, one speaker says “computer” and the other speaker says “laptop” while they both refer to the same object. They start with different terms, but the second speaker ends up using “laptop” as well. In this process, the second speaker is entrained to the first speaker.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/entrainment.jpg" title="lexical entrainment" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<strong>Two types of entrainment</strong>
There are two mainstream explanations for the mechanism of entrainment, that lexical entrainment is an automatic or a meidated process.

<div class="highlighted-content">
    <ul>
        <li><strong>Automatic entrainment:</strong> Higher activation level1 leads to higher probability of adopting the word [2].</li>
        <li><strong>Mediated entrainment:</strong> Features of the linguistic and social context affects speakers’ entrainment [4][5][6].</li>
    </ul>
</div>

<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
