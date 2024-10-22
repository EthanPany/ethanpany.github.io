---
layout: page
title: project 4
description: another without an image
img:
importance: 3
category: fun
---

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


- **Camera and Gyroscope**: These allow for **real-time image capture and stabilization** during food recognition.
- **Raspberry Pi**: The main computing unit, which runs the **food recognition algorithms**.
- **3D Modeling and Printing**: The frame of the glasses was custom-designed, **3D-printed**, and **assembled** by the team.

### Software
The software development involved:
- **YOLO (You Only Look Once) Algorithm**: Used for **object detection** to recognize different types of food in real time.
- **Data Processing**: After detection, the system estimates the **caloric content** and **nutritional information** of the identified food.
- **Web Interface**: A companion website displays the data, allowing users to **track their dietary habits**, **view historical data**, and receive **meal suggestions**.

### Achievements and Testing
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_calGlass/IMG3484.jpg" title="Testing the Prototype" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_calGlass/IMG3485.jpg" title="Captured Image Analysis" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_calGlass/IMG3427.jpg" title="Calglass Team Members" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Through rigorous testing, the team achieved:
- **Over 70% accuracy** in identifying various types of fruits, with plans to increase this rate through further software optimization.
- Integration with the web platform, enabling users to **receive meal recommendations** based on their dietary history.

### Teamwork and Contributions
The Calglass project was a collaborative effort, with team members specializing in different aspects of the development:
- **Ethan**: Handled the **hardware assembly**, including **3D modeling**, **Raspberry Pi setup**, and **software configuration**.
- **Scott**: Developed the code for the **camera's image capture** and implemented **color-based filtering** techniques to improve food recognition.
- **Paul**: Focused on the **algorithm development**, processing the filtered images to determine **caloric values** based on **color ratios**.
- **Melody**: Conduct related research, write survey questions, and analyze the data.
- **Betty**: Write posts and **documentation**, conduct related research and presentation preparation.
- **Feil**: Conduct related research and social media promotion.
- **Lorenzo**: Peer-tutoring, providing guidance and support to team members.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_calGlass/IMG3428.jpg" title="The Development Team" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image of the Development Team
</div>

### Future Vision
The team aims to enhance Calglass by incorporating:
- **Real-time body condition monitoring**, such as **heart rate** and **blood pressure**.
- **Smart dietary recommendations** that consider factors like **weather**, **user activity**, and **location**.
- **Exercise tracking** to offer a comprehensive health management experience.

### Project Files and Media
You can find the **detailed report** and **presentation slides** below:
<a href="assets/pdf/proj_calGlass/CTB_CalGlass_Group_Final_Report.pdf">Final Report (PDF)</a>
<a href="assets/pdf/proj_calGlass/Calglass_Presentation.pdf">Presentation Slides (PDF)</a>
<a href="assets/pdf/proj_calGlass/Calglass_Presentation2.pdf">Presentation Slides2 (PDF)</a>

#### Watch the Demonstration Video
<iframe src="//player.bilibili.com/player.html?bvid=BV1dT4y1D7vb&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

Calglass represents a **revolutionary step** towards making dietary management **more accessible and effective**. By merging **wearable technology** with **artificial intelligence**, the project aims to help users make **better lifestyle choices** effortlessly. Stay tuned as we continue to **refine and expand** this innovative solution!