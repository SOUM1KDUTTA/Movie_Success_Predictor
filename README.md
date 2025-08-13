
# 🎬 Movie Success Predictor

An interactive **Streamlit web app** that predicts whether a movie will be a **Hit** or **Flop** based on key factors like budget, genre, director score, and marketing spend.

🔗 **Live App:** [Movie Success Predictor](https://moviesuccesspredictor-x4ezpjcqwefgffet3bpfld.streamlit.app/)
📂 **GitHub Repo:** [Movie\_Success\_Predictor](https://github.com/SOUM1KDUTTA/Movie_Success_Predictor)

---

## 🚀 Features

* **User-friendly UI** built with Streamlit.
* **Real-time prediction** using a trained Random Forest model.
* Inputs include:

  * 🎭 Genre
  * 💰 Budget (in million \$)
  * 🎬 Director Score
  * ⏱ Runtime
  * 🌟 Cast Popularity
  * 📅 Release Month
  * 📢 Marketing Spend
  * 🔄 Sequel or not
* Displays prediction instantly as **Hit 🎉** or **Flop ❌**.

---

## 🛠 Tech Stack

* **Frontend:** [Streamlit](https://streamlit.io/)
* **Backend Model:** [Scikit-learn](https://scikit-learn.org/)
* **Data Handling:** [Pandas](https://pandas.pydata.org/)
* **Serialization:** [Joblib](https://joblib.readthedocs.io/)

---

## 📂 Project Structure

```
Movie_Success_Predictor/
│
├── Movie/
│   ├── app.py              # Streamlit app
│   ├── data/
│   │   └── movies_100k.csv # Dataset
│   └── src/
│       ├── model.py        # Training and prediction functions
│       └── preprocess.py   # Preprocessing functions
│
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## 📊 Dataset

The dataset (`movies_100k.csv`) contains:

* Movie metadata
* Financial stats
* Popularity scores
  Used to train the **Random Forest Classifier**.

---

## ⚙️ How to Run Locally

1. **Clone the repository**:

   ```bash
   git clone https://github.com/SOUM1KDUTTA/Movie_Success_Predictor.git
   cd Movie_Success_Predictor/Movie
   ```

2. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**:

   ```bash
   streamlit run app.py
   ```

4. Open the link shown in the terminal.

---

## 📦 Model Training

The model is trained using:

* **RandomForestClassifier** from scikit-learn
* Data preprocessing (scaling, label encoding) in `preprocess.py`
* Saved as `model.pkl` along with `scaler.pkl` and `label_enc.pkl` for later predictions.

---



## 🧑‍💻 Author

**Soumik Dutta**
📧 Contact: (hcssoumikdutta16@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/soum1kdutta/)

---


