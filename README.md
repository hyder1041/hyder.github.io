# Data Analyst
Data analyst who transforms complex data into strategic business growth. I specialize in Python, SQL, and predictive analytics to solve real problems, from developing AI models for deepfake detection to implementing operational optimization and sustainability analytics projects. My approach combines technical expertise with business strategy, delivering actionable insights that drive measurable results. I'm seeking opportunities with forward-thinking organizations that want to leverage data for competitive advantage and digital transformation. Let's discuss how I can help turn your data challenges into growth opportunities.

### Technical Skills: Python, SQL, Excel, Tableau, C++

## Education
- Machine Learning Certification | DSI, University of Toronto (2025)
- Electrical Engineering, B.Tech |Indian Institute of Technology, Hyderabad (2017)

## Work Experience
Marketing Analyst Intern | Digital Receipt Activation Strategy |	April 2024 - July 2024 | AngleApp, AB
- Researched digital receipt adoption trends in Canada & California via SimplyAnalytics and consumer data analysis.
- Cleaned datasets in Excel; built pivot tables, KPIs, and charts for trend analysis.
- Designed interactive Tableau dashboards for market segmentation, ROI estimation, and environmental impact visualization.
- Recommended API integration strategies for POS systems with compliance to PIPEDA and CCPA.
- Developed A/B testing campaigns, customer journey maps, and targeted marketing strategies for SMBs.
- Tech Stack: Excel, Tableau, SimplyAnalytics, Google Analytics, Python.
- Key Achievement: Delivered a go-to-market plan backed by Excel-driven analysis and Tableau-powered storytelling.


## Projects
**Plaque detection from intravascular ultrasound (IVUS) images**
- Problem Context
- IVUS imaging provides detailed cross-sectional views of coronary arteries, but manual plaque detection is labor-intensive, prone to observer bias, and affected by noise/artifacts. To address these challenges, I developed an image-processing pipeline that reduces noise, extracts lumen/media boundaries, and detects plaque morphology with higher consistency.
- Methodology
Dataset: 50 IVUS images from human coronary artery pullbacks (Boston Scientific iLab IVUS system, 40 MHz Atlantis SR Pro catheter).

Preprocessing: Resized images (512×512 → 256×256), grayscale quantization (8-bit → 3-bit), and intensity inversion to highlight lumen regions.

Noise Reduction: Applied erosion and dilation filters to enhance lumen and adventitia boundaries.

ROI Extraction: Implemented adaptive border detection and convex hull fitting around lumen to minimize the search space for plaque detection.

Plaque Segmentation: Applied gradient thresholding and intensity-based contour analysis to distinguish concentric vs. eccentric plaque morphology.

Implementation: Entire pipeline built in C++ with optimized memory handling for medical image processing.

- Results & Contributions
Successfully segmented lumen, media, and plaque regions with improved consistency compared to manual segmentation.

Demonstrated detection of both concentric and eccentric plaque across diverse IVUS images. Reduced noise and artifacts while preserving diagnostic features of images.
- Tech Stack: C++ · Medical Imaging · Image Processing · Digital Image Processing · Data Structures · Convex hull analysis · Morphological Operations · Image Segmentation

**Fake Image Classifier Using CNN**
- Developed a CNN to classify facial images as real or fake to combat deepfake content.
- Preprocessed 64×64 RGB images with data augmentation (rotation, flipping, zoom, brightness adjustment) using TensorFlow’s ImageDataGenerator.
- Designed a three-layer CNN with ReLU, MaxPooling, Dropout, and dense layers.
- Trained with Adam optimizer, binary cross-entropy loss, and early stopping.
- Achieved more than 88% classification accuracy; evaluated via confusion matrix, precision, recall, F1-score, and ROC-AUC.
- Tech Stack: Python, Pytorch, NumPy, Pandas, Matplotlib, Scikit-learn.
- Key Achievement: Built a production-ready deep learning model for high-accuracy fake image detection

**Financial Performance & EBITDA Predictive Analysis**
- Analyzed 1,577 company financial records to study EBITDA relationships with Enterprise Value, Market Cap, Revenue Growth, Net Income Growth, and Debt Growth.
- Cleaned data using IQR; computed descriptive statistics and built regression models in Excel.
- Created Excel dashboards (pivot tables, slicers) and Tableau dashboards for interactive exploration of KPIs.
- Implemented predictive models in Python (Logistic Regression, SMOTE) achieving ~83% fraud detection accuracy using M-Score.
- Tech Stack: Excel, Tableau, Python, Google Colab, Pandas, NumPy, Scikit-learn.
- Key Achievement: Delivered a dual-method predictive framework in Excel-based BI and Python-based ML.






