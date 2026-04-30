<div align="center">

# 🚗 Car Price Prediction App

### Predict the market value of any car — instantly, accurately, and for free.

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Click_Here-00C853?style=for-the-badge)](https://ammarahmed-git.github.io/Portfolio)

<br/>

> **Enter car details. Get an instant price prediction. No signup, no wait.**

<br/>


</div>

---

## ✨ What It Does

Ever wondered what a used car is actually worth? This app uses a trained **Machine Learning model** to predict the fair market price of a car based on real-world features — brand, model, year, mileage, fuel type, and more.

No guessing. No haggling blindly. Just data-driven predictions in seconds.

---

## 🎯 Features

- 🔮 **Instant Price Prediction** — get results the moment you hit predict
- 🧠 **ML-Powered** — trained on real car market data using Scikit-Learn
- 📊 **Smart Encoding** — handles categorical features like brand, fuel type & transmission automatically
- 🖥️ **Clean UI** — built with Streamlit for a smooth, no-friction experience
- ☁️ **Cloud Deployed** — live and accessible from any device, no installation needed

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend & UI | Streamlit |
| ML Model | Scikit-Learn |
| Data Processing | Pandas |
| Model Serialization | Pickle |
| Language | Python 3.10+ |
| Deployment | Streamlit Cloud |

---

## 🚀 Getting Started

### Run it locally in 3 steps

**1. Clone the repository**
```bash
git clone https://github.com/Ammarahmed-git/Car_Price_Pediction_App.git
cd Car_Price_Pediction_App
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Launch the app**
```bash
streamlit run app.py
```

The app will open at `http://localhost:8501` 🎉

---

## 📁 Project Structure

```
Car_Price_Pediction_App/
│
├── app.py                  # Main Streamlit application
├── model.pkl               # Trained ML model (serialized)
├── requirements.txt        # Project dependencies
└── README.md               # You are here
```

---

## 🧠 How the Model Works

```
Raw Car Data  ──►  Label Encoding  ──►  ML Model  ──►  Predicted Price
  (user input)     (categorical         (trained on       (PKR / USD)
                    features)            real data)
```

1. User inputs car details through the Streamlit UI
2. Categorical fields (brand, fuel type, transmission) are encoded using `LabelEncoder`
3. The trained model processes the encoded features
4. A predicted price is returned instantly

---

## 📦 Dependencies

```
streamlit
pandas
scikit-learn
```

---

## 👨‍💻 About the Developer

Built by **Ammar Ahmed** — CS Graduate, Full-Stack Developer & AI/ML Enthusiast from Karachi, Pakistan 🇵🇰

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-purple?style=flat-square)](https://ammarahmed-git.github.io/Portfolio)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github)](https://github.com/Ammarahmed-git)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://pk.linkedin.com/in/ammar-ahmed-1606a1242)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

**If this project helped you, drop a ⭐ — it means a lot!**

*Made with 💻 and a lot of chai ☕ by Ammar Ahmed*

</div>
