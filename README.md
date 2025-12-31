Project Overview

This project explores the use of computer vision and deep learning to estimate a person’s age from a facial photograph. The goal is to assist retail businesses in automating age verification decisions, such as determining when to request ID before selling age-restricted products.

A convolutional neural network based on ResNet50 was trained using transfer learning with ImageNet weights. The model learns visual patterns associated with aging, including facial structure, skin texture, and proportions.

Key Steps

Performed exploratory data analysis on facial images and age distribution

Preprocessed and normalized image data

Trained a ResNet50-based regression model on GPU infrastructure

Evaluated performance using MAE and MSE metrics

Results

Validation MAE stabilized at approximately 3.1 years, indicating strong predictive accuracy

Training and validation loss decreased consistently, showing effective learning

Minor late-stage overfitting was observed, but overall generalization remained strong

Business Value

This solution demonstrates how computer vision can support automated age verification, reduce human error at checkout, and improve compliance with age-restricted sales policies. The approach can be extended to other applications such as demographic analysis, customer analytics, and identity verification.

Future Improvements

Fine-tuning deeper ResNet layers

Adding stronger data augmentation

Testing alternative architectures (e.g., EfficientNet)

Increasing input resolution for higher precision
