# ​ Hybrid System for Mastitis & FMD Prediction

An **AI-powered web application** designed to help dairy farmers and veterinarians **quickly diagnose Mastitis and Foot-and-Mouth Disease (FMD)** in cattle using both **symptom inputs** and **image analysis**.

---

##  Overview

- **Hybrid Multi-Modal Diagnosis**: Accepts either symptoms (text) or images to detect Mastitis and FMD.
- **Dual ML Approach**:  
  - Text Model: Random Forest classifier processes entered symptoms.  
  - Image Model: Convolutional Neural Network (CNN) classifies uploaded images.
- **Instant Results**: Get diagnosis, confidence scores, and risk categorization (High / Medium / Low).
- **Handy Reports**: Generate downloadable PDF summaries of diagnoses with visual charts.
- **Multi-Language Support**: Switch between English, Hindi, and Kannada seamlessly.
- **Helpful Extras**: Built-in chatbot and veterinarian locator to guide users further.

---

##  Tech Stack

| Layer        | Technology                              |
|--------------|------------------------------------------|
| Frontend     | HTML, CSS, JavaScript, **i18next**, **jsPDF** |
| Backend      | Python, Flask, ML models (CNN, Random Forest) |

---

##  Project Structure

```text
.
├── backend/             # Flask API + ML models backend
├── frontend/            # Static frontend files + localization (i18n)
├── FMD_Detection/       # CNN model & utilities for FMD
├── Mastitis_Detection/  # CNN model & utilities for Mastitis
├── predict.py           # Main prediction driver
└── requirements.txt     # Project dependencies
