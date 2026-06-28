# 🩺 AI Disease Diagnosis System

An AI-powered web application that predicts possible diseases based on the symptoms entered by the user. The project uses Machine Learning to provide quick and accurate disease predictions.

Features
- User Registration & Login
- Symptom-based Disease Prediction
- AI/ML Model Integration
- Diagnosis History
- Responsive User Interface

Tech Stack
- Backend: Django, Django REST Framework
- Frontend: HTML, CSS, JavaScript, Bootstrap
- Machine Learning: Scikit-learn, Pandas, NumPy
- Database: SQLite

 Installation

bash
git clone https://github.com/mailasaleem09/ai-project.git

cd ai-disease-diagnosis

python -m venv venv

Activate virtual environment
Windows
venv\Scripts\activate

Install dependencies
pip install -r requirements.txt

python manage.py migrate

python manage.py runserver
```

Open your browser and visit:

```
http://127.0.0.1:8000/
```

Project Structure

AI-Disease-Diagnosis
├── accounts/
├── diagnosis/
├── ml_model/
├── templates/
├── static/
├── manage.py
├── requirements.txt
└── README.md


 Future Improvements
- Doctor recommendations
- PDF reports
- Multi-language support
- prediction graph

License
This project is for educational purposes.
