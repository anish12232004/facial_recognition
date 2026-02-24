📌 Face Recognition Using SVM

📖 Project Overview

This project implements a Face Recognition system using a Support Vector Machine (SVM) classifier. The model is trained on labeled face images and predicts the identity of individuals in unseen test images.The system evaluates performance using accuracy, classification reports, and a confusion matrix.

🎯 Objectives

- Load and preprocess a face dataset

- Split data into training and testing sets

- Train an SVM classifier for face recognition

- Evaluate model performance

- Visualize predictions with confidence scores

🗂 Dataset

- Face images resized to 50 × 37 pixels

- Images normalized to range 0–1

- Total images: 1560

- Number of classes: 12

- Each image contains a labeled face of a known individual.

🛠 Technologies Used

- Python

- NumPy

- OpenCV

- Matplotlib

- Scikit-learn

⚙️ Methodology

- Load dataset

- Normalize image pixel values

- Flatten images for SVM input

- Perform train-test split

- Train Support Vector Machine classifier

- Predict test data

Evaluate using:

- Accuracy score

- Classification report

- Confusion matrix

Display predictions with:

- Bounding box

- Predicted name

- Confidence score

📊 Model Performance

Test Accuracy: 83%

🖼 Output Visualization

The model displays 5 test images in a row with:

- Predicted name

- True label

- Overall accuracy at top

📌 Conclusion

The SVM-based face recognition system successfully classifies individuals with good accuracy (83%). Performance can be further improved by:

Using higher resolution images

Applying PCA (Eigenfaces)

Hyperparameter tuning

Using deep learning approaches (CNN)

🚀 Future Improvements

Implement real-time face recognition

Integrate webcam input

Deploy as a web application

Compare SVM with CNN models

📎 How to Run

Install required libraries

Run the Jupyter Notebook

Execute cells sequentially

View accuracy, confusion matrix, and visualization output