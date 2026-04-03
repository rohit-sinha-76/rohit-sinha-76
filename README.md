# Rohit Sinha

Machine Learning Engineer | Deep Learning Researcher | Full-Stack Developer

---

## What I Build

Production-grade systems that bridge research and real-world deployment. I engineer end-to-end applications combining advanced machine learning, deep learning research, and full-stack development to solve complex technical problems.

---

## Technical Expertise

**Core Languages:**
Python | C | Java | JavaScript

**Deep Learning & Machine Learning:**
TensorFlow | Keras | Scikit-learn | XGBoost | Attention Mechanisms | Sequence Modeling | Signal Processing | CNN | BiLSTM | Neural Networks

**Generative AI & LLMs:**
Google Gemini API | Prompt Engineering | RAG Pipelines | Hugging Face Transformers

**Production Systems:**
Next.js | React | Flask | FastAPI | Docker | REST APIs | PostgreSQL | Supabase | Pytest

**Specialized Domains:**
Biomedical Signal Processing | Time-Series Modeling | Computer Vision | NLP | Clinical-Grade Metrics | Signal Processing (CWT, FFT)

---

## Engineering Projects

### Cuffless Blood Pressure Estimation from PPG Signals (In Progress)

**The Challenge:** Traditional blood pressure measurement requires inflatable cuffs. Building a deep learning model to predict BP from photoplethysmography (PPG) signals alone—a critical need in continuous, non-invasive clinical monitoring.

**What I Engineered:**
- Architected CNN-BiLSTM architecture with temporal attention mechanisms for time-series signal analysis
- Implemented end-to-end signal processing pipeline: 3-channel CWT scalograms (PPG, VPG, APG) from MIMIC-III dataset
- Trained on ~40K segments from 31 subjects with subject-independent validation (clinical-grade evaluation)
- currently trying better hybrid architectures that can reduce loss and make it clinical grade 
**Why It Matters:** Demonstrates mastery of medical-grade ML—biomedical signal processing, advanced deep architectures, industry-standard datasets, and realistic clinical evaluation metrics. Shows research rigor and attention to detail in a high-impact healthcare domain.

**Tech Stack:** TensorFlow | CNN-BiLSTM | CWT Signal Processing | MIMIC-III Dataset | Attention Mechanisms

---

### Heart Rate Estimation via 1D-CNN on PPG Signals (Completed, Deployed)

**The Challenge:** Extracting accurate heart rate from noisy, real-world ICU patient monitoring data in production environments.

**What I Engineered:**
- Designed and trained 1D-CNN on BIDMC ICU dataset (53 subjects, 8-second windows) with held-out patient validation
- Tripled effective training data through domain-specific augmentation: noise injection, amplitude scaling, temporal shifting
- Achieved MAE of 3.5 BPM with clinical-grade accuracy
- Deployed as Dockerized Flask REST API with automated Pytest unit testing for reproducible inference

**Why It Matters:** End-to-end production system—from model development through deployment. Demonstrates signal processing expertise, data augmentation strategy, and commitment to production-quality code with testing infrastructure.

**Tech Stack:** TensorFlow | 1D-CNN | Flask | Docker | Pytest | BIDMC Dataset

---

### ReadyCheck AI – AI-Powered Assessment Platform (Completed)

**The Challenge:** Build a tamper-proof assessment system where AI generates questions dynamically while preventing cheating through answer leakage via network inspection.

**What I Engineered:**
- Built full-stack application integrating Google Gemini API for dynamic question generation
- Implemented server-side scoring architecture to prevent client-side answer exposure
- Achieved 261 automated tests passing across 14 test files for reliability
- Supports 4 certification levels with real-time timer and honor code monitoring

**Why It Matters:** Demonstrates full-stack capability combining generative AI integration, security-conscious architecture, and comprehensive testing. Shows understanding of HCI principles and practical AI application design.

**Tech Stack:** Next.js | React | Google Gemini API | Supabase | Automated Testing

---

### Credit Card Fraud Detection Pipeline (Completed)

**The Challenge:** Build a fraud detection system that handles severe class imbalance (99:1 ratio) while maintaining high fraud detection recall for real-world deployment.

**What I Engineered:**
- Implemented hybrid SMOTE resampling to address 99:1 class imbalance
- Trained XGBoost model with threshold tuning optimized for 90.22% fraud recall
- Integrated SHAP interpretability for explainable predictions (essential for financial applications)
- Deployed via Dockerized FastAPI with production-quality pipeline

**Why It Matters:** Real-world ML problem-solving—class imbalance handling, business metric optimization (recall over accuracy), and model interpretability. Shows understanding of practical ML deployment concerns.

**Tech Stack:** XGBoost | FastAPI | SMOTE | SHAP | Docker | Python

---

### Neural Networks from Scratch (Completed)

**The Challenge:** Implement neural networks using only NumPy and matrix calculus to deeply understand backpropagation and gradient descent mechanics.

**What I Engineered:**
- Implemented two networks using pure NumPy without high-level frameworks
- Breast Cancer Classifier: 93.86% accuracy, 88.37% malignant recall (critical metric)
- MNIST Softmax Classifier: Trained on 70,000 samples with validation metrics

**Why It Matters:** Demonstrates foundational ML understanding. Building from scratch shows you understand the mathematics and theory—not just API usage. Necessary foundation for advancing to cutting-edge architectures.

**Tech Stack:** Python | NumPy | Matrix Calculus | Backpropagation

---

## Education

**Government Engineering College Jagdalpur (CSVTU)**
B.Tech Information Technology | Expected Graduation: 2027

**Relevant Coursework:** Machine Learning, Deep Learning, Neural Networks, Data Structures & Algorithms, Linear Algebra & Probability, Artificial Intelligence, Signal Processing, DBMS

---

## Certifications & Training

**Andrew Ng's Deep Learning Specialization** (4/5 Courses Completed)
- Neural Networks & Deep Learning
- Improving Deep Neural Networks: Hyperparameter Tuning, Regularization, Optimization
- Structuring Machine Learning Projects
- Convolutional Neural Networks
- (5th course: Sequence Models – in progress)

**Vocational Training – IIIT Naya Raipur** (June 2025)
- Applied ML/DL pipeline development
- Research methodology and biomedical signal processing applications

---

## Competitive Problem-Solving

**LeetCode:** 80+ DSA problems solved

Demonstrates algorithmic rigor, consistent learning discipline, and interview-ready foundation in data structures and algorithms.

---

## Key Achievements & Competencies

**Research:**
- Attention mechanisms and temporal modeling in biomedical applications
- Signal processing (CWT, FFT) for clinical-grade analysis
- Clinical metrics understanding (MAE, R², subject-independent validation)

**Engineering:**
- Production system deployment (Docker, Flask, FastAPI)
- Comprehensive testing (Pytest, 261+ passing tests)
- Full-stack architecture (Next.js frontend, Python backend)
- API integration (Gemini API, REST architectures)

**Problem-Solving:**
- Active LeetCode engagement (80+ problems)
- Real-world ML challenges (class imbalance, interpretability, deployment)
- Research-quality implementation (attention mechanisms, signal processing)

---

## Current Focus Areas

- End-to-end production ML systems combining research quality with deployment readiness
- Deep Learning research applications in biomedical and time-series domains
- Biomedical AI and healthcare technology
- Cloud services (AWS) for scalable deployments
- Advancing Deep Learning Specialization (working on Sequence Models course)

---

## Connect

**GitHub:** [https://github.com/rohit-sinha-76](https://github.com/rohit-sinha-76)

**LinkedIn:** [https://linkedin.com/in/rohit-sinha-76](https://www.linkedin.com/in/rohitsinha027/)

**Email:** [work.rohit.sinha.11@gmail.com](mailto:work.rohit.sinha.11@gmail.com)

---

## Open To

Actively seeking opportunities in:
- Machine Learning Research (internships & roles)
- Deep Learning & AI Engineering (corporate positions)
- Full-Stack Development with ML integration
- Biomedical AI and healthcare technology projects
- Research-oriented development roles
