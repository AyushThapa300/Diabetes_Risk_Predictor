# 🩺 Diabetes Risk Predictor

An interactive web-based ML health screening tool that estimates a user's
risk of developing Type 2 diabetes using a logistic-regression–style
weighted scoring model.

![Demo Screenshot](assets/SS4.jng)

## 🔗 Live Demo
[Click here to view the live app](https://YOUR_USERNAME.github.io/diabetes-risk-predictor)

## 🧠 How It Works

The model scores 9 clinical and lifestyle features based on weights derived
from the Finnish Diabetes Risk Score (FINDRISC) and epidemiological research:

| Feature | Weight Basis |
|---|---|
| Age | Risk rises sharply after 45 |
| BMI & waist circumference | Visceral fat drives insulin resistance |
| Fasting blood glucose | Primary biomarker (100–125 mg/dL = pre-diabetes) |
| Blood pressure | Hypertension and T2D are strongly co-morbid |
| Family history | Genetic predisposition (~30–50% of risk) |
| Physical activity & diet | Most actionable lifestyle levers |

A final risk score (0–100) is computed and mapped to four risk tiers:
Low, Moderate, High, and Very High.

## 🚀 Features
- Real-time risk assessment with interactive sliders
- Visual risk meter with needle indicator
- Per-factor breakdown (green / amber / red)
- Personalized health tips based on risk tier
- Fully client-side — no data leaves your browser

## 🛠️ Tech Stack
- HTML5 / CSS3 / Vanilla JavaScript
- Logistic-regression–style scoring model
- No external dependencies or frameworks

## 📊 Future Improvements
- [ ] Train on real Pima Indians Diabetes Dataset (UCI ML Repo)
- [ ] Export model to ONNX and run via `onnxruntime-web`
- [ ] Add HbA1c input (gold-standard biomarker)
- [ ] Dark mode support
- [ ] Mobile-responsive layout

## ⚕️ Disclaimer
This tool is for **educational purposes only** and does not constitute
medical advice. Always consult a qualified healthcare professional.

## 📄 License
MIT License — free to use and modify.
