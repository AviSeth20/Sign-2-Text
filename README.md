# Sign Language to Text Interpreter

## 🖥️ **Project Overview**

This project is an **American Sign Language (ASL) to Text Interpreter**, designed to convert hand gestures (representing individual ASL letters) into **words and sentences**. By leveraging deep learning techniques and image processing, this interpreter takes individual hand gestures as input and outputs text that forms meaningful sentences.

## 🔧 **Technologies Used**

This project utilizes the following libraries and frameworks:

- **NumPy**: For handling numerical operations and data manipulation.
- **OpenCV**: For image processing and feature extraction from hand gestures.
- **TensorFlow**: A framework for building and training the deep learning model.
- **Keras**: High-level neural networks API for TensorFlow, used for training and evaluating the model.
- **Tkinter (tk)**: For building the GUI (graphical user interface) to interact with the interpreter.
- **Pillow**: For handling image processing tasks.
- **pyenchant**: A spell-checking library for text validation.
- **cyhunspell**: A library for checking and correcting misspelled words in real-time.

## ⚙️ **How It Works**

The ASL Interpreter recognizes **individual ASL letters** (each hand gesture representing a letter of the alphabet) and converts them into **words and sentences**. The process involves the following steps:

1. **Image Input**: The system captures images of hand gestures through a webcam or file input.
2. **Preprocessing**: The captured images are preprocessed to enhance the visibility of the hand gestures.
3. **Prediction**: A trained deep learning model predicts the corresponding letter for each hand gesture.
4. **Text Construction**: The recognized letters are combined to form words and sentences.
5. **Output**: The resulting text is displayed on the GUI or console.

## 📚 **Dataset**

The model was trained on **ASL Alphabet Datasets** that contain labeled images of hand gestures corresponding to individual ASL letters. These datasets are crucial for training the model to recognize the gestures and classify them into the correct letters.

You can find datasets like [ASL Alphabet Dataset on Kaggle](https://www.kaggle.com/) or similar publicly available datasets for training.
