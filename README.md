# cmm536_advanced_data_science

### Task 1
***Files:***
  * CMM536_coursework__1608118.ipynb
  * data

#### Obejctive:
The objective of this work is to solve a set of medical imaging problems using the ultrasound images

#### Description:
The dataset contains 218 four-chamber heart ultrasound images. 80 images with the Mitral valve open and 138 images with the Mitral valve closed. Furthermore, the dataset also contains 925 images of abdominal ultrasounds. All the images are stored in a resolution of 128 x 128 pixels.

**The Jupyter notebook is structured based on the following tasks:**
  1. Define two separate classifiers (non-neural network classifier & neural network classifier) to distinguish between an abdominal ultrasound and a heart ultrasound.
     - Load ultrasound images; extract HOG features; stratified train/test split; classifiers; performance metrics
    
  2. Using only the heart images, re-train one of the classifiers to distinguish between 'open' and 'closed' images.
     - N-fold cross validation; performance metrics

  3. Improve the results from task 2, by means of image/data augmentation and the use of more advanced classifiers (e.g.: transfer learning)
     - Transfer Learning

### Task 2
***Files:***
  * Water_Quality_Assessment.ipynb
  * water_quality_data.xlsx

### Objective:
Water quality assessment and prediction for Lake Cajititlan (Mexico) - a shallow subtropical lake impaced by fertilizer runoff and wastewater.

### Description:
The water quality data (2009 - 2024), including information on the lake such as: date & time measurements were taken, the location as well as the values for water quality indicators (e.g.: pH) can be found in the excel document.
The goal is to **train and deploy an ML algorithm designed for temporal data forecasting to predict at least one of the pollutants**
  - Train the model using the 2009 - 2023 data to predict 2024
  - Use all the data to predict for 2025
