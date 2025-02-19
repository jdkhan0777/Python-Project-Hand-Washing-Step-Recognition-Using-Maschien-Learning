# Python-Project-Hand-Washing-Step-Recognition-Using-Machine-Learning
# Hand Washing Step Recognition

## Overview
This project uses machine learning to recognize the steps of handwashing based on images. The dataset consists of thousands of images depicting eight different handwashing steps. A trained model predicts which step a person is performing when they upload an image.

## Dataset
The dataset contains a large collection of handwashing images in **JPG format**, covering the eight steps of hand hygiene.

## Technologies Used
- Python (NumPy, Pandas, OpenCV, TensorFlow, Scikit-learn)
- Google Colab

## Approach
1. **Data Preprocessing**:
   - Load and clean the dataset.
   - Remove corrupted images and standardize image sizes.
2. **Exploratory Data Analysis (EDA)**:
   - Visualize sample images from each handwashing step.
   - Identify data imbalances.
3. **Model Training**:
   - Use a deep learning model (CNN) to classify handwashing steps.
   - Train the model using thousands of labeled images.
4. **Evaluation**:
   - Assess model accuracy using confusion matrices and performance metrics.
5. **Prediction**:
   - Upload an image, and the model predicts which handwashing step is being performed.

## Results
- The model successfully classifies handwashing steps with high accuracy.
- Data preprocessing improved model efficiency.

## How to Use
1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```
2. Open `Covid-Python.ipynb` in Google Colab.
3. Run all cells to train and test the model.
4. Upload an image to get a prediction of the handwashing step.

## Future Improvements
- Expand the dataset with more diverse images.
- Optimize the model with additional training techniques.
- Deploy the model as a web app for real-time predictions.


