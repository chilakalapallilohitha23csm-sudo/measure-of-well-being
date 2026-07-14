# 🌍 A Comprehensive Measure of Well-Being

> An interactive Human Development Index (HDI) prediction and recommendation platform that evaluates a country's level of development using key socio-economic indicators and provides actionable insights for improvement.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

---

## 📖 Overview

**A Comprehensive Measure of Well-Being** is an interactive web application that predicts the **Human Development Index (HDI)** of a country or hypothetical scenario based on three internationally recognized development indicators:

- 🌱 Life Expectancy
- 🎓 Years of Schooling
- 💰 Gross National Income (GNI) per Capita (PPP)

The application calculates the HDI score in real time and classifies it into one of the official UNDP Human Development categories:

- 🟢 Very High
- 🔵 High
- 🟡 Medium
- 🔴 Low

Beyond prediction, the platform intelligently recommends the **most impactful indicator** to improve in order to reach the next HDI tier.

---

## 🚀 Live Demo link: https://project-apsche.onrender.com/

**Project Demo**

https://1drv.ms/v/c/877c79faa9c98b23/IQCksyjfIaSPSalNHhIL6RfeAYQmfMo0gksRGSGkP8un7QI?e=KRoYDh

> **Note:** Free hosting services may take **30–50 seconds** to wake up after inactivity.

---

## 💻 Source Code

GitHub Repository

https://github.com/Haradevsrujan/A-Comprehensive-Measure-of-Well-Being

---

# ✨ Features

✅ Real-time HDI Prediction

- Predicts HDI Score instantly.
- Classifies development level.

---

✅ Interactive Dashboard

- Live slider controls
- Instant score updates
- No page refresh required

---

✅ HDI Visualization

- Color-coded HDI spectrum
- Progress indicator
- Official UNDP thresholds

---

✅ Index Breakdown

Displays

- Life Expectancy Index
- Education Index
- Income Index

---

✅ Smart Recommendation System

Automatically

- Detects the weakest indicator
- Suggests the next improvement target
- Calculates the exact value required to move to the next HDI tier

---

✅ Clean User Interface

- Responsive Design
- Modern Layout
- Easy Navigation
- Lightweight

---

# 🛠️ Tech Stack

## Frontend

- HTML5
- CSS3
- JavaScript (ES6)

## Proposed Backend

- Python
- Flask / FastAPI
- Scikit-learn
- Pandas
- NumPy
- Pickle / Joblib

---

# 📂 Project Structure

```text
A-Comprehensive-Measure-of-Well-Being/
│
├── index.html
├── docs/
│   ├── Solution_Requirements.pdf
│   ├── Problem_Solution_Fit.pdf
│   ├── Proposed_Solution.pdf
│   ├── Solution_Architecture.pdf
│   └── Project_Planning.pdf
│
├── README.md
└── assets/
    └── screenshots/
```

---

# 📊 Input Parameters

The prediction model requires three inputs:

| Parameter | Description |
|-----------|-------------|
| 🌱 Life Expectancy | Average life expectancy at birth (Years) |
| 🎓 Years of Schooling | Mean & Expected Years of Schooling |
| 💰 GNI per Capita | Gross National Income (PPP US$) |

---

# 📈 Output

The application generates:

- HDI Score (0–1)
- Development Category
- Life Expectancy Index
- Education Index
- Income Index
- Improvement Recommendation
- Required Target Value
- HDI Progress Visualization

---

# ⚙️ Methodology

The application follows the **United Nations Development Programme (UNDP)** Human Development Index methodology.

### Step 1

Normalize each indicator using official UNDP minimum and maximum values.

### Step 2

Compute

- Life Expectancy Index
- Education Index
- Income Index

### Step 3

Calculate the final HDI score using the **Geometric Mean**.

### Step 4

Classify the score according to UNDP thresholds.

| HDI Score | Category |
|-----------|----------|
| ≥ 0.800 | Very High |
| 0.700 – 0.799 | High |
| 0.550 – 0.699 | Medium |
| < 0.550 | Low |

---

# 🔮 Future Enhancements

- Machine Learning based prediction model
- Historical country-wise HDI analysis
- Interactive visual dashboards
- Country comparison module
- Data export (PDF/CSV)
- AI-powered recommendations
- Cloud deployment
- REST API Integration

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/Haradevsrujan/A-Comprehensive-Measure-of-Well-Being.git
```

## Navigate to Project

```bash
cd A-Comprehensive-Measure-of-Well-Being
```

## Run Locally

Simply open

```text
index.html
```

or start a local server

```bash
python -m http.server
```

Visit

```
http://localhost:8000
```

---

# 📸 Screenshots

## 🏠 Home Page

> <img width="1192" height="641" alt="image" src="https://github.com/user-attachments/assets/4e618bd3-78aa-48fc-bce3-fb464cf97506" />


---

## 📊 Prediction Dashboard

> <img width="968" height="434" alt="image" src="https://github.com/user-attachments/assets/560f1c84-b26e-4da9-ac7a-a24b3cd229cc" />


---

## 💡 Recommendation Result

> <img width="478" height="194" alt="image" src="https://github.com/user-attachments/assets/d6a538c6-a6cc-4dc5-93d1-41e0420211eb" />


---

## 📈 HDI Visualization

> <img width="242" height="215" alt="image" src="https://github.com/user-attachments/assets/a87b59f0-b48c-4dc0-bb09-cdb926fe9769" />


---

# 👨‍💻 Author

### **Lohitha Chilakalapalli**

Github

https://github.com/chilakalapallilohitha23csm-sudo/measure-of-well-being.git

---

# 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork this repository and submit a pull request.

---

# 📜 License

This project is developed for academic and educational purposes.

---

# ⭐ Support

If you found this project useful,

⭐ **Give this repository a Star!**

It helps others discover the project and motivates future improvements.

---

## 🙌 Acknowledgements

- United Nations Development Programme (UNDP)
- Human Development Report Methodology
- Open-source web development community

---

> **A Comprehensive Measure of Well-Being** — Leveraging technology to make Human Development insights more accessible, interactive, and actionable.
