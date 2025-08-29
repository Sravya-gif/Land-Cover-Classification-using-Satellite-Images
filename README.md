# Land-Cover-Classification-using-Satellite-Images
Project Overview:
This project focuses on Land Cover Classification  using satellite imagery to automatically identify and categorize different types of land cover such as urban areas, water bodies, forests, agricultural land, and barren regions. Accurate land cover classification plays a vital role in urban planning, agriculture monitoring and climate studies. The project utilizes remote sensing data and applies deep learning feature extraction combined with machine learning classification to improve accuracy compared to traditional methods.

Objectives:
To analyze satellite images and classify them into meaningful land cover categories.
To compare the performance of machine learning algorithms with deep learning-based feature extraction.
To demonstrate how hybrid models (DL + ML) outperform traditional classification techniques.

Dataset:
Dataset Used: EuroSAT Dataset
Classes (10 categories):
Annual Crop
Forest
Herbaceous Vegetation
Highway
Industrial
Pasture
Permanent Crop
Residential
River
Sea/Lake

Methodology:

Data Preprocessing:
Image resizing, normalization, and augmentation.
Splitting dataset into train/test/validation sets.

Feature Extraction:
Use a Convolutional Neural Network (CNN) to automatically extract spatial features from satellite images.

Classification:
Train Machine Learning models (e.g., SVM, Random Forest, XGBoost) using the extracted features.
Compare results with standalone CNN classification.

Evaluation Metrics:
Accuracy
Precision, Recall, F1-score
Confusion Matrix

Tools & Technologies:
Programming Language: Python
Libraries/Frameworks:
TensorFlow / Keras (for CNN feature extraction)
Scikit-learn (for ML models)
Dataset: EuroSAT (Sentinel-2 satellite images)

Results:
Traditional ML algorithms showed moderate accuracy when applied directly to raw images.
CNN-based feature extraction significantly improved classification performance.
Hybrid approach (CNN + ML classifiers like SVM/Random Forest) gave the best accuracy, combining the strengths of both DL and ML.
Accuracy: 89%
