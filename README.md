# Real vs. Fake Image Classifier 🧠📸

A deep learning classifier built to distinguish between **real images** and **AI-generated fake images** using convolutional neural networks (CNNs).  
This project was developed as part of a **private Kaggle competition**.

---

## 🧩 Project Structure

```
├── real-vs-fake-image-classifier/
│ ├── real_vs_fake.ipynb # Jupyter Notebook for training, validation, and evaluation
│ ├── dataset/ # Folder with dataset access info only
│ │ └── README.md
│ └── README.md 
```

---

## 🧠 Model Overview

- **Architecture:** Convolutional Neural Network (CNN) using PyTorch
- **Input:** 128x128 greyscale images
- **Output:** Binary classification — `real` vs. `fake`
- **Performance:** Achieved **99% validation accuracy**

---

## 🔧 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/EthanTobey/real-vs-fake-image-classifier.git
   cd RealVsFakeClassifier
   ```

2. Set up a Python environment (Python 3.8+ recommended):
   ```bash
   pip install -r requirements.txt
   ```

3. Download and place the dataset into dataset/ (see below for access info).

4. Run the training notebook
    ```bash
    jupyter notebook real_vs_fake.ipynb
    ```

---

## 📂 Dataset

This project used a **private Kaggle competition dataset** containing labeled images of real and AI-generated human faces.

*Due to competition rules, the dataset cannot be shared publicly and is not included in this repository.*  
Please contact the author if access is needed for academic or demonstration purposes.

See `dataset/README.md` for more details.

---

## 📈 Results

- **Validation Accuracy:** 99%
- **Confusion Matrix:** Demonstrates strong performance on both classes  

---

## 🔍 Key Concepts

- Deep CNN model design
- Image preprocessing
- Binary classification
- Overfitting mitigation with dropout and data augmentation
- Model evaluation via precision, recall, and F1 score

---

## 🧑‍💻 Author

**Ethan Tobey** — [GitHub](https://github.com/yourusername)  
Case Western Reserve University  
B.S. in Computer Science, Minor in Computer Gaming


