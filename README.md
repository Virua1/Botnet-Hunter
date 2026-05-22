# An AI-Driven Detection of IoT Botnet DDoS Attacks in Smart Cities

## Project Overview
This repository contains an intelligent, lightweight cybersecurity system designed to secure Smart City infrastructures against modern IoT Botnet and DDoS attacks. Leveraging optimized Machine Learning (ML) techniques, the system monitors, filters, and analyzes network traffic in real-time to maintain a balance between high detection accuracy and low computational overhead.

##  Core Features
* **Smart Data Filtering:** Implements an automated pipeline that extracts and structures network logs down to the top 10 most critical security features using ANOVA (SelectKBest).
* **Multi-Model ML Architecture:** Includes three calibrated models customized for different traffic constraints:
  * **Logistic Regression:** Serves as a lightweight baseline for edge devices.
  * **Support Vector Machine (SVM):** Utilizes a Linear Kernel optimized for high-dimensional stability.
  * **Random Forest (RF):** Designed with balanced decision tree ensembles for deep traffic classification.
* **Intelligent Live Dashboard:** Built entirely with Streamlit, showcasing live anomaly alerts, attack vs. normal traffic metrics, and robust confusion matrices.

##  Tech Stack & Libraries
* **Language:** Python 3
* **Framework:** Streamlit
* **Libraries:** Scikit-Learn, Pandas, NumPy, Joblib, Matplotlib, Seaborn
* **Dataset Used:** BoT-IoT Dataset

##  How to Run the Application
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the Streamlit web dashboard:
 ```bash
    streamlit run app.py
