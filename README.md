# deep-learning-journey

<br>

# Traffic Sign Classification

A CNN-based deep learning project for classifying **43 different traffic signs** using the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset.

## Overview

This project uses **TensorFlow/Keras** to build a Convolutional Neural Network (CNN) that recognizes traffic signs from images.

* **Classes:** 43
* **Image size:** 32 × 32
* **Framework:** TensorFlow / Keras
* **Task:** Multi-class image classification
* **Test Accuracy:** ~95%+

## Dataset

The project uses the GTSRB dataset.

**Dataset:** [Download here](https://zenodo.org/records/13741936/files/data.zip?download=1)

The dataset contains images of 43 different categories of German traffic signs.

## Model

The model is a custom CNN consisting of:

* Convolutional layers
* Batch Normalization
* ReLU activation
* Max Pooling
* Dropout
* Global Average Pooling
* Fully Connected layers
* Softmax output layer

The model predicts one of the 43 traffic sign classes.

## Project Structure

```text
traffic-sign-classification/
│
├── dataset/
│   ├── Train/
│   ├── Test/
│   ├── Train.csv
│   ├── Test.csv
│   └── signnames.csv
│
├── traffic_sign_classification.ipynb
├── requirements.txt
└── README.md
```

## How to Run

Clone the repository:

```bash
git clone <YOUR-REPOSITORY-URL>
cd <PROJECT-FOLDER>
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Then open the notebook:

```bash
jupyter notebook
```

Run the cells in `traffic_sign_classification.ipynb`.

## Results

The trained CNN achieved approximately **95%+ accuracy on the test set**.

The project also includes analysis of misclassified images, including the **Top 5 high-confidence errors** made by the model.

## Technologies

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook
