
# MoodLens 🎭
**A Web-Based Sentiment Analysis Tool**

MoodLens is a web-based application that detects sentiment from user-submitted text using a machine learning model. Whether it’s a tweet, a review, or just a random thought, MoodLens helps determine if it carries a *Positive* or *Negative* tone.

---

## 💡 Features

- 🔍 Text sentiment analysis powered by Machine Learning
- ⚙️ Flask-powered backend
- 🖥️ Clean and responsive UI using HTML & CSS
- ✅ Real-time predictions with no page reload
- 📦 Lightweight and easy to deploy

---

## 📁 Project Structure

```
MoodLens/
├── templates/
│   └── index.html            # Web interface
├── sentiment.ipynb           # Notebook for model training
├── sentiment_analysis.csv    # Dataset used for training
├── app.py                    # Flask application logic
├── sentiment_model.pkl       # Trained ML model (Naive Bayes)
└── README.md                 # Project documentation          <-- (You're here)
```

---

## 📊 Model Details

- **Algorithm**: Multinomial Naive Bayes
- **Dataset**: Cleaned text sentiment dataset (sentiment_analysis.csv)
- **Tech Stack**: Python, scikit-learn, Flask, HTML/CSS
- **Preprocessing**: Tokenization, vectorization, stop-word removal
- **Output**: Prediction — *Positive* or *Negative*

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.x   (Here I have used -- Python 3.11.0)
- `pip` (Python package manager)

### 🧰 Installation & Usage

1. **Clone the repository**
```bash
git clone https://github.com/TechVoyager-rup/MoodLens.git
cd MoodLens
```

2. **(Optional) Create a virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install required libraries**
```bash
pip install flask scikit-learn pandas
```

4. **Run the Flask app**
```bash
python app.py
```

5. **View in your browser**
```
http://localhost:5001
```

---

## 🖼 UI Preview

```text
+----------------------------------------------+
|                MoodLens                      |
|     See your message through a lens          |
|                                              |
|   [ Enter your text here... ]                |
|                                              |
|             [Analyze Sentiment]              |
|        =>  Positive / Negative               |
+----------------------------------------------+
```

---

## 🔮 Future Enhancements

- Support for neutral sentiment
- Expand to emotion recognition (joy, anger, sadness, etc.)
- Language detection & multi-lingual support
- Dockerized deployment & CI/CD integration

---

## 👨‍💻 Author

**Rupanjan Ghosh**  
📧 rupanjanghosh100@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/rupanjan-ghosh)  
💻 [GitHub](https://github.com/TechVoyager-rup)

---

## 🙏 Acknowledgements

- [Flask](https://flask.palletsprojects.com/)
- [Scikit-learn](https://scikit-learn.org/)
- [Google Fonts](https://fonts.google.com/)
- UI inspired by minimal clean design concepts

---
