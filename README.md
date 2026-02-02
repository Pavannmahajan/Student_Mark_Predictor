# 📊 Student Marks Predictor

A Machine Learning web application that predicts student marks based on study hours using Linear Regression and Flask.



---

## 🎯 About The Project

This project predicts student performance (marks out of 100) based on the number of hours they study per day. It uses **Linear Regression** machine learning algorithm and is deployed as an interactive **Flask web application**.

**Key Features:**
- 🔮 Predicts marks with ~95% accuracy
- 🌐 User-friendly web interface
- ✅ Input validation (0-24 hours)
- 💾 Saves all predictions to CSV
- 📊 Built with real student data (200+ samples)

---

## 🛠️ Technologies Used

- **Python** - Programming language
- **Flask** - Web framework
- **scikit-learn** - Machine learning library
- **Pandas & NumPy** - Data processing
- **Matplotlib** - Data visualization
- **Joblib** - Model persistence

---

## 📁 Project Structure

```
Student_Mark_Predictor/
│
├── app1.py                          # Flask application
├── students_mark_predictor.ipynb    # Model training notebook
├── Desktop.pkl2                     # Trained ML model
├── student_info.csv                 # Training dataset
├── index.html                       # Web interface
└── requirements.txt                 # Dependencies
```

---

## 🚀 How To Run

### 1. Clone the repository
```bash
git clone https://github.com/Pavannmahajan/Student_Mark_Predictor.git
cd Student_Mark_Predictor
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Create templates folder
```bash
mkdir templates
move index.html templates/
```


### 4. Run the application
```bash
python app1.py
```

### 5. Open in browser
```
http://127.0.0.1:5000
```

---

## 💡 How To Use

1. Enter study hours (between 0-24) in the input field
2. Click **"Predict Marks"** button
3. See your predicted marks instantly!
4. All predictions are automatically saved

---

## 📊 Model Details

- **Algorithm:** Linear Regression
- **Dataset:** 200+ student records
- **Accuracy (R² Score):** ~0.95 (95%)
- **Features:** Study hours per day
- **Target:** Marks out of 100

### Model Equation:
```
Predicted Marks = 3.93 × Study Hours + 50.44
```

**Example:**
- Study 5 hours → Get ~70% marks
- Study 10 hours → Get ~90% marks

---

## 📸 Screenshots

*Web Interface:*

![Student Marks Predictor](https://via.placeholder.com/800x400?text=Add+Your+Screenshot+Here)

*Prediction Result:*

![Prediction](https://via.placeholder.com/800x400?text=Add+Your+Screenshot+Here)

---

## 🔮 Future Improvements

- [ ] Add more features (attendance, previous performance)
- [ ] Deploy on cloud (Heroku/AWS)
- [ ] Add data visualization dashboard
- [ ] Mobile app version
- [ ] Multiple ML algorithms comparison

---

## 👨‍💻 Author

**Pawan Bapu Mahajan**

- 📧 Email: pavanmahajan0707@gmail.com
- 🐙 GitHub: [@Pavannmahajan](https://github.com/Pavannmahajan)

---

## 🙏 Acknowledgments

- Dataset: Student performance data
- Inspiration: Real-world ML application
- Tools: scikit-learn, Flask, Python

---

## 📝 License

This project is open source and available for educational purposes.

---

⭐ **If you found this project helpful, please give it a star!** ⭐

---


