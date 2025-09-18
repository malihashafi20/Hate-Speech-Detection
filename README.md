# 😠 Hate Speech Detection using Deep Learning

This project implements a deep learning model to classify social media text as Hate Speech, Offensive Language, or Neutral. It's an end-to-end NLP solution that covers data preprocessing, model building, and evaluation.

## 🚀 Key Features

* **Data Handling**: Loads and balances a dataset of labeled tweets.
* **Text Preprocessing**: Includes lowercasing, punctuation removal, stopword removal, and lemmatization.
* **Model Architecture**: A **Bidirectional LSTM** network built with TensorFlow/Keras.
* **Performance Metrics**: Tracks model accuracy and loss during training and validation.

---

## 🛠️ How It Works

1.  **Data Preparation**: The initial imbalanced dataset is balanced using a combination of upsampling and downsampling.
2.  **Preprocessing**: Text is cleaned and normalized. A **Word Cloud**  is used to visualize the most frequent words.
3.  **Tokenization & Padding**: Text is converted into numerical sequences and padded to a uniform length, preparing it for the neural network.
4.  **Model Training**: The model is trained with `EarlyStopping` and `ReduceLROnPlateau` callbacks to optimize the learning process.
5.  **Evaluation**: The model's performance is evaluated using plots for loss and accuracy.

---

## 📁 Repository Contents

* `hate_speech.csv`: The dataset used for training and testing.
* `README.md`: This file.
* *Other files (e.g., Jupyter Notebook, Python script)*: Code for the entire pipeline.

---

## ⚙️ Dependencies

To run this project, you'll need the following libraries:

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `nltk`
* `tensorflow`
* `scikit-learn`
* `wordcloud`

---

## 🤝 Contributing

Feel free to open issues or submit pull requests. All contributions are welcome!
