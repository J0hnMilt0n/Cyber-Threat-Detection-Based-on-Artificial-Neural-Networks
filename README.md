# Cyber-Threat-Detection-Based-on-Artificial-Neural-Networks

This project uses deep learning models like **LSTM** and **CNN** to identify and classify cyber threats in financial institution datasets. It also compares performance with traditional ML models like **SVM**, **KNN**, **Decision Tree**, **Random Forest**, and **Naïve Bayes**.

---

## 💡 Features
- 🧠 Deep Learning (CNN & LSTM) for cyber threat detection  
- 🛡️ Traditional ML algorithms for performance comparison  
- 📊 Accuracy, Precision, Recall, and F-Measure graphs  
- 🗂️ GUI-based interaction using **Tkinter**  
- ⚙️ Preprocessing using TF-IDF vectorization  
- 📁 Dataset parsing and event profiling  

---

## 🛠️ Tech Stack
- Python  
- Tkinter  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib  
- Pyswarms  
- Pandas / NumPy  

---

## 📁 Project Structure

```

CyberThreatDetection/
├── CyberThreatDetection.py       # Main GUI application
├── test.py                       # Standalone test for SVM
├── run.bat                       # Windows launcher
├── report.log                    # Execution log
├── SCREENSHOTS.docx              # UI walkthrough
├── datasets/                     # Folder for datasets (e.g., kdd\_train.csv)
└── README.md                     # This file

````

---

## ▶️ How to Run

1. 🔧 Install required libraries:
```bash
pip install -r requirements.txt
````

2. 🚀 Launch the GUI:

```bash
python CyberThreatDetection.py
```

3. 👇 Follow GUI buttons in order:

* Upload Train Dataset
* Run Preprocessing TF-IDF Algorithm
* Generate Event Vector
* Neural Network Profiling (runs LSTM and CNN)
* Run other algorithms (SVM, KNN, etc.)

---

## 📊 Evaluation Metrics

Each model is evaluated based on:

* Accuracy
* Precision
* Recall
* F-Measure

📉 Visual comparisons are shown using bar graphs in the GUI.

---

## 🖼️ Demo Screenshots

Screenshots included in: `SCREENSHOTS.docx`

---

## 👩‍💻 Author

**Mareddy Bhuvana Kruthi**
*AI & Security Enthusiast* 
This project demonstrates intelligent threat detection using deep learning for real-time cybersecurity monitoring in financial systems.

