Fruit-Type-Classifier

A machine learning project that classifies fruit images into their respective categories using **TensorFlow/Keras**.
This project was built and trained using the [Fruits 360 Dataset](https://www.kaggle.com/datasets/moltean/fruits).

Features

* Classifies fruit images into multiple categories
* Deep Learning model built with TensorFlow/Keras
* Achieves high accuracy on the test dataset
* Easily extendable to other fruit datasets

Dataset

The dataset used is **Fruits 360**, which contains over 70,000 images of fruits, taken in consistent lighting and background conditions.
Download it here: [Kaggle - Fruits 360 Dataset](https://www.kaggle.com/datasets/moltean/fruits)

Installation

Clone the repository:

```bash
git clone https://github.com/CodeByHarini/Fruit-Type-Classifier-.git
cd Fruit-Type-Classifier
```

Install dependencies:

```bash
pip install -r requirements.txt
```

▶️ Usage

Run the classifier:

```bash
python classify.py --image path_to_your_fruit_image.jpg
```

Or open the Jupyter Notebook:

```bash
jupyter notebook "fruit type.ipynb"
```

Model

* Framework: **TensorFlow 2.x / Keras**
* Model type: Convolutional Neural Network (CNN)
* Saved model file: `fruit_classifier.keras` (tracked with Git LFS)

 Sample Prediction
 
[Sample Output](Sample_output.jpeg)

License:

This project is licensed under the MIT License. Feel free to use, modify, and distribute.

 
