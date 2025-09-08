# MigraineMamba Lite

AI-Powered Migraine Trigger Pattern Discovery System using Mamba Architecture and Self-Supervised Learning

## 🎯 Project Overview

MigraineMamba Lite analyzes migraine trigger patterns from patient history to create personalized risk predictions and prevention strategies. The system uses advanced AI techniques including:

- *Mamba Architecture*: Linear complexity temporal modeling for efficient time series processing
- *Self-Supervised Learning*: Pattern discovery from unlabeled lifestyle data
- *Explainable AI*: SHAP-based interpretability for medical insights
- *Web Application*: User-friendly interface for data input and prediction display

## 🏗 Project Structure


MigraineMamba-Lite/
├── data/                   # Dataset storage (raw data protected)
├── notebooks/             # Jupyter notebooks for analysis
├── src/                   # Source code
│   ├── data/             # Data processing modules
│   ├── models/           # ML model implementations
│   ├── api/              # Flask backend API
│   └── utils/            # Helper functions
├── frontend/             # React web application
├── models/               # Trained model storage
├── results/              # Analysis results and figures
├── docs/                 # Documentation
└── tests/                # Test suite


## 🚀 Quick Start

### Prerequisites
- Python 3.9+
- Node.js 14+ (for frontend)
- Git

### Installation
bash
git clone https://github.com/[username]/MigraineMamba-Lite.git
cd MigraineMamba-Lite

pip install -r requirements.txt

cd frontend
npm install


## 📊 Dataset

- *Size*: 62 patients with migraine history
- *Features*: Trigger patterns, lifestyle factors, temporal data
- *Target*: Migraine occurrence prediction
- *Privacy*: Raw data protected by .gitignore, only processed summaries shared

## 🧠 Technical Approach

1. *Data Analysis*: Comprehensive exploration of trigger patterns
2. *Feature Engineering*: Temporal features, trigger combinations, patient-specific metrics
3. *Self-Supervised Learning*: Learn trigger pattern embeddings from unlabeled data
4. *Mamba Model*: Bidirectional temporal modeling with linear complexity
5. *Explainability*: SHAP-based feature importance and patient-specific insights
6. *Web Interface*: React-based dashboard for predictions and visualizations

## 📈 Development Status

- [ ] *Milestone 1*: Data Foundation & Analysis
- [ ] *Milestone 2*: Data Pipeline & Feature Engineering  
- [ ] *Milestone 3*: AI Model Development
- [ ] *Milestone 4*: Backend API Development
- [ ] *Milestone 5*: Frontend Application
- [ ] *Milestone 6*: Personalization & Retraining
- [ ] *Milestone 7*: Deployment & Documentation

## 📝 License

MIT License - See LICENSE file for details

---

*Note*: This is an active academic research project. Patient data is protected and not included in this repository.

