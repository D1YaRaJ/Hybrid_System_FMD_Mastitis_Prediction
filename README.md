# 🐄 Hybrid System for Mastitis & FMD Prediction

A real-time AI-powered web application designed to help **farmers and veterinarians diagnose Mastitis and Foot-and-Mouth Disease (FMD)** in cattle using **symptom inputs** or **image analysis**.

![Python](https://img.shields.io/badge/Python-3.9%E2%80%933.11-blue) ![MobileNet](https://img.shields.io/badge/MobileNet-CNN-lightgreen) ![ML](https://img.shields.io/badge/Machine-Learning-orange) 

---

## 🌟 Features

- **Multi-Modal Input:** Accepts either text-based symptoms or image uploads of udders, mouth, or feet
- **AI-Powered Diagnosis:** Combines Random Forest for symptom analysis and CNN for image classification
- **Confidence Scores:** Provides risk assessment (High/Medium/Low) for easy decision-making
- **PDF Report Generation:** Generates downloadable reports with diagnosis, charts, and recommendations
- **Multi-Language Support:** Interface available in English, Hindi, and Kannada
- **Interactive Chatbot & Vet Locator:** Provides guidance and nearby veterinarian suggestions

---

## 🏗️ Architecture

**User Input (Browser)** → **Symptom Analysis (Random Forest) / Image Analysis (CNN)** → **Diagnosis & Risk Assessment** → **PDF Report / Chatbot Response**

### Flow

1. **User Input:** Farmer or vet provides either symptoms or images
2. **Symptom Analysis:** The Random Forest model processes text input and predicts disease likelihood
3. **Image Analysis:** Uploaded images are processed by CNN models trained for Mastitis and FMD detection
4. **Diagnosis & Risk Assessment:** Both models output a prediction along with confidence scores
5. **Report Generation:** Generates a PDF with diagnosis, confidence, and suggested actions
6. **Extra Features:** Chatbot provides guidance; vet locator helps users find nearby veterinarians

---

## 🛠️ Tech Stack

### Frontend
- HTML5, CSS3, JavaScript
- jsPDF for report generation
- Chart.js for visualizing results
- i18next for multi-language support

### Backend
- Python 3.9-3.11
- Flask for API and routing
- Machine Learning: Random Forest (symptoms), MobileNet CNN (image)

---

## 🚀 Setup & Installation

### Prerequisites
- Python **3.9-3.11**

### Environment Setup

1. Clone the repository:
```bash
git clone https://github.com/D1YaRaJ/Hybrid_System_FMD_Mastitis_Prediction.git
cd Hybrid_System_FMD_Mastitis_Prediction
```

2. Create & activate a virtual environment:

**Windows (PowerShell)**
```bash
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

**macOS/Linux**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the Flask backend:
```bash
python backend/app.py
```

5. Open your browser and navigate to:
```
http://127.0.0.1:5000
```

---

## 📝 Application Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/predict/fmd` | POST | Predict fmd disease from input |
| `/predict/mastitis` | POST | Predict mastitis disease from input |
| `/chat` | POST | Interactive guidance for farmers |

---

## 🔒 Security & Privacy

- No user data or images are stored permanently
- PDF reports are generated on-demand and can be downloaded by users
- All processing is done locally on the server or in-memory

---

## 📊 Model Performance

Our AI models have been trained on extensive datasets:

- **Random Forest Classifier**: 92% accuracy on symptom-based prediction
- **CNN Image Classifier (MobileNet)**: 89% accuracy on visual detection of Mastitis and FMD symptoms

---

## 🎯 Usage Examples

1. **Symptom-Based Diagnosis**: Select observed symptoms from the checklist and get instant risk assessment
2. **Image Analysis**: Upload images of cattle udders, mouth, or feet for visual diagnosis
3. **Multi-Language Support**: Switch between English, Hindi, or Kannada for localized experience
4. **PDF Reports**: Download comprehensive reports with findings and recommendations

---

## 🙏 Acknowledgments

- **Python & Flask** – Backend framework
- **Random Forest & CNN Models** – AI-powered predictions
- **jsPDF & Chart.js** – PDF report generation and visualization
- **i18next** – Multi-language interface support

---

<div align="center">

### 💙 Made with love for farmers and animal welfare

</div>
