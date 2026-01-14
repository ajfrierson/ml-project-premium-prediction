# ml-project-premium-prediction
Health Insurance prediction project

# Streamlit Application – Local Setup & Deployment Guide

This README explains how to run this Streamlit application on your local machine and how to deploy it for public or private access.

---

## 📦 Prerequisites

Make sure the following are installed on your system:

- **Python 3.8 – 3.11**  
  Check version:
  ```bash
  python --version

project-root/
│
├── app.py                  # Main Streamlit app
├── requirements.txt        # Python dependencies
├── README.md               # Documentation
├── artifacts/              # Models, scalers, data files
├── utils/                  # Helper modules
└── .streamlit/             # (Optional) Streamlit config
git clone https://github.com/your-username/your-repo.git
cd your-repo
## Windows
python -m venv venv
venv\Scripts\activate

## macOS/Linux
python3 -m venv venv
source venv/bin/activate

deactivate

# Install Dependencies:
pip install -r requirements.txt

# Run Streamlit APP
streamlit run app.py

