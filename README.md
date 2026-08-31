# Potato Leaf Classification

**Developing a Convolutional Neural Network for Potato Disease Detection in Indonesia**  
*Ziwen Qian¹ & Karthik Chawla²*  
¹ White Oaks Secondary School, Oakville, Canada  
² Iroquois Ridge High School, Oakville, Canada

---

## Overview
This project aims to develop a **Convolutional Neural Network (CNN)** to detect potato leaf diseases, with a focus on **underrepresented countries like Indonesia**. Early and accurate detection of potato diseases can significantly improve crop yields, reduce losses, and support smallholder farmers’ livelihoods.

---

## Motivation
Potatoes are one of the **most consumed food crops worldwide**, feeding over a billion people with global yields exceeding 300 million metric tons annually. They are grown in over 125 countries, from high-altitude plateaus to tropical regions.  

Potato production in developing countries has grown rapidly in recent decades, surpassing that of many developed nations. The global potato-processing industry is also expanding, projected to reach USD 60 billion by 2031, making potatoes a key staple and industrial commodity.  

---

## Problem
The potato is one of the **most disease-prone crops**, losing an estimated 4 million tons annually due to disease. Late Blight Disease (*Phytophthora infestans*) is especially devastating, causing 15–30% crop loss each year. Traditional monitoring methods like PCR, ELISA, and soil DNA testing are **expensive, slow, and require laboratory infrastructure**, making them impractical for farmers in developing regions.  

Historical events like the **Irish Potato Famine** highlight the catastrophic consequences of potato disease outbreaks.  

---

## Solution: Machine Learning
CNNs and other machine learning techniques provide a **fast and scalable alternative** for potato disease detection. However, most existing models are trained on data from major producers like China, Europe, and North America, making them **less effective in underrepresented countries** with limited technological resources.  


- Shabrina et al. developed a dataset from uncontrolled environments in Indonesia, achieving 73.63% accuracy with EfficientNetV2B3. The proposed model, which we have developed, beats this by almost 15% percentage points with an accuracy of 87%

Our approach focuses on **lightweight CNN models like MobileNet**, which are more practical for **real-world deployment** in smallholder farms.

---

## Features
- Detection of major potato leaf diseases
- Lightweight CNN models suitable for mobile and low-resource environments
- Supports deployment in underrepresented regions like Indonesia
- Python and Jupyter Notebook-based implementation

---

## Dataset
- Images from **controlled and uncontrolled environments**
- Focus on **underrepresented regions** with limited existing datasets
- Preprocessing pipelines for CNN input
