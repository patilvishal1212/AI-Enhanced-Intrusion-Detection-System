🛡 AI-Enhanced Intrusion Detection System (IDS)
Real-Time Cyber Threat Detection Using Machine Learning
👨‍💻 Developed by: Avinash Bhojane

📌 Project Overview
In today’s hyper-connected digital world, ensuring the security of critical infrastructure and sensitive data has become more vital than ever. This project is a fully functional AI-Enhanced Intrusion Detection System (IDS) developed by Avinash Bhojane, which leverages machine learning to detect, classify, and respond to network-based cyber threats in real time.

The system integrates Random Forest Classification, SMOTE-based data balancing, and a responsive web interface built with Flask — forming a powerful, intelligent IDS for modern organizational security.

🖼 Output Screenshots
🔹 ![Landing Page](<CYBER_PROJECT/templates/Landing page.png>)

🔹 ![Detection Result](<CYBER_PROJECT/templates/Result 1.png>)

🔹 ![ Detection Result](<CYBER_PROJECT/templates/Result 2.png>)

🛠️ Technologies Used
Python 3.10+ – Core programming language

Flask – Lightweight Python web framework

HTML / CSS – For frontend user interface

Pandas / NumPy – Data preprocessing and manipulation

Scikit-learn – Machine Learning framework

Imbalanced-learn (SMOTE) – To balance the dataset

Joblib – Model saving and loading

🧠 Machine Learning Model Details
The AI model used is a Random Forest Classifier, trained on a well-labeled and balanced network intrusion dataset. Using SMOTE (Synthetic Minority Oversampling Technique), the dataset is adjusted to address class imbalance.

The trained model is saved as:

bash
random_forest_model_4_features.joblib
📁 Project Directory Structure
bash
AI-ENHANCED-INTRUSION-DETECTION/
├── CYBER_PROJECT/
│   ├── templates/
│   │   └── index.html                      # Frontend web template
│   ├── app.py                              # Flask backend server
│   ├── random_forest_model_4_features.joblib
│   ├── web_attacks_balanced.csv           # Cleaned dataset
│   ├── requirment.txt                      # Python dependencies
│   ├── Untitled.ipynb                      # Model training & EDA notebook
│   └── README.md                           # Project guide
├── Documentation/
└── README.md 
⚙️ Installation & Setup Instructions
✅ Using Conda (Recommended)
bash
conda create -n cyber_ids python=3.10
conda activate cyber_ids
git clone https://github.com/your-username/AI-Enhanced-Intrusion-Detection-System.git
cd CYBER_PROJECT
pip install -r requirment.txt

✅ Using Python Virtual Environment
bash
python -m venv ids_env

# Activate:
ids_env\Scripts\activate        # Windows
source ids_env/bin/activate     # macOS/Linux

pip install -r requirment.txt
🚀 Running the Application
bash
cd CYBER_PROJECT
python app.py
Then open in browser:
http://127.0.0.1:5000

📊 Dataset Overview
The web_attacks_balanced.csv dataset includes labeled records of network activity categorized into normal traffic and various intrusion types, making it ideal for classification tasks.

✅ Conclusion
This project demonstrates how artificial intelligence and machine learning can be applied effectively in the cybersecurity domain to build real-time Intrusion Detection Systems.

By integrating a powerful ML classifier, an interactive web interface, and a balanced dataset, the system offers a scalable solution for modern-day network threat detection — enhancing the overall cyber defense posture of any organization.

🔒 Built with passion for cybersecurity by Avinash Bhojane – combining ML with real-world threat intelligence.