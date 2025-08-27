# Internship Tasks – DevelopersHub Corporation  

## Task 2: End-to-End ML Pipeline with Scikit-learn  

**Objective**  
Build a reusable, production-ready machine learning pipeline for predicting **customer churn**.  

**Methodology**  
- Preprocess data (scaling, encoding) using `Pipeline`.  
- Train baseline models (Logistic Regression, Random Forest).  
- Perform hyperparameter tuning with `GridSearchCV`.  
- Export the complete pipeline using `joblib` for deployment.  

**Key Results / Observations**  
- Streamlined preprocessing and training into a single reusable pipeline.  
- Improved model accuracy through systematic hyperparameter tuning.  
- Exported model ensures reusability and production readiness.  

---

## Task 3: Multimodal ML – Housing Price Prediction  

**Objective**  
Predict housing prices by combining **structured tabular data** with **house images**.  

**Methodology**  
- Use **CNNs** to extract image features.  
- Fuse extracted image embeddings with structured/tabular data.  
- Train a regression model on combined features.  
- Evaluate with **MAE** and **RMSE**.  

**Key Results / Observations**  
- Multimodal learning improves prediction performance compared to tabular-only models.  
- CNN feature extraction captures visual aspects (e.g., size, quality) that tabular data misses.  
- Achieved more robust and generalizable housing price predictions.  

---

## Task 4: Context-Aware Chatbot (LangChain / RAG)  

**Objective**  
Build a **conversational chatbot** that remembers context and retrieves external knowledge during interactions.  

**Methodology**  
- Implement **LangChain** or **Retrieval-Augmented Generation (RAG)** framework.  
- Store conversational history for context retention.  
- Use a **vectorized document store** for retrieval from custom corpus (e.g., Wikipedia, internal docs).  
- Deploy chatbot with **Streamlit**.  

**Key Results / Observations**  
- Developed chatbot capable of **contextual, multi-turn conversations**.  
- Integrated vector search allows accurate knowledge-grounded responses.  
- Deployment demonstrates practical use of **LLM + retrieval pipelines**.  





