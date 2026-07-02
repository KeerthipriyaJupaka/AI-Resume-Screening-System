# 🤖 AI Resume Screening System

An AI-powered Resume Screening System that automates candidate evaluation using Machine Learning. The system analyzes resume-related features, predicts interview eligibility, and helps recruiters efficiently shortlist candidates based on their qualifications and skills.

---

## 📌 Features

- 📄 Resume data preprocessing
- 🤖 Machine Learning-based interview prediction
- 📊 Candidate evaluation and scoring
- 🧠 Automatic categorical data encoding
- 📈 Model training using Random Forest Classifier
- 💾 Model saving with Joblib
- 📋 Resume screening workflow
- 🚀 Easy to extend with PDF resume parsing and skill extraction

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Google Colab / Jupyter Notebook
- Streamlit (Optional for Web Application)

---

## 📂 Project Structure

```
AI-Resume-Screening-System/
│
├── dataset/
│   └── AI_Resume_Screening_Job_Market_Dataset_2026.csv
│
├── models/
│   ├── model.pkl
│   └── encoders.pkl
│
├── train_model.py
├── predict.py
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 📊 Dataset

The dataset contains candidate information including:

- Candidate ID
- Job Title
- Industry
- Experience
- Education Level
- Skills Match Score
- Resume Score
- Location Type
- Salary Range
- AI Screening Result
- Interview Call
- Job Market Demand
- Year

---

## ⚙️ Machine Learning Workflow

1. Load Dataset
2. Data Preprocessing
3. Label Encoding
4. Feature Selection
5. Train-Test Split
6. Random Forest Model Training
7. Interview Prediction
8. Model Evaluation
9. Save Trained Model

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/AI-Resume-Screening-System.git
```

Move into the project directory

```bash
cd AI-Resume-Screening-System
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Train the model

```bash
python train_model.py
```

Run the Streamlit application

```bash
streamlit run app.py
```

---

## 📈 Model

Algorithm Used:

- Random Forest Classifier

Evaluation Metrics:

- Accuracy
- Confusion Matrix
- Classification Report

---

## 📷 Output

The application predicts whether a candidate is likely to receive an interview call based on resume-related features.

Example Output:

```
Prediction:
Interview Call = Yes
```

---

## 🔮 Future Enhancements

- Resume PDF Upload
- NLP-based Skill Extraction
- ATS Score Calculation
- Resume Ranking
- Recruiter Dashboard
- Candidate Recommendation System
- Deep Learning Models
- Explainable AI (XAI)

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push to your branch.
5. Open a Pull Request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Keerthipriya**
**Varshitha**
**Rithika**
**Akshitha**

B.Tech Computer Science Engineering

Machine Learning | Artificial Intelligence | Data Science Enthusiast

---

⭐ If you found this project helpful, consider giving it a star on GitHub.
