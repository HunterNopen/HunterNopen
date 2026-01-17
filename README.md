Hi 👋 My name is Roman Herasymov
================================

AI Engineer & Data Scientist | Former Software Engineer
---------------------------------

The force has led me to you, friend? \
I'm a **passionate student and developer** with a solid software background and architecting new solutions!
Currently it's - DeepLearning & MachineLearning systems - from experimentation in notebooks to robust, deployable services.
**Team player** Solo play is great, but I gotta always ask for a review & deployment someone else.

* 🌍  I'm based in Poland, Gdansk
* 🖥️  Explore my portfolio on [LinkedIn](https://www.linkedin.com/in/roman-herasymov)
* ✉️  You can contact me at [gerasimovroman05@gmail.com](mailto:gerasimovroman05@gmail.com)
* 📝  Explore my CV for a tailored summarization [OverLeaf](https://www.overleaf.com/read/nzcmsxfwmrqz#c6294e)
* 🧠  Current zone of interest **Machine Learning, Deep Learning, and Data Science** 
* ⚡  Fun fact: I have a love-hate relationship with React... but shhh, don't tell my team!
 
---

### 📌 Featured AI Projects

#### 🩺 SkinGlanceCare - Early Skin Health Screening (Diploma Thesis Project combining ComputerVision + MLOps)

[![SkinGlanceCareRepo - Application](https://img.shields.io/badge/GitHub_Repo_Application-blue?logo=github)](https://github.com/HunterNopen/SkinGlanceCare)
[![SkinGlanceCareRepo - Model](https://img.shields.io/badge/GitHub_Repo_Model-blue?logo=github)](https://github.com/HunterNopen/SkinGlanceCare_Model)
[![SkinGlanceCareHF](https://img.shields.io/badge/HuggingFace_Space-darkkhaki?logo=huggingface)](https://huggingface.co/spaces/HunterNope/SkinGlanceCare)
[![SkinGlanceCareHF](https://img.shields.io/badge/HuggingFace_Space-darkkhaki?logo=huggingface)](https://huggingface.co/spaces/HunterNope/SkinGlanceCare) 

ComputerVision‑based solution for **early skin health checks from photos**. Includes model pipeline: preprocessing -> training & architecture, REST API & Flask and deployment (OpenVINO quantization via NNCF + HF space CPU)

- **Stack:** Python, PyTorch, OpenVINO, Flask & Gradio, MLflow, Docker, CI/CD, Pandas, Scikit‑Learn,
- **Demo:** https://huggingface.co/spaces/HunterNope/SkinGlanceCare  
- **Highlights:**
  - **Achieved >92\% Cancer Recall** using EfficientNet backbone with custom attention mechanism and specialized loss functions, after empirically evaluating multimodal approaches and rejecting ensemble methods due to deployment overhead
  - **Reduced model size by 63.5\% (48MB => 17.5MB)** via INT8 quantization with OpenVINO \& NNCF, maintaining classification accuracy while enabling CPU-based inference
  - **Built complete MLOps pipeline:** data preprocessing (15K+ images across 3 datasets), stratified sampling, experiment tracking (MLFlow), containerization and HuggingFace Space deployment
  - **Architected \& documented production-ready skin lesion classification system** as thesis project, making engineering trade-offs between model performance, deployment complexity, and medical AI regulatory constraints in \textbf{200-page research paper}
- **Results:** Diploma Thesis 200-page, End-2-End pipeline favoring Transperency \& Reproducibility, Cancer Recall >90%, Deployed, Quantized, Optimized Ready Solution

---

#### 🛡️ AutoCenzurer - ASR (Automatic Speech Recognition) Policy-Enforcement Tool using LLM API \& SLM Local

[![AutoCenzurer](https://img.shields.io/badge/GitHub_Repo-blue?logo=github)](https://github.com/HunterNopen/AutoCenzurer) 
[![SkinGlanceCareHF](https://img.shields.io/badge/HuggingFace_Space-darkkhaki?logo=huggingface)](https://huggingface.co/spaces/HunterNope/AutoCenzurer) - May NOT Work due to Free Tier Usage

Policy-Enforcement Tool combining classic NLP pipelines with LLM‑based reasoning for **knowledge-distillation to local SLM**.  
**Transparent - Reproducible - Explainable**

- **Stack:** Python, NLP, Ffmpeg, Qwen \& Llama, Groq API 
- **Demo:** open‑source **distilled & quantized local LLM** for on‑device / self‑hosted inference + mobile inference 
- **Highlights:**
  - **Designed explainable content moderation system** using hybrid architecture: **rule-based filtering** (regex, beam search) for transparency + **distilled SLM** for semantic understanding, explicitly avoiding pure ML black box approaches
  - **Built synthetic training data pipeline** via LLM distillation: Groq-hosted Llama 7B (teacher) => **locally-deployed quantized LoRA Qwen 7B (student)**, achieving API independence while maintaining policy alignment
  - **Chose rule-based + distilled model** over SOTA deep learning to maintain transparency and auditability for policy enforcement use cases
- **Results:** Quantized & Distilled NLP production-ready solution both for **Static Audio Filtering** as a quick and scalable solution!

---

#### 📰 FakeNewsDetectorML - NLP + LLM Agent Architecture

[![FakeNewsDetectorML](https://img.shields.io/badge/GitHub_Repo-blue?logo=github)](https://github.com/HunterNopen/FakeNewsDetectorML)  

ML‑based solution for **fake news detection** with modern NLP tooling.

- **Stack:** Python, PyTorch, Hugging Face, OpenAI API, Agent architecture + Open-Source (Open-Weights) Models Utilization (Bert, Distilbert, Roberta...)
- **Highlights:**
  - Combines traditional modeling with LLM‑powered components
  - Demonstrates end‑to‑end workflow: modeling, backend, and simple UI
- **Results:** Ensemble Learning with Boosting Techniques helped to fine-tune and achieve the desired acc of 91%.

---

#### 🙂 GetFacialExp - Real-Time Facial Expression Recognition

[![GetFacialExp](https://img.shields.io/badge/GitHub_Repo-blue?logo=github)](https://github.com/HunterNopen/GetFacialExp)
[![GetFacialExpApp](https://img.shields.io/badge/Streamlit_App-cyan?logo=streamlit)](https://hunternopen-getfacialexp.streamlit.app)  

Real‑time facial expression recognition using a CV stack and deep learning.

- **Stack:** Python, OpenCV, PyTorch, Torchvision, Streamlit  
- **Demo:** https://hunternopen-getfacialexp.streamlit.app  
- **Highlights:**
  - Implemented real‑time inference from webcam/video streams
  - Preprocessing, model training, and interactive UI for experimentation
- **Results:** Accuracy ≈ **75%**

---

#### 🧠 DepressionRateAI - Tabular ML Pipeline for Mental Health Risk

[![DepressionRateAI](https://img.shields.io/badge/GitHub_Repo-blue?logo=github)](https://github.com/HunterNopen/DepressionRateAI)  

End‑to‑end **ML pipeline** for predicting depression risk, demonstrating classical ML workflows.

- **Stack:** TensorFlow, Keras, scikit‑learn, NumPy, Pandas  
- **Write‑up:** https://docs.google.com/document/d/1p-5dWHP_y1_cB9ojg2oQ_C-L-HL5CJt8Bsg1K21GLjI/edit  
- **Highlights:**
  - Complete pipeline: preprocessing, feature engineering, model training, evaluation, and testing
  - Comparison of different ML algorithms on tabular data
- **Results:** Accuracy ≈ **92%**, RMSE < **0.1**

---

#### 🧪 ImplementSelfNN - Implementing ML/DL from Scratch

[![ImplementSelfNN](https://img.shields.io/badge/GitHub_Repo-blue?logo=github)](https://github.com/HunterNopen/ImplementSelfNN)  

Self‑implementation of ML/DL algorithms, models, and functions in pure Python.

- **Goal:** Understand the **“inner kitchen”** of neural networks and optimization  
- **Highlights:**
  - Manual implementation of core components without high‑level frameworks
  - Focus on mathematical foundations and numerical behavior

---

### 🛠 Tech Stack (AI Engineer Focus)

#### Languages
![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

#### Machine Learning & Deep Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C.svg?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00.svg?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000.svg?style=for-the-badge&logo=keras&logoColor=white)
![Scikit‑learn](https://img.shields.io/badge/Scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

#### MLOps & Experimentation
![MLflow](https://img.shields.io/badge/MLflow-0194E2.svg?style=for-the-badge&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-ffc107?style=for-the-badge&logo=huggingface&logoColor=black)

#### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23336791.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-%234479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%2347A248.svg?style=for-the-badge&logo=mongodb&logoColor=white)

#### Backend & APIs
![Node.js](https://img.shields.io/badge/Node.js-%23339933.svg?style=for-the-badge&logo=node.js&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-%23512BD4.svg?style=for-the-badge&logo=dotnet&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-%23E10098.svg?style=for-the-badge&logo=graphql&logoColor=white)
![REST](https://img.shields.io/badge/REST-02569B?style=for-the-badge&logo=rest&logoColor=white)

#### Frontend & Apps
![React](https://img.shields.io/badge/React-%2361DAFB.svg?style=for-the-badge&logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

---

### 🔍 Currently

- Building **end‑to‑end AI applications** (CV + NLP) with real users in mind  
- Deepening knowledge of **model monitoring, deployment patterns, and production ML**  
- Exploring **self‑implemented neural networks** to better understand performance trade‑offs

---

### 🤝 Let’s Collaborate!  
I'm always excited to work on innovative projects or collaborate on open-source. Feel free to reach out!  
