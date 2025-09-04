---
layout: page
title: AI File Organizer
description: (macOS App) An intelligent file management system that understands your content and organizes files the way you would.
img: assets/img/proj_solarflow/solarflow.png
importance: 5
category: work
---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/proj_solarflow/solarflow.png" title="Frontpage" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


How does your downloads folder look? If it's a chaotic mix of documents, images, and random files, SolarFlow is here to solve that problem. We're building an AI-powered file organizer that doesn't just sort by file type—it understands content and context to create a personalized, intuitive file system.

### The Problem We're Solving

File management is tedious and time-consuming. Traditional systems rely on arbitrary rules that don't match how we actually think about our files. File search capabilities fall short of expectations, and maintaining organization requires constant manual effort.

### Our Solution: SolarFlow

SolarFlow uses OpenAI's tools to automate file management by creating a human-readable file system tailored to each user. We provide robust search functionality using file metadata and AI-generated summaries, making it easy to find any file—even when you can't remember its name.

### Core Features

**Moonsword** - Our sorting agent that dives deep into every file, regardless of format, understanding content and generating intelligent summaries.

**Neutron Store** - A specialized database that stores all file information, including text embeddings and metadata for lightning-fast retrieval.

**Supernova** - The file organizing agent that uses database information to understand user preferences and sort files the way you would.

**Lightspeed Search** - Super-fast vector search that lets you find files based on content, not just filenames.

### Technology Stack

**Backend (Python)**
- FastAPI for core web framework
- Processing, database integration, and vectorization
- ChatGPT-4o Nano for text and image processing
- Whisper for audio/video transcription
- Text Embedding 3 for generating embeddings

**Frontend (Swift/SwiftUI)**
- Native macOS interface with responsive design
- Direct Finder integration
- Real-time notifications for processing status

### Privacy & Security First

We prioritize user control and privacy:
- Only scan files from directories you choose
- Option to run models locally for privacy-conscious users
- System and hidden files are automatically ignored
- Full transparency in what files are processed

### OpenAI Collaboration

This project is part of a special program at the University of Wisconsin-Madison in collaboration with OpenAI. As team leader, I'm driving the vision while conducting research on benchmarking LLM file organization capabilities—work we plan to publish as an academic paper.

**Interested in being an early user?** We're currently recruiting participants for our user study to help improve SolarFlow's organization algorithms.

### Project Videos

**Team Presentation**
<iframe id="kaltura_player_1" src='https://cdnapisec.kaltura.com/p/1660902/embedPlaykitJs/uiconf_id/55063182?iframeembed=true&amp;entry_id=1_cdv8t09g&amp;config%5Bprovider%5D=%7B%22widgetId%22%3A%221_p69nor2g%22%7D&amp;config%5Bplayback%5D=%7B%22startTime%22%3A0%7D' style="width: 640px;height: 360px;border: 0;" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" title="Team Presentation"></iframe>

**Live Demo**
<iframe id="kaltura_player_2" src='https://cdnapisec.kaltura.com/p/1660902/embedPlaykitJs/uiconf_id/55063182?iframeembed=true&amp;entry_id=1_pbky05lw&amp;config%5Bprovider%5D=%7B%22widgetId%22%3A%221_p69nor2g%22%7D&amp;config%5Bplayback%5D=%7B%22startTime%22%3A0%7D' style="width: 640px;height: 360px;border: 0;" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" title="Live Demo"></iframe>

**Folder Icon Demo**
<iframe id="kaltura_player_3" src='https://cdnapisec.kaltura.com/p/1660902/embedPlaykitJs/uiconf_id/55063182?iframeembed=true&amp;entry_id=1_cy7zim4n&amp;config%5Bprovider%5D=%7B%22widgetId%22%3A%221_p69nor2g%22%7D&amp;config%5Bplayback%5D=%7B%22startTime%22%3A0%7D' style="width: 640px;height: 360px;border: 0;" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" title="Folder Icon Demo"></iframe>


**Presentation Slides**

[Figma](https://www.figma.com/deck/KZYKkW5xMjZWoIGDWnQZ8N/Group-meeting-2?node-id=1-55&t=yYEIHB1DY9E0AO0R-1)