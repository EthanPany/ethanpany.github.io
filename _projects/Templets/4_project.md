---
layout: page
title: project 4
description: another without an image
img:
importance: 3
category: fun
---

Change something to see

**Calglass** is a groundbreaking wearable device designed to help users achieve **better health through smart dietary management**. It was developed as a response to the growing number of people struggling to maintain healthy eating habits, with many mistakenly believing that **exercise alone** is the most effective way to stay fit. Calglass combines **computer vision** and **AI algorithms** to recognize foods and calculate **caloric content**, providing users with **actionable insights** to improve their diets.

### Inspiration
The idea for Calglass originated from the observation that **unhealthy eating habits** contribute significantly to conditions like **obesity** and **heart disease**. The team noticed that existing dietary management solutions, such as **mobile apps**, often require extensive manual input and can be inaccurate. Inspired by this gap, Calglass aims to offer a **more efficient, real-time solution** by automatically analyzing food intake through wearable glasses.

### Development Journey
#### Early Stages
The project began with extensive **research and brainstorming**, aiming to find a practical way to integrate **AI** into dietary management. The team recognized that using a **wearable device** could provide the **convenience and real-time analysis** needed to help people make healthier choices effortlessly.

### Hardware
Calglass was built using a combination of hardware components:
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_calGlass/IMG3493.jpg" title="3D Model of Calglass" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_calGlass/IMG3482.jpg" title="Calglass Prototype" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_calGlass/IMG3483.jpg" title="Calglass Prototype in Use" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **Camera and Gyroscope**: These allow for **real-time image capture and stabilization** during food recognition.
- **Raspberry Pi**: The main computing unit, which runs the **food recognition algorithms**.
- **3D Modeling and Printing**: The frame of the glasses was custom-designed, **3D-printed**, and **assembled** by the team.




Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
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
