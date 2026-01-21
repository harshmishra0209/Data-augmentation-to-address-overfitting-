
# Data Augmentation to Address Overfitting

This project demonstrates how **data augmentation** can be used to reduce **overfitting** in image classification models built with **TensorFlow / Keras**. The notebook shows a complete workflow starting from dataset loading to model training and evaluation.

---

## 📌 Project Overview

Overfitting occurs when a model performs well on training data but poorly on unseen data. To mitigate this, we apply **data augmentation techniques** such as rotation, flipping, zooming, and resizing, which help the model generalize better by learning from varied versions of the same images.

This project uses an image dataset (e.g., flower photos) and trains a CNN model with and without data augmentation to observe performance differences.

---

## 🛠️ Technologies Used

* Python 3.x
* TensorFlow / Keras
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 📂 Project Structure

```
Data-augmentation-to-address-overfitting/
│
├── Data augmentation to address overfitting.ipynb
├── README.md
└── dataset/
    └── image folders (class-wise)
```

---

## ⚙️ Key Features

* Image dataset loading using `tf.keras.utils.image_dataset_from_directory`
* Data preprocessing and normalization
* Data augmentation using Keras preprocessing layers
* CNN model creation
* Training and validation comparison
* Overfitting reduction analysis

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your-repo-name
   ```

3. Install required dependencies:

   ```bash
   pip install tensorflow matplotlib numpy
   ```

4. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Run `Data augmentation to address overfitting.ipynb` cell by cell.

---

## 📊 Results

* Reduced gap between training and validation accuracy
* Improved model generalization
* Better validation performance compared to the non-augmented model

---

## 📈 Future Improvements

* Try advanced augmentation (CutMix, MixUp)
* Use transfer learning (ResNet, MobileNet, EfficientNet)
* Hyperparameter tuning
* Model deployment


