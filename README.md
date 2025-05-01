# image_classification

# 🧠 Objective:
This project aims to classify facial images of individuals as "Smoker" or "Non-Smoker" using deep learning. This model can potentially assist in healthcare screening or behavioral analysis from visual data.

# 🖼️ Dataset Description:
Type: Image Dataset

Classes: Smoker, Non-Smoker

Image Size: Resized to 150x150 pixels

Data Split:

train/ – Training images

test/ – Testing images

predict/ – Unlabeled images for final prediction

Total Images: ~25,000 (as per your previous project context)

# 🔧 Tools and Libraries:
Python (Jupyter Notebook)

TensorFlow / Keras

NumPy, Matplotlib, Seaborn

OpenCV (for image preprocessing)

Sklearn (for performance metrics)

# 🚀 Workflow Summary:
Image Loading & Preprocessing

Resizing, rescaling, and normalization of pixel values

CNN Architecture

Convolution layers with ReLU activation

MaxPooling layers for downsampling

Dropout for regularization

Dense layers for final classification

Model Training

Loss function: binary_crossentropy

Optimizer: Adam

Evaluation using accuracy and loss graphs

Testing & Prediction

Evaluated on unseen test data

Predictions on real-world images

Performance Evaluation

Accuracy score

Confusion matrix

Precision, Recall, F1 Score

# 📊 Results:
Achieved training accuracy of ~95% and validation accuracy of ~92%

Model is capable of predicting smoker status based on facial features

# ✅ Future Improvements:
Use transfer learning (e.g., MobileNet, VGG16) for better accuracy

Improve generalization using data augmentation

Expand dataset diversity (age, gender, ethnicity)

