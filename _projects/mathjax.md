---
layout: page
title: MathJax Clipboard Formula Replacer 
description: (UserScript with JS) A browser extension that automatically converts complex MathJax formulas to clean TeX format when copying from web pages.
img: assets/img/proj_mathjax/MathJax Clipboard Formula Replacer.jpeg
importance: 3
category: fun
---

Replace complex MathJax HTML with its underlying TeX formula in your clipboard, making it easy to paste into LLM tools like ChatGPT, Markdown editors, and other TeX-aware applications. If no MathJax is detected, the original selection is copied unchanged.


### The Problem

My intro to AI class uses webpages as slides, and so do the homework questions for my ECE class on Canvas. One problem with this setup is that whenever I copy something containing a formula and paste it into tools like ChatGPT, the formula disappears. 

I used to convert content into Markdown using Typora before pasting it into ChatGPT, while some of my classmates just take tons of screenshots. Neither approach is elegant—both waste either time or storage space. So I learned scripting from scratch and implemented this solution with help from ChatGPT.

### Key Features

**Automatic MathJax Detection** - Identifies MathJax content within your copied selection and works with both MathJax v2 and v3.

**TeX Extraction** - Accurately extracts TeX formulas from complex HTML structures.

**HTML Cleaning** - Removes unnecessary style, class, and id attributes from copied HTML for cleaner pasting.

**Graceful Fallback** - If no MathJax is found or an error occurs, the script copies the original content without modification.

**Universal Compatibility** - Works on all websites with no special browser permissions required.

### How It Works

This UserScript runs automatically in your browser using extensions like Tampermonkey or Greasemonkey:

1. **Event Listener** - Listens for copy events on any webpage
2. **Selection Analysis** - Captures both plain text and HTML content when you copy
3. **MathJax Detection** - Uses regex to identify MathJax elements in the selection
4. **Smart Processing** - Extracts TeX formulas from `mjx-container` (v3) or `MathJax` span elements (v2)
5. **Clean Output** - Removes styling attributes and replaces complex HTML with clean TeX formulas

### Technical Implementation

The script uses JavaScript to:
- Parse HTML fragments into DOM documents
- Identify MathJax elements by their container classes
- Extract TeX formulas from `alttext` or `aria-label` attributes  
- Replace complex HTML structures with simple TeX text nodes
- Handle errors gracefully with fallback to original content

### Installation & Usage

1. Install a UserScript manager (Tampermonkey for most browsers, or Greasemonkey for Firefox)
2. Install the script from the repository or copy the code into your UserScript manager
3. The script runs automatically on all webpages
4. Simply copy text as normal - MathJax formulas will be automatically converted to TeX format
5. Paste into LaTeX editors, Markdown files, or any TeX-aware application

### Open Source & Contributing

This project is licensed under GNU GPL v3. As my first UserScript project, I welcome all feedback, suggestions, and contributions! 

The project is available on GitHub with plans to publish on GreasyFork once stable. If you find it useful, please consider starring the repository.

**Repository:** [GitHub - MathJax Clipboard Formula Replacer](https://github.com/yourusername/mathjax-clipboard-replacer)