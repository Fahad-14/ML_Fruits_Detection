# ML_Fruits_Detection
Dataset Image Classification using SVM

This Python script performs image classification using Support Vector Machines (SVM) on a dataset containing images of fruits. It extracts color histogram features from the images and trains an SVM classifier to classify them into different fruit categories. Additionally, the script allows predicting the label of a new image.

Instructions:

1. Requirements:
   - Python 3.x
   - OpenCV (`opencv-python` package)
   - NumPy (`numpy` package)
   - scikit-learn (`scikit-learn` package)

2. Dataset Preparation:
   - Organize your dataset into folders where each folder represents a different category of fruits.
   - Ensure that each fruit category has a sufficient number of images for training.

3. Running the Script:
   - Run the script in a Python environment.
   - When prompted, provide the path to the dataset folder containing subfolders of fruit images.
   - After training, the script will output the accuracy of the classifier on the test set.

4. Predicting New Images:
   - Once the classifier is trained, you can input the path to a new image to predict its fruit category.
   - Ensure that the image format is compatible (e.g., JPEG, PNG).

Files:

   - image_classification_svm.py: Python script for image classification using SVM.
   - README.md: Instructions and information about the script.

Usage:

1. Clone or download the repository to your local machine.
2. Install the required dependencies mentioned in the requirements section.
3. Prepare your dataset according to the instructions provided.
4. Run the `image_classification_svm.py` script.
5. Follow the prompts to input the dataset path and path to a new image for prediction.

Example:

```bash
$ python image_classification_svm.py
Enter the path to the dataset folder: /path/to/your/dataset
Accuracy: 0.85
Enter the path to the new image: /path/to/your/new/image.jpg
Predicted fruit: Apple
```

Note:

   - You can modify the `extract_features` function to use different feature extraction techniques for better classification accuracy.
   - Experiment with different SVM kernels and parameters for optimization based on your dataset characteristics.

Author:

This script was developed by Fahad Hussain and Mateen Nizami and can be freely used and modified under the MIT License.

