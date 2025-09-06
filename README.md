# FlexAI 🏋️‍♂️  
> **AI-powered Gym Form Tracking App**  
Built with **Streamlit**, **MediaPipe Pose**, and **OpenAI**

[![Streamlit](https://img.shields.io/badge/Framework-Streamlit-FF4B4B?logo=streamlit&logoColor=white)](https://streamlit.io/)  
[![MediaPipe](https://img.shields.io/badge/Computer%20Vision-MediaPipe-34A853?logo=google&logoColor=white)](https://mediapipe.dev/)  
[![OpenAI](https://img.shields.io/badge/AI-OpenAI-412991?logo=openai&logoColor=white)](https://openai.com/)  
[![Python](https://img.shields.io/badge/Language-Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)  

---

## **📌 Overview**
FlexAI is an **AI-powered gym form tracking app** that uses **computer vision** and **OpenAI** to analyze exercise posture, **joint angles**, and **rep tempo** in real-time.  
It provides **instant feedback**, **personalized coaching**, and tracks your progress with **visual performance analytics**.

---

## **✨ Features**
✅ Real-time gym form tracking  
✅ Posture & angle detection using MediaPipe  
✅ Rep counting & tempo analysis  
✅ AI-powered personalized feedback  
✅ Progress tracking dashboard  
✅ Visual stats & performance history  

---

## **🛠️ Tech Stack**
- **Frontend** → Streamlit (dark, responsive UI)
- **Computer Vision** → MediaPipe Pose + OpenCV (headless)
- **AI Support** → OpenAI GPT integration
- **Data Analysis** → NumPy, Pandas, Matplotlib
- **Development** → GitHub Codespaces

---

## **⚡ Installation**
```bash
# Clone the repository
git clone https://github.com/SamadBhimani07/FlexAI.git

# Navigate to the project folder
cd FlexAI

# Create a virtual environment
python3 -m venv .venv
source .venv/bin/activate   # For Mac/Linux
.venv\Scripts\activate      # For Windows

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run flexAI.py
