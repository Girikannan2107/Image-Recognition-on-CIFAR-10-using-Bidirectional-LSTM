🧠 Image Recognition on CIFAR-10 using Bidirectional LSTM

This project demonstrates image classification on the CIFAR-10 dataset using a Bidirectional Long Short-Term Memory (BiLSTM) network. The objective is to explore how recurrent neural networks (RNNs) can be applied to image recognition tasks by treating images as sequences.

The model is trained and evaluated on the CIFAR-10 dataset, which contains 60,000 color images across 10 classes. This project includes data preprocessing, model building, training, evaluation, and visualization of results.

🚀 Features

CIFAR-10 dataset loading and preprocessing

Image normalization and reshaping into sequences

Bidirectional LSTM based deep learning model

Model training and validation

Accuracy and loss visualization

Performance evaluation on test data

🛠️ Technologies Used

Python

TensorFlow / Keras

NumPy

Matplotlib

Jupyter Notebook / Google Colab

📂 Project Structure
Image-Recognition-on-CIFAR-10-using-Bidirectional-LSTM
│
├── deep_learning.ipynb
├── README.md
└── requirements.txt

▶️ How to Run
pip install tensorflow numpy matplotlib
jupyter notebook deep_learning.ipynb


Or run directly in Google Colab.

📊 Dataset

CIFAR-10 Dataset

60,000 color images (32×32)

10 classes:

Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck

🧠 Model Architecture

Input reshaped into sequential format

Bidirectional LSTM layers

Fully connected dense layers

Softmax output layer

📌 Results

The model achieves good classification performance, showing that Bidirectional LSTM networks can be adapted for image recognition tasks, although CNN-based models typically achieve higher accuracy.

🎯 Use Cases

Academic projects

Learning deep learning concepts

Sequence modeling experiments

Research and exploration

📜 License

This project is for educational and research purposes only.
