# Oshiwambo-NLP-Hybrid-Reconstruction

This repository contains the implementation of a Hybrid AI framework designed to preserve and revive the Oshiwambo language through advanced Natural Language Processing (NLP). This work was developed as part of a Master of Data Science thesis at the Namibia University of Science and Technology (NUST).

## 🚀 Project Overview
The system addresses the dialectal variations within Oshiwambo by utilizing a dual-pathway architecture that combines deterministic dataset matching with predictive deep learning models.

### Key Objectives:
1. **Morphological Peeling:** An N-gram based mechanism to isolate semantic roots from complex Oshiwambo word structures.
2. **Hybrid Feature Fusion:** A deep learning engine combining **CNNs** (for spatial morphological fingerprinting) and **Bidirectional LSTMs** (for sequential context analysis), resulting in a 768-dimensional feature vector.
3. **Agglutinative Synthesis:** A generative module that reconstructs correct linguistic forms for "Out-of-Vocabulary" terms using root preservation and affix extraction.

## 🛠️ Tech Stack
- **Languages:** Python
- **Frameworks:** TensorFlow, Keras, Scikit-learn
- **Libraries:** Pandas, NumPy, RapidFuzz (for fuzzy string matching)
- **Deployment:** Streamlit (Web UI)

## 🏗️ Architecture
The system utilizes a dual-pathway logic:
- **Deterministic Path:** Uses SVM and Min-Max scaling for high-accuracy classification of known vocabulary.
- **Predictive Path:** Employs the CNN + Bi-LSTM fusion layer for unknown or evolving dialectal tokens.

## 📁 Repository Structure
- `/data`: Empirical datasets and dialectal feature indices.
- `/models`: Saved weights for the CNN-LSTM hybrid architecture.
- `/src`: Core logic for morphological peeling and agglutinative synthesis.
- `app.py`: The Streamlit interface for live testing and prediction.

---
**Author:** Raban S. Raban  
**Supervision:** Prof. Hippolyte N’sung-Nza Muyingi  
*Department of Informatics, Journalism and Media Studies, NUST.*
