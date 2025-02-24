Brain Tumor Detection and Segmentation Using MRI Images (MATLAB)

Overview

This project focuses on the detection and segmentation of brain tumors from MRI images using image processing techniques in MATLAB. It aims to assist medical professionals in early diagnosis by accurately identifying tumor regions.

Features

Preprocessing: Enhances MRI images by reducing noise and improving contrast.

Segmentation: Uses techniques like Otsu's thresholding, k-means clustering, and region-growing methods.

Feature Extraction: Analyzes shape, texture, and intensity characteristics of the tumor.

Classification (Optional): Implements machine learning methods like SVM for tumor categorization.

Visualization: Highlights detected tumor areas on MRI images.

Technologies Used

MATLAB (Image Processing Toolbox)

MRI Image Dataset

Image Processing Techniques

Machine Learning (if classification is implemented)

Implementation Steps

1. Data Collection

Used publicly available MRI datasets containing normal and tumor-affected brain images.

2. Image Preprocessing

Converted images to grayscale (if necessary).

Applied filtering techniques (Gaussian, Median) to remove noise.

Enhanced contrast using histogram equalization.

3. Tumor Segmentation

Applied Otsu's thresholding and k-means clustering for tumor region extraction.

Used region-growing and edge-detection methods to refine segmentation.

4. Feature Extraction

Extracted features such as area, perimeter, mean intensity, and texture properties.

5. Classification (Optional)

Used SVM or deep learning techniques to classify tumor and non-tumor images.

6. Visualization

Highlighted detected tumor regions in the original MRI images for better understanding.

Results

Successfully segmented and detected tumor regions in MRI images.

Provided an efficient way to assist medical professionals in diagnosis.

How to Run the Project

Install MATLAB with the Image Processing Toolbox.

Download the project files and dataset.

Run BrainTumorDetection.m in MATLAB.

Load an MRI image and follow the on-screen instructions to process and visualize the results.

Future Enhancements

Improve accuracy using deep learning (CNN-based models).

Automate feature extraction and classification.

Create a GUI for better user interaction.

Contributions

Feel free to contribute by improving the segmentation techniques, adding new features, or optimizing the code.

License

This project is open-source and available under the MIT License.

