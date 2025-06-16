# 🌾 Crop Yield Prediction Project

This project aims to predict crop yield using machine learning models trained on agricultural data. It includes a web application built with Flask to allow users to input parameters and receive crop yield predictions.

---

## 📁 Project Structure

```
├── .idea/                     # IDE configuration (ignore)
├── .ipynb_checkpoints/       # Jupyter notebook backups
├── .venv/                    # Virtual environment
├── templates/                # HTML templates for Flask app
├── app.py                    # Flask web app
├── crop yield prediction.ipynb # Jupyter notebook for model building
├── dtr.pkl                   # Trained Decision Tree Regressor model
├── preprocessor.pkl          # Preprocessing pipeline (e.g., encoding, scaling)
├── yield_df.csv              # Dataset used for training/testing
```

---

## 🛠️ How to Run the Project

1. **Clone the repository** or download the files.

2. **Set up virtual environment (optional but recommended):**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # or .venv\Scripts\activate on Windows
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask app:**
   ```bash
   python app.py
   ```

5. **Open the browser and go to:**
   ```
   http://127.0.0.1:5000/
   ```

---

## 📊 Model Overview

- **Algorithm Used:** Decision Tree Regressor
- **Data Preprocessing:** Handled via `preprocessor.pkl`
- **Input Features:** Based on the dataset in `yield_df.csv`
- **Output:** Predicted yield value for given input parameters

---

## 📓 Jupyter Notebook

- `crop yield prediction.ipynb` contains:
  - EDA (Exploratory Data Analysis)
  - Data cleaning and preprocessing
  - Model training and evaluation
  - Saving models using `joblib` or `pickle`

---

## 🧪 Sample Input (via Web App)

- Region
- Crop type
- Rainfall
- Temperature
- Soil type

---

## 📂 Dependencies

See `requirements.txt` for full list.

---

## 💡 Future Improvements

- Add support for more ML models (Random Forest, XGBoost, etc.)
- Deploy to cloud (Heroku, Render, etc.)
- Improve UI/UX with frontend frameworks

---

## 👨‍💻 Author

Sharma Ritvik  
Email: sharmaritvik031@gmail.com  


