# 😷 Face Mask Detection

TensorFlow **Object Detection API**–based project to classify whether a person is **wearing a face mask or not** from images or a live webcam feed.

<p align="left">
  <a href="https://www.python.org/downloads/release/python-370/"><img src="https://img.shields.io/badge/python-3.7%20|%203.8-blue.svg" alt="Python"></a>
  <img src="https://img.shields.io/badge/TensorFlow-1.15-orange.svg" alt="TensorFlow 1.15">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-green.svg" alt="MIT License"></a>
</p>

---

## 🚀 Features

- **Real‑time detection** from your webcam  
- **Simple dataset generator** (`data_gen.py`)  
- **End‑to‑end Jupyter notebook** (`face_mask_detection.ipynb`) for training & inference  
- **Sample prediction results** included


---

## ✅ Requirements

- **Python 3.7 / 3.8**
- (Recommended) **Anaconda**
- **TensorFlow 1.x** (tested on **1.15**)
- **OpenCV**
- **NumPy, Matplotlib, Jupyter**
- **TensorFlow Models repository** (Object Detection API)

### Example environment setup

```bash
conda create -n maskdetect python=3.7 -y
conda activate maskdetect

pip install tensorflow==1.15 opencv-python numpy matplotlib jupyter
