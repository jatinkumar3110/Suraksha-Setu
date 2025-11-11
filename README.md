# 🌍 Suraksha Setu: AI-IoT Platform for Disaster Prediction & Response

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-FF6F00?logo=tensorflow)](https://www.tensorflow.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-Modeling-2E7D32?logo=xgboost)](https://xgboost.readthedocs.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Project Stage](https://img.shields.io/badge/Stage-Research--Prototype-orange)]()


**Suraksha Setu** is an AI-powered multi-hazard management platform integrating **machine learning, deep learning, and IoT** for the prediction, analysis, and response coordination of natural disasters — including **floods**, **wildfires**, and **landslides**.  

The system aims to enable **real-time risk intelligence, multilingual alerts, and inclusive disaster communication** for citizens, authorities, and vulnerable communities.  

## 📁 Repository Structure

📦 Suraksha-Setu
├── notebooks/                      # Jupyter notebooks for experiments
├── src/                            # Core reusable Python scripts
│   ├── data_processing.py          # Data preprocessing and generation
│   ├── model_training.py           # Model building and training utilities
│   ├── evaluate.py                 # Model evaluation and metrics
│   └── utils.py                    # Helper and support functions
│
├── SurakshaSetu_model 1.ipynb      # Model training & refinement (Phase 1)
├── SurakshaSetu_models_2.ipynb     # Multi-model refinement & optimization
├── Suraksha_Setu_Results.ipynb     # Inference & visualization dashboard
│
├── suraksha_setu_backend.zip       # Backend code for API / system integration
├── n8n automation architecture links.txt  # Integration workflow reference
├── requirements.txt                # Python dependencies
├── LICENSE                         # MIT License
└── README.md                       # Project documentation

## 🧠 Project Overview

**Suraksha Setu** integrates geospatial intelligence and AI-driven models to assess **multi-hazard risks** dynamically.

| Hazard | Model Type | Input Features | Output |
|--------|-------------|----------------|---------|
| 🌊 **Flood** | XGBoost (Multi-Class) | Geospatial & hydrological features | 5-class susceptibility levels |
| 🔥 **Fire** | CNN-LSTM | Meteorological & environmental parameters | Probability (0–1) |
| ⛰️ **Landslide** | XGBoost | Geological & topographic features | Probability (0–1) |
| 🧩 **Ensemble** | Weighted Fusion | Combines model predictions | Unified overall risk index |

Each component is modular, reusable, and optimized for integration with IoT and real-time data systems.


## ⚙️ Setup & Usage

### 🔧 Prerequisites
- Python **3.8+**
- Jupyter Notebook
- GPU (optional for deep learning acceleration)

### 🚀 Installation

git clone https://github.com/jatinkumar3110/Suraksha-Setu.git
cd Suraksha-Setu
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
pip install -r requirements.txt


### 🧪 Run the Notebooks

Then open the notebooks sequentially:

1️⃣ **`SurakshaSetu_model 1.ipynb`** — Flood / Fire / Landslide model training  
2️⃣ **`SurakshaSetu_models_2.ipynb`** — Multi-model refinement and fusion  
3️⃣ **`Suraksha_Setu_Results.ipynb`** — Scenario-based prediction & visualization  


## 📊 Features

✅ AI-powered **Flood**, **Fire**, and **Landslide** risk modeling  
✅ Multi-class **pluvial flood** susceptibility mapping  
✅ CNN-LSTM deep learning for **wildfire spread prediction**  
✅ Weighted ensemble for **multi-hazard risk fusion**  
✅ **Radar & bar visualizations** for scenario comparison  
✅ Modular pipeline for retraining and IoT integration  
✅ Ready for **real-time risk intelligence dashboards**  


## 🧩 Example Output

| Scenario | Flood | Fire | Landslide | Overall Risk |
|-----------|--------|-------|------------|---------------|
| Low | 🟢 Low | 🟠 Moderate | 🟢 Low | 🟢 Low |
| Moderate | 🟠 High | 🟠 Moderate | 🔴 High | 🔴 High |
| High | 🔴 Very High | 🔴 High | 🔴 High | 🔴 High |

*The ensemble output provides a unified multi-hazard risk score and categorical risk level.*


## 🗺️ Future Roadmap

- 🌐 **Real-time IoT ingestion** from sensors and drones  
- 🗣️ **Multilingual alert APIs** for inclusive communication  
- 🗺️ **GIS-based interactive risk dashboards**  
- 📡 **Edge ML deployment** for low-connectivity rural zones  
- 🧾 **Research publication and patent filing** (AI-driven multi-hazard fusion model)  


## 🤝 Contributors & Acknowledgements

- **Project BY** [@jatinkumar3110](https://github.com/jatinkumar3110)  
- **Supported by:** Risk Management Solutions (India), Ibadan Urban Flood Management Project  
- **Data Sources:** USGS, Copernicus Climate Data Store, GIS Academy  



## ⚖️ License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details

### 🌿 “When AI serves Nature, Nature sustains Humanity.” — *Suraksha Setu Vision*
