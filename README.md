# 🩻 Chest X-Ray Classification with Deep Learning and Apache Spark

This project builds a scalable pipeline for classifying chest X-ray images into four diagnostic categories: **Normal**, **Pneumonia**, **Tuberculosis**, and **COVID-19**. It combines big data processing 
(Apache Spark) with deep learning (TensorFlow/Keras) to support clinical diagnostic workflows with explainable AI.

---

## 🧠 Project Highlights

- 🔍 **Multiclass Classification** of X-ray images (4 classes).
- ⚙️ **Big Data Preprocessing** using PySpark (7,000+ images).
- 🧪 **Fine-tuned CNNs:** VGG19, ResNet101, EfficientNetB2.
- 🧼 **Balanced Dataset** via oversampling and augmentation.
- 📊 **98.4% Test Accuracy** achieved with VGG19.
- 🌈 **Grad-CAM Visualizations** for explainability.
- 🐳 **Dockerized Deployment** (Optional).
- 🚀 **CI/CD Integration** (Optional via GitHub Actions).
- 🧪 **REST API Inference** (Optional with Flask).

---

## 📁 Project Structure

```bash
├── notebooks/                 # Jupyter notebooks and PySpark scripts
├── README.md                  # You're here!
└── report/                    # Final evaluation PDF and charts
