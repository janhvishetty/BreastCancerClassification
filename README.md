# BreastCancerClassification
Breast Cancer Classification Using CNN
Project Overview
This project focuses on classifying breast cancer tumors as either malignant or benign using a Convolutional Neural Network (CNN). The model is trained on the Breast Cancer Wisconsin (Diagnostic) dataset to improve diagnostic accuracy by leveraging advanced deep learning techniques. The primary goal is to develop a reliable model that can assist in early detection and treatment planning for breast cancer.

Dataset
The dataset used is the Breast Cancer Wisconsin (Diagnostic) dataset, which contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The features describe the characteristics of the cell nuclei present in the image.

Number of instances: 569

Number of features: 30 (plus an ID column)

Classes: Malignant (212), Benign (357)

Project Structure
data/: Contains the dataset files.

notebooks/: Jupyter notebooks with detailed analysis and model development.

models/: Saved models for inference.

src/: Source code for data processing, model training, and evaluation.

README.md: Project documentation.
Key Features
Data Preprocessing: Handled missing values, normalized feature values, and split the dataset into training and testing sets.
Model Architecture: Developed a CNN model with multiple convolutional and pooling layers to extract relevant features from the input data.
Training: The model was trained using the Adam optimizer and cross-entropy loss.
Evaluation: Model performance was evaluated using accuracy, precision, recall, and F1-score metrics.
Results: Achieved an accuracy of X% (replace with actual accuracy) on the test set, with insights into the model's strengths and areas for improvement.

Future Work
Model Optimization: Fine-tuning hyperparameters and exploring different architectures to improve accuracy.
Feature Engineering: Investigating additional features or techniques to enhance model performance.
Deployment: Developing a user-friendly interface for clinicians to use the model for real-time diagnosis.
Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an issue if you have suggestions or improvements.
