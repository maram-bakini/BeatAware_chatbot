# BEATAWARE: A Medical Chatbot for Early Detection of Heart Disease

## Introduction
BEATAWARE is an innovative chatbot application designed to assist in the early detection of heart disease. Our goal is to empower individuals by providing insights based on their symptoms, encouraging them to seek timely medical advice. While it is not a replacement for professional medical consultation, BEATAWARE acts as a first step in identifying potential risks.

---

## The Problem
Heart disease is one of the leading causes of mortality worldwide. Many patients ignore early symptoms due to a lack of awareness or access to quick diagnostic tools. This delay often leads to severe consequences. BEATAWARE addresses this critical gap by offering a smart, user-friendly chatbot for symptom analysis.

---

## How It Works
1. **Model Selection**:  
   BEATAWARE is built on the **Gemma 2** model, known for its versatility and general capabilities.

2. **Data Preparation**:  
   - A detailed dataset dedicated to heart disease classification was sourced.
   - Data was converted into a question-answer format for effective interaction within the chatbot's conversational framework.

3. **Model Fine-Tuning**:  
   - We employed the **LoRA (Low-Rank Adaptation)** technique to efficiently fine-tune the Gemma 2 model for heart disease diagnostics.
   - LoRA allowed us to introduce trainable layers without retraining the full model, optimizing computational efficiency while retaining the original knowledge base.

4. **Validation**:  
   - Rigorous testing and hyperparameter tuning were conducted to ensure reliability across various scenarios.

5. **Deployment**:  
   - The fine-tuned model was deployed on **Kaggle**, leveraging its robust AI hosting capabilities.
   - A **Streamlit** interface was developed to provide a seamless and intuitive chat experience for users.

---

## Features
- Symptom-based diagnostic assistance.
- Conversational interface powered by AI.
- Secure and accessible on Kaggle.

---

## Technologies Used
- **Gemma 2**: Pre-trained language model.
- **LoRA**: For efficient model fine-tuning.
- **Streamlit**: For user interface development.
- **Kaggle**: For model deployment.

---

## How to Run the Application
1. Access the chatbot on Kaggle (add a link here if applicable).
2. Launch the Streamlit application to interact with the chatbot.
3. Input symptoms to receive diagnostic insights and recommendations.

---

## Credits
- **Team BEATAWARE**  
  Developed by a dedicated team focused on making health insights accessible to everyone.

---

## Quote
_"The greatest wealth is health." – Virgil_
