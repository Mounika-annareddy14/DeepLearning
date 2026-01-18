# Deep Learning Practice – ANN & CNN

This repository contains my **hands-on practice and mini-projects** on **Artificial Neural Networks (ANN)**, **Convolutional Neural Networks (CNN)**, and **Transfer Learning** using **TensorFlow & Keras**. These notebooks/scripts were created as part of my learning.

---

## 📌 Topics Covered

### 1️⃣ Binary Classification using ANN (Breast Cancer Dataset)

* Dataset: `sklearn.datasets.load_breast_cancer`
* Problem Type: Binary Classification (Malignant vs Benign)
* Model Type: Fully Connected ANN
* Loss Function: `binary_crossentropy`
* Activation Functions: `ReLU`, `Sigmoid`
* Optimizer: `Adam`

**Key Concepts Practiced:**

* Data loading using sklearn
* Feature–target separation
* Train-test split
* ANN architecture design
* Model compilation & training
* Accuracy & loss visualization
* Threshold-based prediction
* Confusion matrix & accuracy score

---

### 2️⃣ Multi-Class Classification using ANN (Iris Dataset)

* Dataset: `sklearn.datasets.load_iris`
* Problem Type: Multi-class classification (3 classes)
* Output Activation: `Softmax`
* Loss Function: `categorical_crossentropy`

**Additional Concepts:**

* One-hot encoding using `to_categorical`
* Multi-class probability prediction
* `argmax` for class selection

---

### 3️⃣ Binary CNN (Day vs Night Image Classification)

* Data Source: Folder-based image dataset
* Model Type: Custom CNN
* Input Size: `(256 × 256 × 3)`

**CNN Architecture:**

* Conv2D + MaxPooling layers
* Flatten layer
* Dense ANN layers
* Sigmoid output layer

**Image Processing Concepts:**

* ImageDataGenerator
* Data augmentation (zoom, flip, shear)
* Rescaling pixel values
* Folder-based dataset handling

---

### 4️⃣ Multi-Class CNN (Butterfly Species Classification)

* Problem Type: Multi-class image classification
* Number of Classes: 74
* Output Activation: `Softmax`

**Advanced Concepts Used:**

* Training, validation & testing splits
* Callbacks:

  * ModelCheckpoint
  * EarlyStopping
  * ReduceLROnPlateau
* Class index mapping
* Prediction on external images

---

### 5️⃣ Transfer Learning – VGG16

* Pretrained Model: `VGG16 (ImageNet weights)`
* Task: Binary Image Classification

**Transfer Learning Steps:**

* Load pretrained model without top layers
* Freeze base layers
* Add custom classifier
* Train on custom dataset

---

## 📊 Model Evaluation

* Accuracy Score
* Confusion Matrix
* Training vs Validation plots
* Manual image testing using OpenCV

---

## 🛠 Libraries Used

```text
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
TensorFlow / Keras
OpenCV
```

---


## 🎯 Learning Outcomes

* Clear understanding of ANN vs CNN
* Binary vs Multi-class classification
* Custom CNN design
* Image preprocessing & augmentation
* Transfer learning fundamentals
* Model evaluation techniques

---

* Use **Sigmoid + Binary Crossentropy** for binary classification
* Use **Softmax + Categorical Crossentropy** for multi-class problems
* ANN works well for tabular data
* CNN is best suited for image data
* Transfer learning reduces training time and improves accuracy

---

## ✍️ Author

**Mounika Reddy**
Aspiring DataScientist

---

⭐ *This repository is created for learning, revision, and interview preparation.*
