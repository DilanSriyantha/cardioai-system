# ❤️ CardioAI

**CardioAI** is an intelligent cardiac risk prediction and health insight system that combines **machine learning, conversational interfaces, and medical report analysis** to provide accessible and explainable cardiovascular risk assessments.

> ⚠️ This is a **hub repository**.  
> It contains documentation and links to individual system components.  
> Source code is maintained in separate repositories.

---

## 🚀 Overview

CardioAI is designed to make **cardiovascular risk assessment more accessible**, especially for non-technical users.

The system allows users to:

- Input health data through a **chat-based interface**
- Upload medical reports for **automated data extraction**
- Receive **AI-driven cardiac risk predictions**
- Get **explainable insights and recommendations**

---

## ✨ Key Features

### 🤖 AI-Based Risk Prediction
- Machine learning model trained on medical datasets
- Predicts likelihood of cardiac-related conditions
- Provides interpretable results based on input features

### 💬 Conversational Data Collection
- Chat-like interface for collecting user health data
- Improves usability for non-technical users
- Reduces friction in data entry

### 🧾 Medical Report Analysis
- Upload medical reports (images/documents)
- Extract relevant health parameters using OCR
- Automatically populate prediction inputs

### 📊 Explainable Insights
- Recommendations based on model outputs
- Simplified explanations for end users
- Focus on accessibility and clarity

### 🌐 Full-Stack System
- Web-based frontend
- API-driven backend
- Dedicated ML prediction service

---

## 🏗 Project Architecture

CardioAI follows a **multi-service architecture**, separating concerns across independent systems:

| Component | Description | Repository |
|----------|------------|------------|
| 🌐 Frontend | React-based user interface | https://github.com/DilanSriyantha/cardioai-frontend |
| ⚙️ Backend | NestJS API for orchestration & data handling | https://github.com/DilanSriyantha/cardioai-backend |
| 🧠 Prediction Service | FastAPI ML service for predictions | https://github.com/DilanSriyantha/cardioai-prediction-service |

---

## 🛠 Tech Stack

**Frontend**
- React.js

**Backend**
- NestJS (Node.js)
- REST API architecture

**Machine Learning Service**
- FastAPI (Python)
- Scikit-learn / ML models

**Database**
- MySQL

---

## 🧠 System Design Approach

- **Microservice-based architecture**
- **Separation of AI and application logic**
- **Explainable AI focus**
- **User-friendly interaction model (chat-based input)**
- **Healthcare-oriented usability**

---

## 📸 Screenshots

<div>
    <img src="https://i.ibb.co/1fFxRHFj/Screenshot-2026-03-12-104513.png" alt="Screenshot 2026 03 12 104513" border="0">
    <img src="https://i.ibb.co/NnW4xGDp/Screenshot-2026-03-12-104535.png" alt="Screenshot 2026 03 12 104535" border="0">
    <img src="https://i.ibb.co/GvWFdRZJ/Screenshot-2026-03-12-104654.png" alt="Screenshot 2026 03 12 104654" border="0">
    <img src="https://i.ibb.co/GfcQhMHX/Screenshot-2026-03-12-104741.png" alt="Screenshot 2026 03 12 104741" border="0">
    <img src="https://i.ibb.co/yc8b3p3S/Screenshot-2026-03-12-104840.png" alt="Screenshot 2026 03 12 104840" border="0">
    <img src="https://i.ibb.co/hJsYNSPn/Screenshot-2026-03-12-104855.png" alt="Screenshot 2026 03 12 104855" border="0">
    <img src="https://i.ibb.co/27vDQ7jC/Screenshot-2026-03-12-104916.png" alt="Screenshot 2026 03 12 104916" border="0">
    <img src="https://i.ibb.co/gLfNM3DH/Screenshot-2026-03-12-104346.png" alt="Screenshot 2026 03 12 104346" border="0">
    <img src="https://i.ibb.co/KxDKrWLJ/Screenshot-2026-03-12-104429.png" alt="Screenshot 2026 03 12 104429" border="0">
    <img src="https://i.ibb.co/3mXqbqmQ/Screenshot-2026-03-12-104455.png" alt="Screenshot 2026 03 12 104455" border="0">
</div>
---

## 🔬 Research Context

This project was developed as a **final-year research project**, focusing on:

- Applying machine learning to healthcare
- Improving accessibility of medical insights
- Enhancing user interaction using conversational interfaces
- Bridging the gap between AI models and real-world usability

---

## ⚠️ Disclaimer

CardioAI is intended for **educational and research purposes only**.  
It does **not replace professional medical advice, diagnosis, or treatment**.

---

## 🔮 Future Improvements

- Improved model accuracy with larger datasets
- Integration with real hospital systems
- Advanced explainable AI techniques
- Mobile application support
- Real-time health monitoring integrations

---

## 📄 License

MIT License
