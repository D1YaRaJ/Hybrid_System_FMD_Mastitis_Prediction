# 🐄 Hybrid System for Mastitis & FMD Prediction in Dairy Cows

A **web-based AI application** for early detection and diagnosis of **Mastitis** and **Foot & Mouth Disease (FMD)** in cattle using **symptom inputs** and **image processing**.

---

## 📌 Table of Contents
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [System Architecture](#system-architecture)
- [Setup & Installation](#setup--installation)
- [Application Endpoints](#application-endpoints)
- [Security & Privacy](#security--privacy)
- [License & Acknowledgments](#license--acknowledgments)

---

## Project Overview

This Hybrid Bovine Disease Identification System is designed to assist farmers and veterinarians in the **early detection and management** of two major cattle diseases: Mastitis and Foot & Mouth Disease (FMD). By combining **text-based symptom analysis** with **image-based AI models**, the system provides **real-time, accurate diagnosis** along with **treatment recommendations**.

---

## Problem Statement

Cattle diseases lead to serious economic losses:

- Mastitis costs the global dairy industry **≈ $35 billion annually**  
- FMD outbreaks can reduce milk yield by **20–50%**  
- Many small-scale farmers lack access to **timely veterinary diagnostics**  
- Traditional methods are **slow and require specialized expertise**

---

## Features

### Disease Detection
- Mastitis diagnosis via udder image analysis  
- FMD detection using:  
  - Mouth symptoms evaluation  
  - Foot symptoms evaluation  

### Multi-Modal Input
- Text-based symptom reporting  
- Image uploads for visual analysis:  
  - Udder images for Mastitis  
  - Mouth/Foot images for FMD  

### Comprehensive Reporting
- Diagnosis with **confidence percentages**  
- Severity-based treatment suggestions:  
  - **High risk:** Immediate action  
  - **Medium risk:** Monitoring recommended  
  - **Low risk:** Preventive measures  
- PDF report generation for record-keeping  

### Additional Features
- Multi-language support (**English, Hindi, Kannada**)  
- Interactive chatbot for guidance  
- Nearby veterinarian locator  
- Responsive interface for mobile devices  

---

## Technologies Used

### Frontend
- HTML5, CSS3, JavaScript  
- [i18next](https://www.i18next.com/) for multi-language support  
- [jsPDF](https://parall.ax/products/jspdf) for report generation  
- Chart.js for visualizing results  

### Backend
- Python 3.9+ with Flask  
- Machine Learning Models:  
  - **CNN** for image classification  
  - **Random Forest** for symptom analysis  

---

