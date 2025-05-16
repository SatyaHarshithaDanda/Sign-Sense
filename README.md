# 🚦 Traffic Sign Classification

This project focuses on classifying traffic signs using deep learning techniques. It demonstrates how computer vision and convolutional neural networks (CNNs) can be applied to real-world problems such as autonomous driving and road safety systems.

## 🎯 Objective

- Train a model to accurately classify traffic signs into their respective categories.
- Utilize deep learning and image processing techniques to build an end-to-end classification system.
- Evaluate the model's performance and interpret its predictions.

## 🧰 Tools & Technologies

- **Python**
- **TensorFlow / Keras** – Deep learning framework
- **OpenCV** – Image preprocessing
- **Matplotlib / Seaborn** – Visualization
- **NumPy / Pandas** – Data handling
- **Jupyter Notebook** – Development and testing

## 🗂️ Dataset

The project uses a traffic sign dataset containing images of various road signs labeled by class. Each image is:
- Labeled with the sign category (e.g., speed limit, yield, stop).
- Preprocessed and resized for uniform input to the neural network.

> Dataset source: [German Traffic Sign Recognition Benchmark (GTSRB)](http://benchmark.ini.rub.de/?section=gtsrb&subsection=news)

## 📊 Project Workflow

1. **Data Loading & Preprocessing**
   - Resize, normalize, and augment images.
2. **Exploratory Data Analysis**
   - Visualize class distributions and sample images.
3. **Model Building**
   - Build a CNN using Keras for classification.
4. **Training & Validation**
   - Train the model and evaluate using accuracy and loss curves.
5. **Testing & Evaluation**
   - Test on unseen data and display classification results.

## ✅ Results

- Achieved high classification accuracy on validation and test sets.
- Successfully distinguishes among dozens of traffic sign classes.
- Robust model capable of generalizing to real-world traffic images.

## 🧠 Skills Demonstrated

- Image classification with CNNs
- Data preprocessing and augmentation
- Model evaluation and tuning
- Practical application of deep learning

## ▶️ How to Run

1. Clone the repository or download the notebook.
2. Install the dependencies:
   ```bash
   pip install tensorflow keras numpy matplotlib opencv-python
   ```
3. Run Traffic_Sign_Classification.ipynb step-by-step in Jupyter Notebook.
