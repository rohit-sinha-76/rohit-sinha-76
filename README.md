# Rohit Sinha

**Biomedical AI · Deep Learning for Healthcare · Signal Processing**

Third-year B.Tech student (Information Technology, GEC Jagdalpur, CSVTU) with a focused research interest in physiological signal processing and clinical-grade deep learning systems. Working independently on problems at the intersection of machine learning and non-invasive medical diagnostics.

Open to research internships at IITs, NITs, and IIITs in ML/healthcare AI.

---

## Research Focus

Cuffless, continuous vital sign estimation from PPG signals using deep learning. Primary interest: building models that meet clinical validation standards (AAMI/BHS) — not just achieving low benchmark error, but validating under subject-independent conditions against real ICU datasets.

Secondary interests: LLMs, generative AI, and multimodal systems.

---

## Selected Projects

### Cuffless Blood Pressure Estimation from PPG Signals
`Python` `TensorFlow` `CNN-BiLSTM` `Temporal Attention` `CWT`

Hybrid CNN-BiLSTM model with temporal attention for non-invasive blood pressure estimation. Trained and validated on **MIMIC-III Waveform Database** (40,000 segments, 31 subjects) using subject-independent cross-validation.

Preprocessing pipeline converts raw PPG into 3-channel CWT scalograms (PPG, VPG, APG) to preserve morphological features across frequency bands.

| Metric | DBP | SBP |
|--------|-----|-----|
| MAE | 3.42 mmHg | 6.84 mmHg |
| R² | 0.81 | 0.74 |
| BHS Grade | **A** | **B** |
| AAMI Standard | Pass | Pass |

[View Repository](https://github.com/rohit-sinha-76/bp-estimation-from-ppg)

---

### Heart Rate Estimation via 1D-CNN on PPG Signals
`Python` `TensorFlow` `Flask` `Docker` `Pytest`

1D-CNN trained on the **BIDMC ICU Dataset** (53 subjects, 8-second overlapping windows) with augmentation strategies including Gaussian noise injection, amplitude scaling, and temporal shifting. Achieved ~3.5 BPM MAE on held-out patients.

Deployed as a Dockerized Flask REST API with Pytest unit testing suite.

[View Repository](https://github.com/rohit-sinha-76/ppg-heart-rate-app)

---

### Credit Card Fraud Detection Pipeline
`Python` `XGBoost` `FastAPI` `SMOTE` `SHAP` `Docker` `Streamlit`

End-to-end fraud detection system trained on 2 years of transaction data. Key design choices: chronological train/test split to prevent leakage, hybrid SMOTE resampling for class imbalance, and precision-recall threshold tuning (optimal threshold: 0.1659).

- Fraud Recall: **90.22%** — AUC-ROC: **~95%**
- SHAP-based feature interpretability
- Deployed via Docker Compose with FastAPI backend and Streamlit UI

[View Repository](https://github.com/rohit-sinha-76/Credit_Card_Fraud_Detection)

---

### Neural Network from Scratch — Breast Cancer Classification
`Python` `NumPy` `Scikit-learn`

2-layer fully connected network built without any ML library — only NumPy. Implements matrix calculus backpropagation, ReLU/Sigmoid activations, cross-entropy loss, and batch gradient descent from first principles.

- Accuracy: **93.86%** — Malignant Recall: **88.37%**
- Dataset: Wisconsin Breast Cancer Dataset

[View Repository](https://github.com/rohit-sinha-76/breast-cancer-nn)

---

## Technical Skills

**ML / DL:** TensorFlow, Keras, Scikit-learn, XGBoost, NumPy, SciPy, Pandas  
**Signal Processing:** CWT scalograms, PPG morphology, subject-independent validation  
**Deployment:** Docker, FastAPI, Flask, Pytest  
**LLM / GenAI:** Hugging Face Transformers, Gemini API, RAG pipelines, Prompt Engineering  
**Languages:** Python, C, Java, JavaScript  
**Other:** Git, SQL, 100+ LeetCode problems solved

---

## Education & Certifications

**B.Tech — Information Technology**  
Government Engineering College Jagdalpur, CSVTU · Expected 2027

**Deep Learning Specialization** — deeplearning.ai / Coursera (Andrew Ng, 2024)  
5 courses covering CNNs, Sequence Models, Attention Mechanisms, YOLO, Hyperparameter Tuning

**Vocational Training — Python, Data Science, AI/ML/DL**  
IIIT Naya Raipur, 2024

---

## Contact

[LinkedIn](https://www.linkedin.com/in/XXXXXXXXXXXXX) · [GitHub](https://github.com/rohit-sinha-76)
