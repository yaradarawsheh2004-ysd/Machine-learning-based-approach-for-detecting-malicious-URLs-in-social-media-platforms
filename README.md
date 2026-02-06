##Malicious URL Detection in Social Media Platforms

##Overview
This project focuses on securing social media platforms by detecting malicious URLs using machine learning techniques. With the rapid increase in online content sharing, attackers frequently spread harmful links disguised as shortened or deceptive URLs to facilitate phishing, malware downloads, or unauthorized data collection. This study develops an intelligent, lightweight ML-based detection model that analyzes URL properties to provide a proactive defense mechanism.

##Key Features

Proactive Defense: Identifies new (zero-day) attacks that traditional blacklist methods might miss.

Efficient Analysis: Analyzes lexical and structural properties (e.g., length, domain structure, special characters) without needing to inspect page content.

High Performance: Achieves high detection accuracy with low false-positive rates.

Real-time Potential: Designed as a lightweight tool suitable for fast processing in dynamic social media environments.

##Methodology & Dataset
The model was trained on a comprehensive dataset (over 200,000 URLs) combined from trusted sources like PhishTank, the UNB URL dataset, and URLs directly collected from social media platforms.

##Features Extracted:

1- Lexical Features: URL length, presence of digits, special characters, and subdomain count.

2- Structural Features: Domain registration details and path patterns.

##Algorithms & Experimental Results
We evaluated multiple Machine Learning and Deep Learning models to determine the most effective classifier. Random Forest emerged as the top performer.
Model,Accuracy,F1-Score,AUC
Random Forest (RF),96%,0.96,0.98
XGBoost (XGB),94%,0.94,0.975
Support Vector Machine (SVM),93%,0.93,0.96
Logistic Regression (LR),88%,0.88,0.92
Decision Tree (DT),87%,0.87,0.90

##Implementation Details

Language: Python 

Key Libraries: Scikit-learn, Pandas, NumPy, XGBoost 

Hardware Used: Tested on a system with Intel Core i7 and 16GB RAM

##How to Use
Clone the Repository:
git clone https://github.com/yaradarawsheh2004-ysd/Malicious-URL-Detection.git](https://github.com/yaradarawsheh2004-ysd/Machine-learning-based-approach-for-detecting-malicious-URLs-in-social-media-platforms.git
Install Dependencies:
pip install -r requirements.txt
Run the Application: Activate your environment and run the server to access the detection tool via localhost

##Conclusion
The results demonstrate that ensemble-based models like Random Forest are highly effective for real-time malicious URL detection, offering a superior balance between performance, speed, and interpretability.

##Project Team

Author: Yara Darawsheh  & Salam Metleq
Supervisors: Prof. Farah Zawaideh & Dr. Motasem Abu-Dawas 
Institution: Irbid National University, Faculty of Science and IT
