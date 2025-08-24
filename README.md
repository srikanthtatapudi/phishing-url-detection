# Phishing URL Detection System  

## 📌 Overview  
This project is a simple **Machine Learning-based Phishing URL Detection System** built using Python.  
It classifies URLs as **Legitimate** or **Phishing** using features like URL length and the number of special characters.  
The project comes with a sample dataset for quick testing and learning purposes.  

---

## 🚀 Features  
- Detects phishing URLs using simple URL characteristics  
- Uses **Random Forest Classifier** for training and prediction  
- Easy to extend with real-world phishing datasets  
- Beginner-friendly and ready to run  

---

## 🛠️ Tech Stack  
- **Python**  
- **Scikit-learn** – Machine Learning model  
- **Pandas** – Data handling  

---

## 📂 Project Structure  
Phishing-URL-Detection/
│-- phishing_detection.py # Main Python script
│-- README.md # Documentation file
│-- requirements.txt # Python dependencies

---

## ⚙️ Installation & Setup  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/your-username/phishing-url-detection.git
cd phishing-url-detection
```
2️⃣ Install dependencies
```
pip install -r requirements.txt
```
3️⃣ Run the project
```
python phishing_detection.py
```
📊 How It Works
Takes URL length and special character count as features

Trains a Random Forest Classifier on sample data

Predicts whether a new URL is Legitimate (0) or Phishing (1)

🖼️ Example Output
```

Accuracy: 1.0
Phishing
```
🔮 Future Enhancements
Add real phishing datasets for better accuracy

Add more URL-based features (HTTPS, IP address, etc.)

Build a simple Flask web app for real-time prediction

