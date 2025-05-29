## Named Entity Recognition (NER) Visualization

This project demonstrates how Named Entity Recognition (NER) works using a simple example. It shows how text can be analyzed to highlight named entities like people, places, or organizations.

## 📄 Project Overview

We used Python and spaCy to extract named entities from a text, and then visualized the results using HTML. The file example.html contains the output showing entities directly in the browser.

## 🔍 What’s Inside

example.html: This file shows the final NER results with highlighted entities. For instance, the word "America" is detected as a geographical location (GPE - Geo-Political Entity).

The HTML was generated using a Python script with spaCy's built-in displacy visualizer.

## What is NER?

NER (Named Entity Recognition) is a part of NLP (Natural Language Processing) that identifies specific kinds of words in a sentence, such as:

🧝 Person names (e.g., Elon Musk)

🏢 Organizations (e.g., Google)

🌍 Locations (e.g., Asia)

📅 Dates and times (e.g., May 2025)

It’s commonly used in search engines, recommendation systems, and chatbots.

## ⚙️ How It Was Done

A Python script was used to process the text using spaCy.

The displacy.render() function was used to convert the results into a visual format.

This HTML output was saved as example.html.

You can open the HTML file in any browser to view the result.

No external servers or frameworks were required — it's all local and lightweight.

## 🧰 Tools Used

Python 3

spaCy (for named entity detection)

HTML/CSS (for visualization)

![image](https://github.com/user-attachments/assets/b449d660-c96a-4ca7-b3b4-817f09f07b3f)

Author : NUKALA RISHITA NAGA SAI
