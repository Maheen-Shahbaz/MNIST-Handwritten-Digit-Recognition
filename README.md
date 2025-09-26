
# **MNIST Handwritten Digit Recognition**

## **Project Description**

This project uses the **MNIST dataset of handwritten digits** to train a machine learning model that can **recognize and classify digits from 0 to 9**. The dataset is provided in CSV format, and the project demonstrates:

* Data preprocessing and normalization
* Model training using **Random Forest Classifier** (CPU-friendly)
* Evaluation with **accuracy and confusion matrix**
* Visualization of **sample images and predictions**

> This version avoids installing TensorFlow, making it **fast, lightweight, and easy to run** on any system.

## **Installation**

1. Clone this repository:
git clone https://github.com/your-username/MNIST-Digit-Recognition.git
cd MNIST-Digit-Recognition

2. Install required packages:

pip install pandas numpy matplotlib scikit-learn
> No TensorFlow installation is required.

## **Usage**

1. Open the Jupyter Notebook:
jupyter notebook mnist_digit_recognition.ipynb

2. Run each cell **in order**:

   * Import libraries
   * Load CSV datasets
   * Preprocess and visualize data
   * Train Random Forest model
   * Evaluate and visualize predictions

3. Check results:

   * **Accuracy on test set**
   * **Confusion matrix**
   * **Sample predictions vs true labels**
  
## **Features**

* Fully CSV-based, no TensorFlow download required
* Fast training on CPU (Random Forest)
* Graphs for **digit distribution, training/evaluation results**
* Confusion matrix and sample predictions for analysis
* Clean, readable, and professional code
* 
## **Results**

* Test accuracy: ~**95%** (varies depending on training)
* Confusion matrix shows which digits are commonly misclassified
* Sample prediction plots demonstrate model performance

## **Notes**

* Can be extended to CNNs using Keras or TensorFlow if needed
* Lightweight and ideal for **internship submission or beginner ML projects**


