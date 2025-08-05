# Quran Reciter Identification using PyTorch

## 📌 Project Overview
This project focuses on **identifying Quran reciters** from their audio recordings using **deep learning techniques**.  
Unlike typical speech recognition, this is a **speaker identification** task applied to Quranic recitations, where the goal is to classify **who** is reciting.

---

## 🔍 Approach

### 1️⃣ Data Preprocessing
- Converted raw Quran recitation audio files into **spectrograms** for feature extraction.
- Normalized and prepared data for training/testing.

### 2️⃣ Model Development
- Implemented a **Convolutional Neural Network (CNN)** using **PyTorch**.
- Optimized architecture and hyperparameters to handle variations in recitation styles and recording conditions.

### 3️⃣ Training & Evaluation
- Trained the CNN on labeled reciter data.
- Evaluated performance using:
  - Accuracy
  - Confusion Matrix
  - Loss Curves

---

## 💡 Key Insights
- **Speaker recognition** in Quranic recitations is a complex classification problem due to stylistic variations.
- Deep learning models (especially CNNs) can effectively learn **speaker-specific acoustic patterns** from spectrograms.

---

## 🚀 Results
- The model achieved **promising accuracy** in identifying reciters.
- Visualizations such as **confusion matrices** and **loss/accuracy curves** were generated to analyze performance.

---

## 🛠️ Tech Stack
- **Python**  
- **PyTorch**  
- **Librosa** (for audio processing)  
- **Matplotlib / Seaborn** (for visualization)  
- **NumPy / Pandas**

---

## 📜 Conclusion
This project showcases how **deep learning** can successfully tackle **speaker recognition** problems in a culturally meaningful context.  
It demonstrates the potential of AI in **audio analysis** and **heritage preservation**.

---

## 🤝 Contributing
Pull requests and suggestions are welcome!

## 👤 Author
**Yassine Sadiqi**  
*Data Scientist | AI Enthusiast*  

🔗 [LinkedIn](https://www.linkedin.com/in/ine-sadiki-2bb5482yass36)  

---
