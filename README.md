
---

# 👟 Shoe Size Prediction App

This project is a **machine learning web application** that predicts a person’s shoe size based on their **age, height, and gender**.
It is built with **Python, Scikit-learn, and Streamlit** for deployment.

---

## 🚀 Features

* Collects user input (age, height, gender) through a simple interface.
* Uses a **trained regression model** to predict shoe size.
* Provides **visualizations** of data (Seaborn/Matplotlib).
* Interactive **Streamlit web app** that runs locally or can be deployed online.

---

## 🛠️ Tech Stack

* **Python 3.x**
* **Scikit-learn** – machine learning model training
* **Pandas & NumPy** – data handling
* **Matplotlib & Seaborn** – data visualization
* **Streamlit** – web app deployment

---

## 📂 Project Structure

```
shoe-size-prediction/
│── assets/               # saved model and plots
│── app/                  # Streamlit app files
│── notebooks/            # Jupyter notebooks (data exploration, training)
│── requirements.txt      # dependencies
│── README.md             # project documentation
│── shoe_model.pkl        # trained ML model
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/shoe-size-prediction.git
   cd shoe-size-prediction
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   # Windows
   .venv\Scripts\activate
   # Mac/Linux
   source .venv/bin/activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the app:

   ```bash
   streamlit run app/app.py
   ```

---

## 📊 Example

Input:

* Age: 20
* Height: 170 cm
* Gender: Male

Output:

* Predicted Shoe Size: **42**

---

## 🔮 Future Improvements

* Add more features (e.g., weight, country).
* Improve accuracy with advanced ML models.
* Deploy on **Hugging Face Spaces**.

---

## 🤝 Contributing

Contributions are welcome! Please fork this repo and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---
# 👟 Shoe Size Prediction App  
🔗 [Live Demo on Streamlit Cloud](https://shoesizeapp.streamlit.app/)






