\# Handwritten Character Recognition Using CNN



\## Project Overview

This project uses Convolutional Neural Networks (CNNs) to recognize handwritten digits and English letters using the MNIST and EMNIST Letters datasets. It was developed as part of the CodeAlpha Machine Learning Internship.



\## Objectives

\- Recognize handwritten digits from 0 to 9.

\- Recognize handwritten English letters from A to Z.

\- Train CNN models using PyTorch.

\- Evaluate model performance using accuracy, precision, recall, F1-score, and a confusion matrix.



\## Datasets

\- \*\*MNIST:\*\* 60,000 training images and 10,000 testing images.

\- \*\*EMNIST Letters:\*\* 124,800 training images and 20,800 testing images.

\- Image dimensions: 28 × 28 pixels, grayscale.



\## Technologies Used

\- Python

\- PyTorch

\- Torchvision

\- NumPy

\- Matplotlib

\- Scikit-learn

\- Jupyter Notebook



\## Model Architecture

The CNN architecture uses convolutional layers, max pooling, and fully connected layers to classify handwritten images.



Two models were trained:

1\. MNIST digit recognition — 10 classes.

2\. EMNIST letter recognition — 26 classes.



\## Results



| Model | Dataset | Test Accuracy |

|---|---|---:|

| Digit Recognition CNN | MNIST | 98.91% |

| Letter Recognition CNN | EMNIST Letters | 92.81% |



\## Project Structure



```text

CodeAlpha\_Handwritten\_Character\_Recognition\_CNN/

├── Handwritten\_Character\_Recognition\_CNN.ipynb

├── README.md

├── data/

├── models/

│   ├── handwritten\_cnn\_mnist.pth

│   └── handwritten\_letters\_cnn.pth

└── results/

&#x20;   ├── letter\_classification\_report.txt

&#x20;   └── letter\_confusion\_matrix.png

```



\## How to Run



1\. Install Python.

2\. Install the required libraries:



&#x20;  ```bash

&#x20;  pip install torch torchvision numpy matplotlib scikit-learn jupyter

&#x20;  ```



3\. Open the notebook using Jupyter Notebook.

4\. Run the cells in order to load the datasets, train the models, and evaluate performance.



\## Evaluation

The models were evaluated using their respective test datasets. The project includes a letter classification report and a confusion matrix.



\## Internship

\*\*Program:\*\* CodeAlpha Machine Learning Internship



\*\*Task:\*\* Handwritten Character Recognition



\## Author

Sudais Khan

