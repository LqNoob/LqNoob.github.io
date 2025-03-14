---
layout: page
title: Automated Audiobook
description: Dubbing for various types of text data, including books, screenplays, and more.
img: assets/img/3.jpg
importance: 2
category: work
giscus_comments: false
---

Transform text stories into immersive audio experiences with AI-powered multiple characters and variety of emotions in voice generation.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/tellstories.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    The Excalidraw-formatted diagrams were created from the GitHub repository "tell-stories-webui".
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
Given the topic to be discussed, PodAgent will simulate human behavior to create podcast-like audio presented as a talk show, featuring one host and several guests. The show will include diverse and insightful viewpoints, delivered in appropriate voices, along with structured sound effects and background music to enrich the listening experience.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/podAgent.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    The Excalidraw-formatted diagrams were created from the GitHub repository "PodAgent".
</div>

To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
