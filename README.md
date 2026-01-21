# Insurance Premium Prediction API 🚀
**FastAPI + Machine Learning | Real-Time Premium Prediction**

A Machine Learning project that predicts **insurance premium** based on user inputs.  
Built using **FastAPI** to serve the ML model as a REST API.

---

## ✨ Features
- ✅ FastAPI-based REST API
- ✅ Real-time insurance premium prediction
- ✅ Clean project structure (config, schema, model)
- ✅ Model saved using `pickle`
- ✅ Input validation using Pydantic

---

## 🛠 Tech Stack
- **Python**
- **FastAPI**
- **Scikit-learn**
- **Pydantic**
- **Uvicorn**

---

## 📂 Project Structure
```txt
Insurance-Premium-Predict/
│── config/
│── model/
│── schema/
│── .gitignore
│── README.md



---

## ⚙️ Setup & Run Locally

### 1️⃣ Clone the repository
```bash
git clone https://github.com/snehapankhi05/Insurance-Premium-Predict.git
cd Insurance-Premium-Predict

2️⃣ Create virtual environment
python -m venv myenv
myenv\Scripts\activate

3️⃣ Install dependencies
pip install -r model/requirements.txt

4️⃣ Run the FastAPI server
uvicorn schema.app:app --reload

🔥 API Documentation (Swagger UI)

Open:

http://127.0.0.1:8000/docs

👩‍💻 Author

Sneha Pankhi
GitHub: https://github.com/snehapankhi05

⭐ If you like this project, don’t forget to star the repository!
