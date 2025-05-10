# LinkedIn Learning: Getting Started with AI and Machine Learning

This repository contains notebooks and materials from LinkedIn Learning's **"Getting Started with AI and Machine Learning"** learning path. These examples demonstrate various machine learning and deep learning concepts applied to real-world problems, implemented in Python using TensorFlow and Keras.

## 🚀 Overview

This repository contains my implementations and exercises from the LinkedIn Learning path "Getting Started with AI and Machine Learning." The notebooks cover deep learning models for classification tasks, ranging from classic datasets to practical applications in text analysis and IT operations.

These materials are provided as a reference for those also taking the course or for anyone interested in practical deep learning examples.

## 📋 Course Contents

This repository includes implementations from the LinkedIn Learning path, specifically from these modules:

### Classification Examples

- **Iris Classification (Deep Learning)** - Implementation of a deep neural network to classify the famous Iris flower dataset (Module 04).
- **Spam Classification** - Using natural language processing and deep learning to detect spam messages (Module 05).
- **IT Incident Root Cause Analysis** - Applying deep learning to automatically determine the root cause of IT incidents based on system metrics and error codes (Module 06).

## 📊 Datasets

- `iris.csv` - The classic Iris flower dataset with measurements for three different species
- `Spam-Classification.csv` - Text messages labeled as spam or ham (not spam)
- `root_cause_analysis.csv` - Synthetic IT incident data with various system metrics and root cause labels

## 🛠️ Setup and Requirements

To run these notebooks, you'll need:

```
- Python 3.8+
- TensorFlow 2.x
- Keras
- Pandas
- NumPy
- Matplotlib
- scikit-learn
- NLTK (for text processing)
```

You can install all requirements with:

```bash
pip install -r requirements.txt
```

## 📘 Notebooks

### 1. Iris Deep Learning Classification (Module 04)
This notebook demonstrates a basic deep learning model for classifying Iris flowers based on their measurements.

Key concepts:
- Data preprocessing and normalization
- Building a neural network with Keras
- Model training and evaluation
- Saving and loading models
- Making predictions with the trained model

### 2. Spam Classification (Module 05)
This notebook demonstrates text classification using deep learning to identify spam messages.

Key concepts:
- Text preprocessing with NLTK
- Converting text to numerical features using TF-IDF
- Building and training a neural network classifier
- Evaluating model performance
- Making predictions on new data

### 3. IT Incident Root Cause Analysis (Module 06)
This notebook shows how to apply deep learning to automate the analysis of IT incident root causes.

Key concepts:
- Feature engineering from system metrics
- Building a multi-class classification model
- Training and evaluating the model
- Using the model for incident diagnosis

## 📈 Performance

All models achieve the following performance metrics:

- Iris Classification: ~94% accuracy
- Spam Detection: ~94% accuracy
- Root Cause Analysis: ~76% accuracy

## 📝 Disclaimer

This repository contains my work and notes from the LinkedIn Learning course "Getting Started with AI and Machine Learning." The original course materials and concepts are the property of LinkedIn Learning and their respective instructors. This repository is meant for personal reference and educational purposes only.

## 📜 License

This project is shared under the MIT License. However, please respect LinkedIn Learning's terms of service regarding their course materials.

## 🔗 LinkedIn Learning Course

For those interested in taking the full course, you can find the "Getting Started with AI and Machine Learning" learning path on LinkedIn Learning.

## 📞 Contact

For questions or feedback about my implementation of these exercises, please open an issue on this repository.
