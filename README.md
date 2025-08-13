# Multiple Disease Prediction System using Machine Learning

## 📌 Overview
The **Multiple Disease Prediction System** is a web-based application that uses **Machine Learning** models to predict the likelihood of multiple diseases based on user-provided medical data.  
The project is built using **Python**, **Streamlit**, and **CNN-based ML models**, enabling real-time, interactive disease prediction for conditions such as **Diabetes, Heart Disease, and Cancer**.

---

## 🚀 Features
- **Multi-Disease Prediction** – Supports multiple diseases in a single platform.
- **User-Friendly Interface** – Built using Streamlit for quick, interactive results.
- **Real-Time Prediction** – Instant results based on user input.
- **ML Model Integration** – Pre-trained models for accurate predictions.
- **Data Preprocessing** – Cleansing and scaling to improve model performance.

---

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Framework:** Streamlit
- **Machine Learning:** Scikit-learn, TensorFlow/Keras (for CNN models)
- **Libraries:** Pandas, NumPy, Matplotlib, Pickle
- **Dataset Sources:** Public medical datasets (Kaggle, UCI Repository)

---

## 📂 Project Structure
MultipleDiseasePrediction/
│── datasets/ # Medical datasets for training
│── models/ # Trained ML model files (.pkl, .h5)
│── app.py # Streamlit application script
│── requirements.txt # Python dependencies
│── README.md # Project documentation
│── utils/ # Data preprocessing & helper functions


---

## ⚙️ Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/MultipleDiseasePrediction.git
   cd MultipleDiseasePrediction
   
2. **Install Dependencies**
   pip install -r requirements.txt

3. **Run the Application**
   streamlit run app.py
   
4.**Access in Browser**
  Open the local Streamlit URL (usually http://localhost:8501).

**📸 Screenshots**
<img width="500" height="1000" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/84ee993d-654a-406a-92a4-251d81e81dae" />

<img width="150" height="200" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/a9702689-d3c0-4ad2-96e0-ce42941fb887" />

<img width="150" height="200" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/8cf6d12f-ffa0-40e2-99c0-021708ded7eb" />






📊 Machine Learning Workflow
Data Collection – Gather datasets for each disease.
Data Preprocessing – Handle missing values, normalization, and encoding.
Model Training – Train separate models for each disease (Logistic Regression, CNN, Random Forest, etc.).
Model Saving – Store models as .pkl or .h5 files.
Integration with Streamlit – Load and run predictions based on user inputs.

