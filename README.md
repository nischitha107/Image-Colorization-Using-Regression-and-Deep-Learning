🎨 Image Colorization Using Regression and Support Vector Regression

This project focuses on automatic image colorization by predicting color information from grayscale images using regression-based machine learning models. The goal is to reconstruct realistic color images by learning mappings between luminance and chrominance components.

🔍 Project Overview

Images from the Tiny ImageNet dataset were converted from RGB to LAB color space, where the L channel represents grayscale input and the a and b channels represent color output. The model predicts color channels using grayscale information as input, framing colorization as a supervised regression problem.

🧠 Modeling Approach

Dimensionality reduction was applied using PCA to manage high-dimensional image data. Multiple models were implemented, including linear regression with gradient descent and support vector regression. Performance was evaluated using MSE, SSIM, and PSNR to assess both numerical accuracy and perceptual image quality.

📈 Outcome

The project demonstrates how traditional machine learning models can be applied to image colorization, highlighting trade-offs between computational efficiency and visual quality. Results show meaningful color reconstruction with improved structural similarity.

🛠 Tools Used

Python, PyTorch, scikit-learn, PCA, Linear Regression, Support Vector Regression, NumPy, matplotlib
