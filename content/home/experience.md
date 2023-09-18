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

 - title: Machine Learning Intern
    company: Latent AI Inc.
    company_url: 'https://latentai.com/'
    company_logo: Lai
    location: Skillman, NJ
    date_start: '2023-05-22'
    date_end: '2023-08-15'
    description: |2-
        Joined as a Machine Learning Intern under the ML Team:
        * Worked on enabling Intellectual Property Ownership verification using Black-Box Watermarking of DNNs.
        * Implemented a fully Black-Box DNN watermarking technique which gives 100% success rate with just 10-30% of the training compute cost (takes less than 10 minutes on a single 12 GB GPU of NVIDIA RTX 3070).
        * Developed and integrated the same technique as an end-to-end Black-Box watermarking module with Latent AI's flagship LEIP SDK toolkit as an add-on feature.
        * Conducted empirical experiments across different benchmark datasets and model architectures to prove the robustness of the watermarking method against variety of attacks like FTAL, FTLL, Pruning etc.

 - title: Graduate Research Assistant, 
    company: Prof. Teresa Wu's Lab, SCAI, ASU
    company_url: 'https://labs.engineering.asu.edu/wulab/'
    company_logo: scai
    location: Tempe, AZ
    date_start: '2022-08-18'
    date_end: '2023-05-01'
    description: |2-
        * Worked on predicting the improvement in aPTH (migraine) patients using a multi-modal approach combining functional MRI data and brain T2* imaging data using Graph Neural Networks (GNNs).
        * Improved the aPTH severity prediction accuracy by a stellar 11.5% by performing feature selection using Boruta ranking algorithm and SHAPley feature importance scores.
        * Collaborated with medical experts of Mayo Clinic and visualized the classification performance of our method to them by generating 3D embeddings of the final classification layer using UMAP projection plots.
   
  - title: Research Assistant: Deep Learning, Computer Vision
    company: Malaviya National Institute of Technology Jaipur
    company_url: 'https://depakranjannayak.wixsite.com/drnayak/research-1'
    company_logo: Mnit
    location: Jaipur, India
    date_start: '2020-05-01'
    date_end: '2022-05-01'
    description: |2-
        Research Assistant at Vision Analytics and Pattern Recognition(VAPR) Lab:
        * Worked on developing lightweight Deep Neural Networks (DNNs) with a focus on Multi-scale feature learning for COVID-19 Detection from Chest CT Scans. Proposed and published three models at top conferences and journals.
        * Developed MFL-Net: an efficient lightweight DNN (0.78M Params) with Multiscale Feature Learning (MFL) modules capturing and preserving features at different depths with a blend of convolutions and residual skip connections.
        * MFL-Net (30x lighter than ResNet-50 and 9x lighter than DenseNet-121) achieved an accuracy of 98.79% and 93.59% on SARS-CoV-2 CT-Scan dataset and COVID-CT dataset respectively.
        
  - title: Intern at Interactive Media Group
    company: Microsoft Research(MSR) Redmond
    company_url: ''
    company_logo: Microsoft_logo
    location: Redmond, Washington
    date_start: '2021-09-01'
    date_end: '2022-01-01'
    description: |2-
        * Worked on understanding why Convolutional Neural Networks (CNNs) fail to generalize on images with varying intensities of adversarial perturbations like Gaussian Noise, Background Occlusion and Affine Transformations.
        * Performed experiments on the benchmark ILSVRC Dataset using pretrained Imagenet models like AlexNet, VGG-16, EfficientNet using Pytorch. Visualized saliency maps using GradCAMs to highlight the model’s attention region in the image, giving insights behind the wrong prediction.  
        * Analyzed the dip in classification performance with the increasing intensity of different perturbations for all the ImageNet models using Matplotlib and Python.
  
  - title: Deep Learning Research Intern
    company: Indian Institute of Technology Ropar
    company_url: ''
    company_logo: ropar
    location: Punjab, India
    date_start: '2020-11-01'
    date_end: '2021-06-01'
    description: |2-
        * Worked on COVID-19 Lung Lesion Segmentation on the official NIH COVID-19 Grand Challenge Data. Analyzed the segmentation performance of U-Net and its variants like R2UNet, Attention UNet etc.
        * Experimented modifying these networks by adding residual blocks and atrous convolution blocks in their architectures.
        * Added attention mechanism in UNet coupled with Tversky Loss function for enhancing feature learning capability which gave the best segmentation IoU of 93.47%.
    
  - title: Data Science Intern
    company: Indian Institute of Information Technology Guwahati
    company_url: ''
    company_logo: guwat
    location: Guwahati, India
    date_start: '2020-05-01'
    date_end: '2020-08-01'
    description: |2-
        * Worked on developing a bike recommendation system for public bike sharing systems around the globe. Analyzed millions of trip records from the official Divvy Bike trip data.
        * Grouped bikes with similar trip patterns like trip distance and trip duration using K-means clustering into three categories: highly used, moderately used and rarely used bikes.
        * Trained a Random Forest Classifier to predict the best cluster of bikes depending on the user’s desired trip duration and trip distance. The model achieved an accuracy of 97%.


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
