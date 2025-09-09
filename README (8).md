# Traffic Sign Recognition 🚦

A deep learning project for classifying traffic signs with **99% accuracy** using Convolutional Neural Networks (CNNs). This project demonstrates how computer vision can be applied in real-world scenarios like **autonomous driving** and **road safety systems**.

---

## 📌 Features
- Preprocessing and visualization of traffic sign dataset.
- One-hot encoding of class labels.
- CNN architecture for traffic sign recognition.
- Data augmentation for better generalization.
- Training with validation split.
- Evaluation with confusion matrix & classification report.
- Achieved **99% accuracy** on test data.

---

## 📂 Dataset
The project uses the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset, which contains images of traffic signs belonging to multiple classes.

- **Classes**: 43 traffic sign categories
- **Source**: [GTSRB Dataset](https://benchmark.ini.rub.de/gtsrb_news.html)

---

## ⚙️ Installation
Clone the repository and install the required dependencies:

```bash
# Clone the repository
git clone https://github.com/yourusername/traffic-sign-recognition.git
cd traffic-sign-recognition

# Install dependencies
pip install -r requirements.txt
```

---

## ▶️ Usage
Run the Jupyter notebook to train and evaluate the model:

```bash
jupyter notebook traffic-sign-recognition.ipynb
```

Alternatively, run the Python script (if exported):

```bash
python train.py
```

---

## 📊 Results
- **Accuracy**: ~99%
- **Evaluation**: Confusion matrix and classification report provided.
- **Predictions**: Correctly classifies unseen test traffic sign images.

Example output:
- ✅ High accuracy on training and validation sets.
- ✅ Robust performance on test data.

---

## 🧰 Technologies Used
- **Python 3**
- **TensorFlow / Keras**
- **NumPy, Pandas**
- **Matplotlib, Seaborn**
- **Scikit-learn**

---

## 📌 Future Improvements
- Deploy model as a web or mobile app.
- Implement real-time recognition with OpenCV.
- Optimize CNN for edge devices.

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repo, open an issue, or submit a pull request.

---

## 📜 License
This project is licensed under the MIT License.

---

## 👤 Author
Developed by **[Your Name](https://github.com/yourusername)**
