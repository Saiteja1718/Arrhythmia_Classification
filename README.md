# 🫀 Arrhythmia Detection using Hilbert Vibration Decomposition and Machine Learning

This project focuses on detecting multiple types of human heart arrhythmia using advanced signal processing and machine learning techniques. The proposed model demonstrates high accuracy and robustness across multiple datasets by leveraging Hilbert Vibration Decomposition (HVD), CORAL domain adaptation, and various classifiers.

## 🚀 Project Highlights

- ✅ Achieved **98% accuracy** using Random Forest with CORAL on MIT-BIH and INCART databases.
- 📉 Compared multiple classifiers: Random Forest, Gradient Boosting, XGBoost, K-Nearest Neighbors.
- 🌐 Domain adaptation handled using **CORAL (Correlation Alignment)** to improve generalization across datasets.
- 🧠 Signal decomposition with **Hilbert Vibration Decomposition (HVD)** for effective feature extraction from ECG signals.

---

## 📁 Dataset Information

### 1. MIT-BIH Arrhythmia Database
- Source: PhysioNet
- Records: 48 half-hour ECG recordings
- Annotations: Normal, PVC, APB, LBBB, RBBB, etc.

### 2. INCART Database
- Source: PhysioNet
- 75 annotated recordings of 30 minutes
- Real-world variability from clinical ECGs

---

## 🧠 Model Architecture

1. **Preprocessing:**
   - ECG signal denoising
   - R-peak detection
   - Segmentation of heartbeats

2. **Feature Extraction:**
   - Apply **Hilbert Vibration Decomposition (HVD)**
   - Extract statistical and morphological features

3. **Domain Adaptation:**
   - Use **CORAL** to align feature distributions across domains

4. **Classification:**
   - Train classifiers (Random Forest, XGBoost, etc.)
   - Evaluate using accuracy, precision, recall, and F1-score

---

## 🧪 Results

| Classifier         | Accuracy (%) |
|--------------------|--------------|
| Random Forest (CORAL) | **98.0**       |
| Gradient Boosting  | 82.0         |
| XGBoost            | 82.0         |
| K-Nearest Neighbors | 86.0        |

---

## 🛠 Technologies Used

- Python
- NumPy, Pandas
- SciPy, Scikit-learn
- Matplotlib, Seaborn
- PyECG (for preprocessing)
- Custom HVD implementation
- CORAL for domain adaptation

---

## 📊 Evaluation Metrics

- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- Cross-validation

---

## 🧩 Folder Structure

