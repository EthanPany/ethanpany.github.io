---
layout: page
title: Power Writer
description: An Smart Building Design Slide Generator Based on RAG
img: assets/img/proj_sliGen/11-31-38-0002.png
importance: 3
category: work
---

**Power Writer** is a smart tool developed to automate the creation of slide decks for design projects. The tool helps streamline the process of generating presentations by using AI to create structured content based on user inputs, thus saving time and ensuring a professional layout.

### Demo Video

<iframe id="kaltura_player" src='https://cdnapisec.kaltura.com/p/1660902/embedPlaykitJs/uiconf_id/55063182?iframeembed=true&amp;entry_id=1_w4snuodx&amp;config%5Bprovider%5D=%7B%22widgetId%22%3A%221_p69nor2g%22%7D&amp;config%5Bplayback%5D=%7B%22startTime%22%3A0%7D'  style="width: 1024px;height: 576px;border: 0;" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *"  title="24Summer Interen Demo-Up to 4K"></iframe>

### Inspiration

The idea for Power Writer came from the observation that preparing slide decks for projects can be time-consuming, especially in industries like smart building design where slide decks often span hundreds of pages. The goal was to create a tool that could significantly reduce the workload by automating the initial draft creation, allowing designers to focus on refining the content.

### Development Journey

#### Early Stages

The project began with the need to automate slide generation for design projects. The team experimented with different approaches for **text segmentation, embedding**, and **content generation**. After various trials, a solution was developed that uses smaller language models for efficient processing while maintaining content relevance.

### Solution Approach

The system's core consists of several steps:

- **Document Preprocessing**: Source documents are converted to markdown format for structured segmentation. This allows for easier management of slide content and ensures that slide boundaries are preserved.
- **Embedding and Storage**: The text is embedded using the **all-MiniLM-L6-v2 model** for vector representation and stored in a local database for fast retrieval.
- **Chain Design**: A sequence of six chains was created to manage tasks such as **outline generation, title creation, content formatting,** and **image integration** using APIs like Unsplash.
- **Frontend and API Integration**: A simple web interface was built using **Slidev**, which supports markdown grammar and dynamic slide formatting.

### Hardware and Software

The software architecture was optimized for local processing, ensuring that content can be generated quickly, even on devices with limited hardware resources, such as an **Apple M1 chip**. The tool achieves results in under a minute, providing a fast and practical solution for designers.

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

### Achievements

Power Writer has shown significant potential in streamlining slide creation. During testing, it demonstrated the ability to:

- Generate slide content relevant to the specified topics, including **background information, project plans,** and **summaries**.
- Maintain a logical flow within the slide deck, with each slide focusing on a **central topic**.
- Produce an outline in **less than a minute**, making it suitable for time-sensitive tasks.

### Challenges and Limitations

- **Smaller Language Model Limitations**: Generating slide content from smaller language models sometimes resulted in long paragraphs, which required additional formatting.
- **Text Segmentation Issues**: The original format of slides was sometimes hard to maintain, which was addressed by using attributes such as **text size** to identify titles and key sections.
- **Prompt Engineering Difficulties**: Ensuring consistent output required fine-tuning the prompts and using **template-based formatting** to handle content presentation.

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

### Future Vision

Future plans for Power Writer include:

- **Adding memory capabilities** to improve content consistency across slides.
- **Integrating more advanced language models** for better semantic understanding.
- **Expanding the use case beyond slide decks** to support other types of documents.

### Project Files and Media

You can find the **detailed report** below:

<a href="../../assets/pdf/proj_sliGen/PowerWriter_Final_Report.pdf">Final Report (PDF)``</a>

---

Power Writer aims to simplify the process of creating professional slide decks by combining the power of AI and intuitive design. As the project evolves, it will continue to push the boundaries of what is possible in automated content generation.
