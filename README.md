<h1 align="center">Hi there 👋, I'm Anoop Mishra</h1>
<h3 align="center">
🚀 M.Tech | NIT  | Data Scientist | Machine learning | Analyst | R&D Enthusiast
</h3>

---

### 📍 About Me

I'm **Anoop Mishra** from **Lucknow, India**, currently pursuing M.Tech  at **Malaviya National Institute of Technology, Jaipur (MNIT Jaipur)**.

I am passionate about transforming data into impactful solutions through advanced analytics and machine learning. My journey in technology spans multiple domains—from environmental modeling to AI-driven decision-making tools.
---
### 🧠 What I Do

- 🎓 M.Tech |NIT
- 📊 Expert in **Data Science**, **Model Building**,**Data Analysis**,**Deep Learning**,** Data-Driven Decision Making**,**Machine Learning** and **GIS & LULC Mapping**
- 💡 Guiding **20+ students** in their academic and technical projects
- 🔭 Actively working in the **R&D field**, especially in **climate and spatial modeling**
- 🌍 Passionate about **Data Science and Data Analysis** with a strong focus on real-world applications 
- 🚀 Exploring **Deep Learning**, **GenAI**, and **Cloud Model Deployment**
---
### 💼 Currently Working On

- 📌 **Project**: `Drought Analysis using SPI & Trend Analysis (1980–2020)`
- 📍 **Regions**: Jaipur & Jodhpur Divisions, Rajasthan, India
- 🧪 Analysis using SPI-3, SPI-6, SPI-9, SPI-12, SPI-18, Mann-Kendall, Sen’s Slope
- 🛠 Tools Used: Python, Pandas, Matplotlib, Excel, GIS, IMD Rainfall Data

---

### 🛠️ Skills & Tools

- 👨‍💻 Python Developer | Machine Learning | Deep Learning | Data Science
- 📊 Data Analysis | Excel Advanced | Power BI | Model Deployment
- 🧠 AI & GenAI | NLP | Computer Vision | LLMs | Chatbots
- 🌐 Web APIs | Automation | Data-Driven Decision Making
- 🛰️ GIS | Remote Sensing | QGIS | LULC Classification
- ☁️ Cloud Computing (AWS/GCP) – Learning Phase
- 🧪 Research | Project Mentoring | Scientific Writing

---

### 👨‍🏫 Mentorship

- 👥 Guiding over **20+ students** in **Python**, **ML**, **GIS**, and **R&D Projects**
- 🧩 Helping peers understand and build models for real-world data problems
- 🔗 Collaborating with professors, engineers, and research teams

---

### 📫 Connect with Me

- 🔗 LinkedIn: [anoop-mishra-b5b61314a](https://www.linkedin.com/in/anoop-mishra-b5b61314a/)
- 📬 Email: anoopkumarmishra3875@gmail.com
- 🐙 GitHub: [mishraanoop1028](https://github.com/mishraanoop1028)
- 📱 Phone: +91 8968343668
- 🏫 Institute: Malaviya National Institute of Technology Jaipur (MNIT Jaipur)

---

### 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mishraanoop1028&show_icons=true&theme=radical" alt="Anoop's GitHub stats" />
  <br />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mishraanoop1028&layout=compact&theme=radical" alt="Top Languages" />
</p>

---

### 🌟 Motto

> "Learn continuously. Build fearlessly. Mentor selflessly."

---

⭐ *Thank you for visiting my profile! Feel free to connect and explore my repositories for exciting real-world data science and GIS applications!*

# 🌍 Geospatial AI Risk Engine: 41-Year Climatic Time-Series Forecasting
**Architecting Agricultural Resilience through Deep Learning and SPI-based Feature Engineering**

[![Docker Support](https://img.shields.io/badge/Docker-Supported-blue.svg)](https://www.docker.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.11](https://img.shields.io/badge/Python-3.11-green.svg)](https://www.python.org/)

---

## 🚀 Project Overview
This project transforms 41 years of granular IMD climatic data into a high-fidelity **Early Warning System (EWS)** for drought and rainfall risk. By moving beyond traditional statistics, it utilizes **LSTM (Long Short-Term Memory)** networks to predict multi-scale temporal indices (SPI-3 to SPI-18), providing a blueprint for risk management in semi-arid regions.

### 🎯 Key Engineering Highlights
* **Big Data Pipeline:** Engineered features from **15,000+ daily observations** (1980–2021).
* **Advanced Feature Engineering:** Automated calculation of the **Standardized Precipitation Index (SPI)** across multiple time scales.
* **Architecture:** Hybrid modeling approach combining **Deep Learning (LSTMs)** with **Ensemble Methods (XGBoost/Random Forest)** for baseline comparison.
* **Production Ready:** Fully containerized environment for seamless deployment on AWS/Azure.

---

## 🛠️ System Architecture


The pipeline is modularized into three core services:
1. **Ingestion Engine:** Automated cleaning and normalization of IMD raw datasets.
2. **Analysis Core:** SPI computation and statistical stationarity testing (ADF/KPSS).
3. **Forecasting Service:** LSTM model training, hyperparameter tuning, and inference.

---

## 🐳 Deployment (Docker Instructions)
To ensure 100% reproducibility in any environment (Production/Research), use the provided Docker configuration.

### 1. Build the Image
```bash
docker build -t geospatial-ai-engine .
