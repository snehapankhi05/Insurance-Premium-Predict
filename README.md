# Insurance Prediction System 🏥📊

An end-to-end Machine Learning project that predicts insurance-related outcomes using structured user inputs.  
The project focuses on clean code organization, model inference, and practical ML workflow rather than just raw accuracy.

---

## 🚀 Project Overview

This project uses a trained Machine Learning model to make insurance predictions based on user-provided inputs such as demographic and location-related features.

### Key focus areas:
- Clean ML pipeline
- Model loading and inference
- Input and output schema handling
- Production-style project structure

---

## 🧠 Machine Learning Approach

- **Problem Type:** Supervised learning (Regression)
- **Model:** Pre-trained ML model (`model.pkl`)
- **Data Processing:** Completed during the training phase
- **Inference:** Handled via a separate prediction module
- **Validation:** Train/Test split with standard regression metrics

### 📊 Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

These metrics were used to evaluate generalization performance on unseen data.

---

## 🗂️ Project Structure

insurance-prediction/
│
├── config/
│ └── city_tier.py # City classification logic
│
├── model/
│ ├── model.pkl # Trained ML model
│ └── predict.py # Prediction logic
│
├── schema/
│ ├── user_input.py # Input schema definition
│ └── prediction_response.py # Output schema definition
│
├── app.py # Main application file
├── requirements.txt
├── README.md
├── .gitignore

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/insurance-prediction.git
cd insurance-prediction
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run the Application
python app.py
Ensure Python 3.8 or higher is installed.

🧩 Key Learnings
Structuring an ML project for real-world usage

Separating configuration, schema, and model logic

Loading and using trained models safely

Writing readable and maintainable ML code

📌 Notes
This project is intended for learning and demonstration purposes.

Model performance depends on the quality and distribution of the training data.

Future improvements may include advanced models and better feature engineering.

👩‍💻 Author
Khush
B.E. Computer Science Engineering (AI & ML)
India


---