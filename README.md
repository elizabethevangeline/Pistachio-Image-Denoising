# 🥜 Pistachio Image Denoising & Preprocessing  

## 📌 Project Overview  
This project focuses on **image preprocessing and denoising** for a **Pistachio dataset**.  
The aim is to clean and prepare the images so they can be used effectively in **deep learning models (CNN)** for classification or analysis.  

---

## 🔎 Workflow  

### 1. Dataset Loading  
- Extracted and loaded Pistachio dataset.  
- Inspected image samples for quality and consistency.  

### 2. Exploratory Data Analysis (EDA)  
- Checked image dimensions (width & height distributions).  
- Analyzed aspect ratios to see if resizing is needed.  
- Identified corrupted or unusual images.  
- Visualized random samples from the dataset.  

### 3. Image Preprocessing & Denoising  
- Normalized image pixel values.  
- Applied **denoising techniques** (e.g., Gaussian filter / Non-local Means Denoising).  
- Ensured consistent size and format across all images.  

### 4. Visualization  
- Compared original vs. denoised images.  
- Plotted histograms of pixel intensity distribution before and after cleaning.  

---

## 📊 Key Insights  
- Pistachio images vary in dimension and aspect ratio → resizing required.  
- Some noise present in the dataset → denoising step improves quality.  
- Clean, standardized images make the dataset ready for **deep learning training (CNN)**.  
