---
title: Malaria Detection from Blood Smears using Deep Learning
summary: Worked on Malaria detection from blood cell images using Deep Learning. Used the NIH GOV's Official Malaria Cell Image Dataset. Created a model from scratch and trained it and got a 99.95% Training Accuracy and 99.61% Validation Accuracy.

tags:
- Medical Image Analysis
date: "2020-06-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
MedDES is a medical diagnostic system for medical diagnosis using deep learning which has 4 diagnostic tests for Malaria, COVID-19, Pneumonia and Brain Tumour. 
The system also generates a detailed patient report after testing and can be accessed here. 

Built 4 light weight CNN models using Keras and Tensorflow backend, one for each test and were trained on respective official datasets. The highly accurate models have an avg inference time of 84 msecs. 
For enabling easy access, system was built as a web application using Streamlit and deployed using herokuapp and can be accessed here.
