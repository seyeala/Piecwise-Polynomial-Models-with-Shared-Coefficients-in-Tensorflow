# Piecwise-Polynomial-Models-with-Shared-Coefficients-in-Tensorflow

Introduction

This repository contains a TensorFlow/Keras implementation of a dual polynomial model that shares a set of coefficients. The model is intended to be used with two datasets, each represented by a polynomial function with shared coefficients. Additionally, the model applies a high-temperature sigmoid-based conditioning on a break point. The idea is inspired from the Mooney-Rivlin solid equation used in material science.

Features:

Data reading from Google Drive. Custom TensorFlow layer to manage shared coefficients. Custom TensorFlow layer to represent a dual polynomial model. Custom loss function for training. A high-temperature sigmoid function to provide conditional computation based on a break point. How to Use

Prerequisites: You should have TensorFlow installed. Google Colab is used for the implementation, so make sure you have access to Google Drive to store and retrieve your dataset files. Data: Ensure your datasets are in .csv format and are structured with two columns labeled "A" and "B". Mount your Google Drive and provide the necessary file paths. Parameters: Set the filenamecut, filenamenocut, and foldername to point to your dataset files on Google Drive. Adjust the model parameters such as numberofbrakpoints and epch as necessary. Run: Execute the code. The model will be trained on the provided datasets. A plot showing the real vs. predicted data points for both datasets will be generated at the end of the training. Results: At the end of the execution, the shared coefficients, break points, and other parameters will be printed for both polynomial models. Contribution

Contributions are welcome! Please ensure that any changes do not break the existing functionality. New features, bug fixes, and optimizations are always appreciated.

Acknowledgments

This implementation was inspired by the Mooney-Rivlin in hyperelastic materials. Kudos to the original researchers and contributors.
