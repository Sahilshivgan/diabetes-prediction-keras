# 🧠 Diabetes Prediction using Keras

A machine learning project that predicts the onset of diabetes using a pre-trained Keras model and the Pima Indians Diabetes Dataset. This project demonstrates how to load model architecture and weights from files and perform predictions on real-world healthcare data.

---

## 📁 Project Structure

```
diabetes-prediction-keras/
├── test.py                    # Script to load model and make predictions
├── model.json                 # Saved model architecture
├── model.weights.h5           # Trained model weights
├── pima-indians-diabetes.csv  # Input dataset
├── README.md                  # Project documentation
└── .gitignore                 # Ignored files configuration
```

---

## 🚀 How to Run

### 📦 Requirements
- Python 3.x
- Keras
- TensorFlow
- NumPy
- Pandas

### 🔧 Install Dependencies
```bash
pip install tensorflow keras numpy pandas
```

### ▶️ Run the Script
```bash
python test.py
```

---

## 📊 Sample Output

```
Loaded model from disk
[6.0, 148.0, 72.0, 35.0, 0.0, 33.6, 0.627, 50.0] => 1 (expected 1)
[1.0, 85.0, 66.0, 29.0, 0.0, 26.6, 0.351, 31.0] => 0 (expected 0)
[8.0, 183.0, 64.0, 0.0, 0.0, 23.3, 0.672, 32.0] => 1 (expected 1)
[1.0, 89.0, 66.0, 23.0, 94.0, 28.1, 0.167, 21.0] => 0 (expected 0)
[0.0, 137.0, 40.0, 35.0, 168.0, 43.1, 2.288, 33.0] => 1 (expected 1)
```

---

## 📌 Dataset

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/pima+indians+diabetes)
- **Description:** Contains medical data for Pima Indian women, used to predict diabetes onset.

---

## 🛠️ Model Details

- **Architecture:** Feed-forward neural network
- **Layers:**
  - Dense (12 units, ReLU)
  - Dense (8 units, ReLU)
  - Dense (1 unit, Sigmoid)
- **Loss Function:** Binary Crossentropy
- **Optimizer:** Adam
- **Epochs:** 150

---

## 🙋‍♂️ Author

**Sahil Sudhir Shivgan**  
🎓 B.E. Computer Science (AI & ML)  
🔗 [LinkedIn](https://www.linkedin.com/in/sahil-shivgan)  
💻 [GitHub](https://github.com/Sahilshivgan)

---

## 🌟 Support

If you found this helpful, feel free to ⭐ star the repo and share it!
