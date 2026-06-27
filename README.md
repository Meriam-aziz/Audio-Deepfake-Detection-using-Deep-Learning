# 🎙️ Audio Deepfake Detection using Deep Learning

## 📌 Overview

This project presents a Deep Learning approach for detecting fake audio using the **SceneFake** dataset. The system analyzes audio data, performs preprocessing, and classifies audio samples as **Real** or **Fake**, helping address challenges in digital forensics and audio authentication.

---

## 🎯 Objective

The main objective of this project is to develop a deep learning model capable of distinguishing between genuine and manipulated audio recordings for forensic and cybersecurity applications.

---

## 📊 Dataset

The project uses the **SceneFake** dataset, which contains audio samples labeled as:

- **Real Audio**
- **Fake Audio**

The dataset is divided into training, validation, and testing sets to evaluate the model's performance.

---

## ⚙️ Workflow

1. Load the audio dataset.
2. Perform data preprocessing.
3. Explore the dataset using visualizations.
4. Extract audio features.
5. Train the Deep Learning model.
6. Evaluate model performance.
7. Classify audio samples as Real or Fake.

---

## 🤖 Model

Deep Learning model for binary audio classification using the **SceneFake** dataset.

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score

---

## 🖼️ Results

### Number of Real and Fake Audios per Split and Version

![Real vs Fake Split](images/real_fake_split_version.png)

---

### Number of Real and Fake Audios per Split in SceneFake Dataset

![SceneFake Split Distribution](images/scenefake_split_distribution.png)

---

### Label Distribution in SceneFake Dataset

![Label Distribution](images/label_distribution.png)

The exploratory analysis provides a clear understanding of the dataset distribution and class balance before training the deep learning model.

---

## 🛠️ Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Librosa
- Scikit-learn
- Jupyter Notebook

---

## ▶️ How to Run

```bash
git clone https://github.com/Meriam-aziz/Audio-Deepfake-Detection-using-Deep-Learning.git

cd Audio-Deepfake-Detection-using-Deep-Learning

pip install -r requirements.txt

jupyter notebook "Forensic Science Project.ipynb"
```

---

## 📁 Project Structure

```text
Audio-Deepfake-Detection-using-Deep-Learning/
│
├── images/
│   ├── real_fake_split_version.png
│   ├── scenefake_split_distribution.png
│   └── label_distribution.png
│
├── Forensic Science Project.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Features

- Audio preprocessing and analysis.
- Exploratory Data Analysis (EDA).
- Deep Learning-based audio classification.
- Binary classification of Real vs Fake audio.
- Visual analysis of dataset distribution.

---

## 👩‍💻 Author

**Meriam Aziz**

---

## ⭐ Future Improvements

- Improve model accuracy using advanced neural network architectures.
- Support real-time fake audio detection.
- Deploy the model as a web application using Streamlit or Flask.
- Expand the system to detect multiple types of manipulated audio.
