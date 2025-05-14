

# 🐾 Animal Image Classification using Deep Learning

This project focuses on classifying images of animals into their respective categories using deep learning. It uses a Convolutional Neural Network (CNN) model trained on a dataset of 15 animal classes to demonstrate image classification capabilities.


## 📊 Dataset

The dataset includes **15 different animal classes**, such as:

- Cat
- Dog
- Horse
- Elephant
- Lion
- Tiger
- Monkey
- Bear
- Deer
- Giraffe  
*(and more...)*

Images are preprocessed (resized, normalized) and augmented during training to improve model generalization.

---

## 🧠 Model Architecture

The model is built using:

- ✅ Convolutional layers with ReLU
- ✅ MaxPooling layers
- ✅ Dense layers with Dropout
- ✅ Softmax activation for multiclass output

You can replace the base model with transfer learning (e.g., ResNet, VGG) for better accuracy.

---

## 🚀 How to Run

```bash

pip install -r requirements.txt
python train.py
python test.py --image path_to_image.jpg

