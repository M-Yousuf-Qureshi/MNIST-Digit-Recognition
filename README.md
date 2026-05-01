readme = """# 🔢 MNIST Digit Recognition using CNN

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Accuracy](https://img.shields.io/badge/Test%20Accuracy-99.21%25-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)

A deep learning project that recognizes handwritten digits (0–9) using 
a CNN built with TensorFlow and Keras. Achieved 99.21% test accuracy.

## 📊 Dataset
- 70,000 grayscale images (60,000 train / 10,000 test)
- Image size: 28×28 pixels
- 10 classes (Digits 0–9)

## 🧠 Model Architecture
- Conv2D → MaxPooling → Conv2D → MaxPooling → Dropout → Dense → Output
- Total Parameters: 225,034

## 📈 Results
| Metric | Value |
|--------|-------|
| Test Accuracy | 99.21% |
| Test Loss | 0.0241 |
| F1-Score | 0.992 |
| Misclassifications | 79 / 10,000 |

## 🚀 How to Run
```bash
git clone https://github.com/yourusername/MNIST-Digit-Recognition.git
pip install -r requirements.txt
jupyter notebook mnist_digit_recognition.ipynb
```

## 🛠️ Technologies
Python | TensorFlow | Keras | NumPy | Matplotlib | Scikit-learn

## 👤 Author
**[Your Name]** — AI/ML Intern
"""

with open("MNIST-Digit-Recognition/README.md", "w") as f:
    f.write(readme)

print("README.md created!")
