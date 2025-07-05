---
layout: page
title: Power Writer
description: An AI-powered slide generator that turns tedious work into a five-minute task.
img: assets/img/proj_sliGen/11-31-38-0002.png
importance: 3
category: work
---

Imagine being a smart building designer, tasked with creating a compelling, hundred-page presentation to win a new project. Now imagine doing that over and over again, with much of the content being repetitive. This was the problem I was tasked with solving during my internship at **Coco Tech Co.**, and the solution was **Power Writer**.

### Demo Video

<iframe id="kaltura_player" src='https://cdnapisec.kaltura.com/p/1660902/embedPlaykitJs/uiconf_id/55063182?iframeembed=true&amp;entry_id=1_w4snuodx&amp;config%5Bprovider%5D=%7B%22widgetId%22%3A%221_p69nor2g%22%7D&amp;config%5Bplayback%5D=%7B%22startTime%22%3A0%7D'  style="width: 1024px;height: 576px;border: 0;" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *"  title="24Summer Interen Demo-Up to 4K"></iframe>

### From Tedium to Automation

My role was to develop an automatic slide generator agent that could take a database of previous design plans and, combined with the requirements of a new project, generate a complete presentation. I built both the backend and frontend of this tool, creating a full-stack solution that would dramatically reduce the workload for the design team.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_sliGen/11-31-38-0001.png" title="Power Writer Interface 1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_sliGen/11-31-38-0002.png" title="Power Writer Interface 2" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_sliGen/11-31-38-0003.png" title="Power Writer Interface 3" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### The Technology Behind the Transformation

I used a combination of **RAG (Retrieval-Augmented Generation)**, **LangChain**, and the **OpenAI API** to build the core of the slide generator. The system preprocesses source documents, embeds the text for fast retrieval, and then uses a series of chains to generate an outline, create titles, format content, and even integrate images. The result is a professional-looking presentation, generated in minutes.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_sliGen/11-31-38-0004.png" title="Generated Slide Example 1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_sliGen/11-31-38-0005.png" title="Generated Slide Example 2" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_sliGen/11-31-38-0006.png" title="Generated Slide Example 3" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### A resounding success

The results were astounding. Power Writer can produce a complete design plan in **under five minutes** with local models, and in **under two minutes** with online models. This represents a **700% reduction** in the time spent creating slides, and the generated content is, on average, **80% as good as a human-generated version**. The project was a huge success, setting a new standard for efficiency and providing a powerful example for the company's future product development.

### Project Files

You can find the **detailed report** below:

<a href="../../assets/pdf/proj_sliGen/PowerWriter_Final_Report.pdf">Final Report (PDF)</a>

---

Power Writer is a story of how a focused application of AI can solve a real-world business problem, transforming a tedious, time-consuming task into a streamlined, automated process.
