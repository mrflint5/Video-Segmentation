
# 🎬 Video Segmentation: A Comparative Study of Classical, Machine Learning, and Deep Learning Techniques

Welcome to a comprehensive research project on **Video Segmentation**, where we explore, analyze, and compare various segmentation techniques including classical algorithms, machine learning models, and state-of-the-art deep learning frameworks. This repository contains both a detailed research report and a working notebook implementation.

📄 **[Read the Full Report](./Report%20Analysis.pdf)** | 💻 **[Access the Notebook](./Working.ipynb)**

---

## 📌 Abstract

This study evaluates the performance of classical, machine learning, and deep learning-based video segmentation methods. While traditional techniques like thresholding and edge detection are computationally efficient, they lack robustness in dynamic environments. Machine learning approaches improve adaptability, and deep learning methods — especially Transformers — deliver cutting-edge accuracy at a computational cost.

**Key Contributions:**
- ✅ Comparative analysis using IoU, F1-score, and processing time
- 🧠 Evaluation of CNNs, FCNs, RNNs, and Transformer architectures
- 💡 Recommendations for hybrid models and future optimization

---

## 🗂 Table of Contents

- Abstract  
- Techniques Implemented  
- Comparative Analysis  
- Experimental Results  
- Repository Structure  
- How to Run  
- Screenshots  
- Demo Video  
- Future Scope  
- Acknowledgments  
- Author

---

## 🧠 Techniques Implemented

### 🔹 Classical Techniques
- Thresholding
- Edge Detection
- Optical Flow

### 🔸 Machine Learning Algorithms
- K-Means Clustering
- Gaussian Mixture Models (GMM)
- Support Vector Machines (SVM)

### 🔺 Deep Learning Architectures
- Convolutional Neural Networks (CNNs)
- Recurrent Neural Networks (RNNs)
- Fully Convolutional Networks (FCNs)
- Transformers (ViT, Swin Transformer)

---

## 📊 Comparative Summary

| Technique       | Accuracy | Speed  | Occlusion Handling | Real-Time Suitability |
|----------------|----------|--------|---------------------|------------------------|
| Thresholding    | Low      | Fast   | Poor                | Good                   |
| Edge Detection  | Medium   | Fast   | Moderate            | Good                   |
| Optical Flow    | Medium   | Medium | Good                | Moderate               |
| K-Means         | Medium   | Medium | Moderate            | Moderate               |
| GMM             | High     | Medium | Good                | Moderate               |
| SVM             | High     | Slow   | Moderate            | Poor                   |
| CNNs            | Very High| Medium | Excellent           | Moderate               |
| FCNs            | Very High| High   | Excellent           | Moderate               |
| Transformers    | Highest  | Slow   | Outstanding         | Poor                   |

---

## 📈 Experimental Results

| Method        | IoU Score | F1-Score | Processing Time (ms/frame) |
|---------------|-----------|----------|-----------------------------|
| Thresholding  | 40%       | 0.55     | 2 ms                        |
| K-Means       | 70%       | 0.75     | 15 ms                       |
| GMM           | 78%       | 0.80     | 20 ms                       |
| CNNs          | 90%       | 0.92     | 50 ms                       |
| FCNs          | 94%       | 0.96     | 80 ms                       |
| Transformers  | 96%       | 0.98     | 120 ms                      |

---

## 📂 Repository Contents

- `Report Analysis.pdf` – 📘 Complete research documentation  
- `Working.ipynb` – 🧪 Jupyter notebook with code implementation  
- 📊 Visual analysis and tabular results included

---

## 🚀 How to Run the Notebook

### 🧰 Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required libraries: `opencv-python`, `numpy`, `matplotlib`, `scikit-learn`, `tensorflow/torch`

```bash
pip install opencv-python numpy matplotlib scikit-learn tensorflow
```

### ▶️ Steps to Execute
1. Clone this repository.
2. Open `Working.ipynb` using Jupyter Notebook.
3. Execute each cell to view implementation and outputs.
4. Evaluate results and compare performance metrics.

---

## 🖼️ Output Screenshots

Visual outputs from various segmentation methods:

📁 [View Screenshot Gallery](https://drive.google.com/drive/folders/1n9Z5go1hfpoSdl3vcxJHDxdBxDnMiJ_p?usp=sharing)

---

## 🎥 Demonstration Video

🎬 Watch a quick demonstration of the project's results and methodology:

🔗 [Click to View on Google Drive](https://drive.google.com/file/d/1Pv0Qmih6-KpsFFEIqTHhhuRN-mi1XDAs/view?usp=sharing)

---

## 🌱 Future Scope

- Optimize deep learning models for real-time performance
- Design hybrid models combining classical & DL techniques
- Improve efficiency with hardware acceleration (GPU/TPU)
- Extend applications to AR/VR, surveillance & healthcare

---

## 🙏 Acknowledgments

Thanks to the open-source community and researchers in the field of computer vision for their valuable contributions and tools that made this project possible.

---

## 👤 Author

**Sameer Malik**  
🎓 BCA Student, Amity University Lucknow  
🔗 [LinkedIn](https://linkedin.com/in/sameermalik5) | 🌐 [GitHub](https://github.com/mrflint5)

---

⭐ *If you find this repository helpful, don't forget to give it a star!*
