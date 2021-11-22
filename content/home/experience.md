---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Volunteer Intern
    company: Microsoft Research
    company_url: ''
    company_logo: Microsoft_logo
    location: California
    date_start: '2021-08-01'
    date_end: ''
    description: |2-
        Volunteering intern under Dr. Vibhav Vineet, MSR Redmond:
        * Working on a research project on understanding why DNNs fail to some adversarial perturbations like Gaussian Noise, Affine Transformations, Background change.
        * Project also deals with understanding whether GradCAMs offer sufficient insights about why the model predicts 
        the wrong class on such perturbations. 
    
        
  - title: Research Assistant
    company: Malaviya National Institute of Technology Jaipur
    company_url: ''
    company_logo: mnit
    location: Jaipur, India
    date_start: '2020-05-01'
    date_end: ''
    description: |2-
        Research assistant under Prof. Deepak Ranjan Nayak, Dept of Computer Science:
        * Worked on two projects on COVID-19 Detection from Chest CT scans using Deep Learning. Used the official COVID CT 
          dataset by UCSD Research Group.
        * Proposed LiMS-Net, a light weight CNN (2.53 M) with multi-scale feature learning capability which outperformed the
          heavy Imagenet models and existing published works on that dataset.
        * Proposed another model MFL-Net, an ultra-light weight network (0.78 M) consisting of 4 Multi-Scale Feature Learning 
          (MFL) Blocks which capture and preserve various receptive fields using residual skip connections.
        * Currently working on designing another CNN model for Glaucoma Detection from Fundus Images.  
  
  - title: Research Intern
    company: Indian Institute of Technology Ropar
    company_url: ''
    company_logo: ropar
    location: Punjab, India
    date_start: '2020-12-01'
    date_end: '2021-08-01'
    description: |2-
        Research intern under Prof. Puneet Goyal, Dept of Computer Science:
        * Worked on COVID-19 Lung Lesion Segmentation on the official NIH COVID-19 Grand Challenge Data.
        * Explored the efficacy of U-Net and its variants by modifying the networks by adding residual blocks and atrous convolution blocks.
        Also introduced attention mechanism coupled with Tversky Loss for enhancing feature learning capability
        * Among all its variants, R2-UNet gave the best dice score of 83.54%
    
  - title: Research Intern
    company: Indian Institute of Information Technology Guwahati
    company_url: ''
    company_logo: guwat
    location: Guwahati, India
    date_start: '2020-05-01'
    date_end: '2020-08-01'
    description: |2-
        Research intern under Prof. Subhasish Dhal, Dept of Computer Science:
        * Worked on a research project on optimising public Bike Sharing Systems. Developed a Machine Learning based bike recommendation system which recommends bikes to the users based on their travel demands.
        * Used the Official Divvy Bike System trip records from their data to analyze the bike trip patterns. Grouped bikes with similar trip patterns using K-means clustering.
        * Used a neural network to finally predict the best cluster of bike for the user's inputs which achieved 97% accuracy. The system recommends the bike belonging to the predicted cluster among the available bikes. 


  - title: Winter Research Intern
    company: Indian Institute of Information Technology Allahabad
    company_url: ''
    company_logo: alahab
    location: Prayagraj, India
    date_start: '2019-11-01'
    date_end: '2020-01-01'
    description: |2-
        Research intern under Prof. Ratan K Saha, Dept of Applied Sciences:
        * Studied various Biomedical Imaging Modalities. Work mainly focused on Photoacoustic Imaging techniques like PA Tomography, Microscopy.
        * Successfully simulated phantoms of various shapes using K-Wave toolbox in MATLAB. 
        * Implemented various Image Development Algorithms like UBP, TI and worked on different simulation techniques like Monte Carlo Simulation.
design:
  columns: '2'
---
