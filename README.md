
# 🧠 ASD Prediction Using Deep Learning

A clean and compact machine learning project using a **deep autoencoder** model to classify whether an individual is on the autism spectrum, based on standard diagnostic scores.

---

## 🚀 Overview

This notebook loads diagnostic screening data, preprocesses it, and trains a neural network for ASD classification using Keras. It handles data preparation, scaling, and builds an autoencoder model to learn compact representations for classification.

---

## 📑 Table of Contents

* [Features](#features)
* [Dataset](#dataset)
* [Installation](#installation)
* [Usage](#usage)
* [Model Architecture](#model-architecture)
* [License](#license)
* [Contact](#contact)

---

## ✨ Features

* 📊 Binary classification for autism spectrum detection
* 🔍 Uses 9 diagnostic screening scores (A1–A9)
* 🔄 Preprocessing with `StandardScaler`
* 🤖 Deep learning with an **autoencoder** architecture using Keras
* 🧪 Scalable for both training and test prediction

---

## 🗄️ Dataset

Two CSV files are used:

* `train.csv` – contains labeled training data with features A1–A9 and the `Class/ASD` label
* `test.csv` – similar format, but without the label for inference

**Features used:**

| Feature             | Description                        |
| ------------------- | ---------------------------------- |
| A1\_Score–A9\_Score | Binary diagnostic inputs (0/1)     |
| Class/ASD           | Target label (0 = No ASD, 1 = ASD) |

---

## ⚙️ Installation

```bash
# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install required packages
pip install pandas scikit-learn keras tensorflow
```

---

## ▶️ Usage

1. Place `train.csv` and `test.csv` in your working directory.
2. Run the notebook `Asd.ipynb` in Jupyter or Colab.
3. The model will:

   * Preprocess the features
   * Train the autoencoder model
   * Prepare the test set for prediction

---

## 🧠 Model Architecture

* **Encoder**: 64 → 32 units (ReLU)
* **Decoder**: 32 → 64 → output layer (Sigmoid)
* Optimized for binary feature reconstruction to aid classification.


---

## 📬 Contact

Created by **\[Your Name]**
📧 Email: [SAMYUKTHASASIKUMAR0061@GMAIL.COM](mailto:SAMYUKTHASASIKUMAR0061@GMAIL.COM)
🔗 GitHub: [Samyukthacs07](https://github.com/Samyukthacs07)


