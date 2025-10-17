💡 AI-Powered Loan Eligibility Advisory System

 An AI-driven web application that predicts loan eligibility, explains model decisions, and provides personalized financial insights through an intelligent chatbot.

🧭 Overview

Loan approval decisions are often **slow, inconsistent, and opaque**, especially in high-volume financial institutions.  
This project builds an **AI-powered web platform** that automates **loan eligibility analysis** using machine learning and natural language processing (NLP).

The system predicts approval likelihood based on user-provided financial information, generates **transparent PDF-based decision summaries**, and integrates a **financial guidance chatbot** for improved accessibility and user understanding.

🎯 Core Features

| Feature | Description |
|----------|-------------|
| **Loan Approval Prediction Engine** | Predicts approval probability using trained ML models based on credit score, income, and financial history. |
| **Explainable AI Outputs (SHAP)** | Visualizes how each input feature affected the decision, improving model transparency. |
| **Personalized Financial Chatbot** | Provides tailored explanations and financial tips using transformer-based NLP models. |
| **Automated PDF Report Generation** | Creates downloadable credit evaluation reports summarizing inputs, predictions, and SHAP insights. |
| **Real-Time Evaluation Workflow** | Processes inputs, performs inference, and displays results instantly through a responsive web interface. |

🧩 System Modules

1. **Data Ingestion & Preprocessing**  
   - Cleans and processes input data from user forms and uploaded financial documents.  
   - Uses **pdfplumber**, **OpenCV**, and **pytesseract** for document extraction and OCR.

2. **Machine Learning Model Training & Inference**  
   - Implements **Scikit-learn’s RandomForestClassifier** with balanced class weights for robust predictions.  
   - Outputs approval probability and decision results in real-time.

3. **Explainability & Report Generation**  
   - Uses **SHAP** for interpretable model outputs.  
   - Generates a **professional PDF report** summarizing data, visual explanations, and decision logic.

4. **Chatbot Integration & App Deployment**  
   - Integrates a transformer-based financial assistant to explain results and answer common questions.  
   - Deploys via **FastAPI** and **Socket.IO** for responsive, real-time interactions.
