# EpiCauses – a cancer surveillance web API to track the causes of cancer in humans.

## Rationale
The EpiCauses Tracker aims to create a cancer surveillance ecosystem for knowledge generation on the causes of cancer using text mining of open web content. The platform’s ability to generate custom reports and visualizations makes it easier for scientists and the population to identify what is known about the causes of cancer in humans. Our goal was to create an integrative web API that could visualize and navigate the content of the text and create common answers on the causes of cancer using machine learning techniques.

## Materials and methods
Data source
EpiCauses tracker is a collaborative open-source web API built in Phyton and JavaScript to offer solutions for text mining information on human cancer causes. The dataset was created using open and free information from the World Health Organization, which includes tables, scientific articles,  and 136 books published by the program and available elsewhere as pdfs (https://publications.iarc.fr/Book-And-Report-Series/Iarc-Monographs-On-The-Identification-Of-Carcinogenic-Hazards-To-Humans). 
Details on the open notebook are available here: (https://observablehq.com/d/774190043eb69c6a).
### Natural Language Processing models
To optimize frequent answers about cancer causes, we used scraping text from tables, text mining, and a natural language processing engine. Data gathering can be visualized in details here:  (scrap_iarc.py).

