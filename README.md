# Breast Cancer Classification Using CNN

## Project Overview

This project is designed to classify breast cancer tumors as either malignant or benign using a Convolutional Neural Network (CNN). The model is trained on the Breast Cancer Wisconsin (Diagnostic) dataset, applying advanced deep learning techniques to enhance diagnostic accuracy. Additionally, the project includes a feature that suggests the closest hospital to patients detected with cancer, using a key-value pair system. The primary goal is to create a reliable tool to aid in early detection and provide practical next steps for treatment.

## Dataset

The project utilizes the Breast Cancer Wisconsin (Diagnostic) dataset, which includes features derived from digitized images of fine needle aspirate (FNA) samples from breast masses. These features capture the characteristics of cell nuclei present in the samples.

- **Number of Instances**: 569
- **Number of Features**: 30 (excluding an ID column)
- **Classes**: Malignant (212), Benign (357)

## Project Structure

- **data/**: Contains the dataset files.
- **notebooks/**: Jupyter notebooks with detailed analysis and model development.
- **models/**: Saved models ready for inference.
- **src/**: Source code for data preprocessing, model training, and evaluation.

## Key Features

- **Data Preprocessing**: Addressed missing values, normalized features, and split the dataset into training and testing sets.
- **Model Architecture**: Designed a CNN model with multiple convolutional and pooling layers to extract critical features from the input data.
- **Training**: The model was trained using the Adam optimizer with cross-entropy loss as the objective function.
- **Evaluation**: Assessed model performance using metrics such as accuracy, precision, recall, and F1-score.
- **Hospital Suggestion Feature**: Implemented a key-value pair system that provides the closest hospital suggestion for patients detected with cancer.
- **Results**: Achieved an accuracy of **93%** (replace with actual accuracy) on the test set, offering insights into the model's performance and potential areas for enhancement.

## Future Work

- **Model Optimization**: Further tuning of hyperparameters and exploration of alternative architectures to boost accuracy.
- **Feature Engineering**: Exploring additional features or techniques to improve model performance.
- **Deployment**: Creating a user-friendly interface for clinical application, enabling real-time diagnosis.

## Contributing

Contributions are highly appreciated! Please feel free to submit a Pull Request or open an issue if you have suggestions or improvements.
Google Collab Link to the project: https://colab.research.google.com/drive/1bEkVAjp-Fq2mM4PvheUJelAjABhiS7XI#scrollTo=M7owYocGGhei
