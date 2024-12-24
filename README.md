# Hexadecimal Digit Recognizer

This repository contains a machine learning project designed to classify grayscale images of handwritten hexadecimal digits (0-9, A-F) and empty images. The project leverages Support Vector Machines (SVM) and Random Forest classifiers, along with PCA for dimensionality reduction, to achieve efficient and accurate recognition.

## Features

- **Handwritten Hexadecimal Recognition**: Classification of digits and empty images using machine learning techniques.
- **Dimensionality Reduction**: Principal Component Analysis (PCA) to enhance computational efficiency.
- **Robust Preprocessing**: Data scaling, normalization, and stratified splitting for improved performance.
- **Comparative Analysis**: Evaluation of classifier performance with and without PCA.

## File Structure

- `hex_digit_recognizer.ipynb`: The main Jupyter Notebook containing the implementation of the project.
- `project_report.pdf`: The detailed project report, including methodology, results, and insights.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/brageaasen/Grayscale-HexDigit-Identification-with-SVM-and-Random-Forest.git
   cd Grayscale-HexDigit-Identification-with-SVM-and-Random-Forest
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook hex_digit_recognizer.ipynb
   ```
3. Explore the project report for detailed documentation:
- Refer to `project_report.pdf` for in-depth explanations, results, and conclusions.

## Requirements
- Python 3.x
- Jupyter Notebook
- Required libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`

## References
For a detailed explanation of the project's methodologies and findings, see [project_report.pdf](project_report.pdf).
