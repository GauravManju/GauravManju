<div align="center">

# Gaurav Manju

**MSc Artificial Intelligence with Industry · University of Leicester**<br/>
Python · Machine Learning · Applied AI · Software Engineering

[![Portfolio](https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=githubpages&logoColor=F0A500)](https://GauravManju.github.io/portfolio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHJlY3Qgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0IiByeD0iMyIgZmlsbD0iI0YwQTUwMCIvPjx0ZXh0IHg9IjEyIiB5PSIxOCIgZm9udC1mYW1pbHk9IkFyaWFsLEhlbHZldGljYSxzYW5zLXNlcmlmIiBmb250LXdlaWdodD0iNzAwIiBmb250LXNpemU9IjE1IiB0ZXh0LWFuY2hvcj0ibWlkZGxlIiBmaWxsPSIjMGQxMTE3Ij5pbjwvdGV4dD48L3N2Zz4%3D)](https://www.linkedin.com/in/gaurav-manju/)
[![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=F0A500)](https://github.com/GauravManju)
[![Email](https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=F0A500)](mailto:gauravsaimeena@gmail.com)

</div>

---

## About me

I'm an MSc Artificial Intelligence student at the University of Leicester, with a BEng in Computer Science from SJB Institute of Technology, India. Before my master's I completed four engineering internships, at ISRO, DRDO, Tech Mahindra and HAL, building Python desktop tools and web applications.

I like building AI software that is practical and explainable: an LLM where it genuinely helps, deterministic logic where trust matters, and tests around the parts that count.

**Currently seeking:** a UK industry placement (9–11 months, from February 2027) as part of my degree. No employer sponsorship is required.

---

## Featured projects

### AI Resume & Interview Assistant
[Live app](https://gaurav-resume-assistant.streamlit.app) · [Repository](https://github.com/GauravManju/ai-resume-assistant)

- **Problem:** Job seekers can't easily tell how well a CV matches a job description, and LLM-generated "match scores" are opaque and can hallucinate skills.
- **Approach:** Extracts text from PDF/DOCX resumes; uses Gemini with Pydantic-validated structured output to parse job descriptions into required/preferred skill groups (including "React *or* Angular" alternatives); matches skills deterministically, never via the LLM; and combines them with sentence-embedding similarity into a transparent weighted score. Gemini is used only for suggestions and interview questions, with a keyword-matching fallback if parsing fails.
- **Stack:** Python, Streamlit, sentence-transformers, Google Gemini API, Pydantic, PyMuPDF, python-docx, pytest, GitHub Actions
- **Result:** Deployed on Streamlit Community Cloud with a pytest suite covering extraction, skill matching and semantic scoring.

### Flood Extent Mapping with Sentinel-1 SAR
[Repository](https://github.com/GauravManju/cnn-flood-mapping-sentinel1) · MSc group project (5 members), project lead

- **Problem:** Optical satellites can't see through cloud during floods; radar (SAR) can, but needs a model to turn it into flood maps.
- **Approach:** Pixel-wise segmentation on the Sen1Floods11 hand-labelled dataset using a ResNet-34 U-Net on dual-polarisation (VV + VH) input, with BCE + Dice loss, class weighting for imbalance, NaN imputation and dB-scale normalisation.
- **Stack:** Python, PyTorch, segmentation-models-pytorch, rasterio, albumentations, Google Colab (T4 GPU)
- **Result:** Held-out test set: **IoU 0.563 · F1/Dice 0.720 · Precision 0.666 · Recall 0.784**.
- **My role:** Data pipeline and preprocessing, model and training loop, debugging, evaluation, and report.

### task-cli
[Repository](https://github.com/GauravManju/task-cli)

- **Problem:** A fast, keyboard-only way to manage tasks from the terminal.
- **Approach:** A packaged Python CLI with a separate SQLite data layer, Typer commands and Rich tables, plus priorities, due dates and overdue detection.
- **Stack:** Python, Typer, Rich, SQLite, pytest
- **Result:** Installable with `pip install -e .`; 11 unit tests cover the database layer.

### Big Data Analytics — Diabetes Readmission
[Repository](https://github.com/GauravManju/GROUP12_BIG_DATA) · MSc group coursework

- **Problem:** Analysing the UCI *Diabetes 130-US Hospitals* dataset (~100k encounters) for readmission patterns.
- **Approach:** Exploratory analysis, imbalanced classification and K-Means clustering.
- **Stack:** PySpark (MLlib), scikit-learn, imbalanced-learn, Jupyter

<details>
<summary><b>Other academic projects</b> (no public code)</summary>
<br/>

- **Anywhere Voting System:** Django remote-voting platform with facial recognition (OpenCV LBPH + Haar cascades), OTP/email two-factor authentication and a MySQL backend.
- **Insider Guard:** Python/MySQL application for anomaly-based intrusion detection and ML-based risk assessment.

</details>

---

## Experience

| Organisation | Role | Period | Summary |
|---|---|---|---|
| **DRDO — CASDIC** | GUI Developer Intern | Feb – Apr 2025 | Built a Python GUI for monitoring a fighter-aircraft coolant system. |
| **Tech Mahindra** | Project Intern | Dec 2024 – Feb 2025 | Worked in an enterprise team on software for semiconductor wafer processing. |
| **ISRO — URSC** | GUI Developer Intern | Sep – Oct 2024 | Built a Tkinter tool using NASA/JPL SPICE (spiceypy) to compute satellite position, latitude, longitude and altitude from kernel data. |
| **HAL** | Web Developer Intern | Oct – Nov 2023 | Built an e-commerce MVP in a team, including the cart, pricing and checkout flow. |

---

## Education

- **MSc Artificial Intelligence with Industry**, University of Leicester, UK · 2026 – 2028 (expected) · includes an integrated industry placement
- **BEng Computer Science**, SJB Institute of Technology, India · 2021 – 2025 · CGPA 8.58 / 10

---

## Tech stack

**Languages**<br/>
![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=F0A500)
![Java](https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=F0A500)
![SQL](https://img.shields.io/badge/SQL-0d1117?style=flat-square&logo=mysql&logoColor=F0A500)
![JavaScript](https://img.shields.io/badge/JavaScript-0d1117?style=flat-square&logo=javascript&logoColor=F0A500)
![HTML/CSS](https://img.shields.io/badge/HTML%20%2F%20CSS-0d1117?style=flat-square&logo=html5&logoColor=F0A500)

**AI / ML & data**<br/>
![PyTorch](https://img.shields.io/badge/PyTorch-0d1117?style=flat-square&logo=pytorch&logoColor=F0A500)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0d1117?style=flat-square&logo=scikitlearn&logoColor=F0A500)
![PySpark](https://img.shields.io/badge/PySpark-0d1117?style=flat-square&logo=apachespark&logoColor=F0A500)
![sentence-transformers](https://img.shields.io/badge/sentence--transformers-0d1117?style=flat-square&logo=huggingface&logoColor=F0A500)
![Gemini API](https://img.shields.io/badge/Gemini%20API-0d1117?style=flat-square&logo=googlegemini&logoColor=F0A500)
![OpenCV](https://img.shields.io/badge/OpenCV-0d1117?style=flat-square&logo=opencv&logoColor=F0A500)
![NumPy](https://img.shields.io/badge/NumPy-0d1117?style=flat-square&logo=numpy&logoColor=F0A500)
![pandas](https://img.shields.io/badge/pandas-0d1117?style=flat-square&logo=pandas&logoColor=F0A500)

**Apps, data & tooling**<br/>
![Streamlit](https://img.shields.io/badge/Streamlit-0d1117?style=flat-square&logo=streamlit&logoColor=F0A500)
![Django](https://img.shields.io/badge/Django-0d1117?style=flat-square&logo=django&logoColor=F0A500)
![MySQL](https://img.shields.io/badge/MySQL-0d1117?style=flat-square&logo=mysql&logoColor=F0A500)
![SQLite](https://img.shields.io/badge/SQLite-0d1117?style=flat-square&logo=sqlite&logoColor=F0A500)
![pytest](https://img.shields.io/badge/pytest-0d1117?style=flat-square&logo=pytest&logoColor=F0A500)
![Git](https://img.shields.io/badge/Git-0d1117?style=flat-square&logo=git&logoColor=F0A500)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-0d1117?style=flat-square&logo=githubactions&logoColor=F0A500)
![Jupyter](https://img.shields.io/badge/Jupyter-0d1117?style=flat-square&logo=jupyter&logoColor=F0A500)

---

## Certifications

- Cybersecurity Analyst Job Simulation — Tata (Forage), 2024
- Introduction to Front-End & Back-End Development — Meta (Coursera), 2023
- Getting Started with Python — Coursera, 2023
- Design Thinking: A Primer — NPTEL, IIT Madras
- Problem Solving — HackerRank, 2024
- Gen-AI Study Jams — Google Developer Groups, 2025

**Languages:** English, Kannada, Hindi, Telugu, Tamil, German (A1)

---

<div align="center">

Open to UK placement opportunities in AI/ML, data science and Python development.<br/>
The best way to reach me is by [email](mailto:gauravsaimeena@gmail.com) or [LinkedIn](https://www.linkedin.com/in/gaurav-manju/).

</div>
