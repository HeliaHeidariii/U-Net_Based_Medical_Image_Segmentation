# U-Net Based Medical Image Segmentation

This project implements the **U-Net architecture**, a widely used deep learning model for biomedical image segmentation. The primary goal is to segment medical images and detect abnormalities with high precision and recall. The U-Net model is known for its effectiveness in image segmentation tasks due to its symmetric architecture and ability to capture both high- and low-level features.

## Features

- **Segmentation**: Accurately segments medical images to identify specific areas of interest (e.g., tumors or other abnormalities).
- **U-Net Architecture**: Implements the U-Net deep learning model, optimized for medical image processing.
- **Performance Metrics**: Evaluates the model's performance using metrics like accuracy, precision, recall, F1 score, and a confusion matrix.
- **Custom Dataset**: Works with medical image datasets, using ground-truth masks for training and validation.

## Technologies Used

- `TensorFlow/Keras`: For building and training the U-Net model.
- `scikit-learn`: To calculate performance metrics such as accuracy, precision, recall, F1 score, and confusion matrix.
- `NumPy`: For numerical operations and data manipulation.
- `Matplotlib`: For visualizing the segmentation results and performance metrics.

## How to Use

1. **Install Dependencies**  
   Make sure you have all required dependencies installed by running the following command:
   ```bash
   pip install tensorflow scikit-learn numpy matplotlib
   ```

2. **Dataset Preparation**  
   Prepare your dataset with image and mask pairs. Ensure the dataset is organized with separate directories for training, validation, and test sets. The project uses the U-Net architecture to predict segmentation masks.

3. **Run the Project**  
   To train the model and evaluate its performance, execute the notebook. Model predictions can be visualized to assess segmentation quality.

## Performance

The U-Net model used in this project achieves high accuracy in segmenting medical images. The performance metrics include:

- **Accuracy**: Measures the proportion of correctly predicted pixels.
- **Precision**: Evaluates the model's ability to correctly predict positive samples.
- **Recall**: Determines the model's ability to find all relevant cases.
- **F1 Score**: The harmonic mean of precision and recall.
- **Confusion Matrix**: A detailed breakdown of the model's true/false positive and negative rates.

## Example Output

After training the U-Net model, you will see visualizations of the predicted masks compared to the ground truth, along with the following metrics:

- **Accuracy**: ~96.95%
- **Precision**: ~91.98%
- **Recall**: ~85.51%
- **F1 Score**: ~88.63%
