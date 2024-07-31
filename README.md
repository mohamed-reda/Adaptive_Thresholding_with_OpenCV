# Adaptive Thresholding with OpenCV

## Overview

This repository explores adaptive thresholding techniques using OpenCV, focusing on converting images to black and white
under varying lighting conditions. Adaptive thresholding is particularly useful for images with uneven illumination,
where traditional static thresholding falls short.

## Content

The project includes:

- **Introduction to Adaptive Thresholding**: Explains the concept and importance of adaptive thresholding in image
  processing.
- **Histogram Analysis**: Demonstrates how to analyze the histogram of a grayscale image to understand its intensity
  distribution.
- **Adaptive Thresholding Methods**:
    - **Adaptive Mean Thresholding**: Computes the threshold for a pixel based on the mean of a neighborhood around it.
    - **Adaptive Gaussian Thresholding**: Similar to mean thresholding but weights pixels in the neighborhood based on a
      Gaussian distribution.
- **Comparative Analysis**: Shows the results of static and adaptive thresholding on different images, highlighting the
  advantages of adaptive methods.

## Examples

- **Sudoku Image**: Analyzes a Sudoku image with varied backgrounds, demonstrating the effectiveness of adaptive
  thresholding in extracting numbers and lines.
- **Play Space Image**: Applies adaptive thresholding to a play space image, showcasing its artistic effect on
  photograph borders.

## Getting Started

To run the project, ensure you have the following dependencies installed:

- Python 3.x
- OpenCV
- NumPy
- Matplotlib

Clone the repository and follow the instructions in the Jupyter Notebook to see adaptive thresholding in action.

## Conclusion

Adaptive thresholding is a powerful tool for image processing, especially when dealing with images that have
inconsistent lighting. This project highlights its practical applications and effectiveness compared to traditional
thresholding methods.

For more details and the complete code, explore the repository. Happy image processing!