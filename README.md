

# 🐾 Animal Image Classification using MobileNet (TensorFlow)

This project classifies animal images into 15 categories using **transfer learning** with **MobileNet** and **TensorFlow**. It demonstrates how to leverage pre-trained models for accurate and efficient image classification.

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

- ✅ **Transfer Learning** using `MobileNetV2` (pre-trained on ImageNet)
- ✅ TensorFlow / Keras API for easy integration
- ✅ Global Average Pooling + Dense layer for classification
- ✅ Softmax activation for multi-class output (15 classes)
- ✅ Data augmentation with `ImageDataGenerator`

---
🧪 Results
✅ Fast training with transfer learning

✅ Lightweight model, suitable for mobile/edge deployment

🔍 Confusion matrix, accuracy graph, and sample predictions included in results/

🎯 Test Accuracy: ~ZZ% (update after training)

🔧 Tech Stack
🧠 TensorFlow / Keras

📊 NumPy, Matplotlib

🗂️ ImageDataGenerator for loading + augmentation

💾 MobileNetV2 from TensorFlow Hub or Keras Applications

📈 Future Improvements
 Fine-tune top MobileNet layers for better accuracy

 Convert model to TFLite for mobile deployment

 Build a simple web UI with Flask or Streamlit

 Add support for batch inference

🙋‍♀️ About Me
I’m Devika, an aspiring AI/ML Engineer passionate about real-world applications of deep learning. This project is part of my journey into transfer learning and computer vision.



## 🚀 How to Run

```bash

pip install -r requirements.txt
python train.py
python test.py --image path_to_image.jpg

