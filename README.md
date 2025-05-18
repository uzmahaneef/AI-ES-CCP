Youtube: https://youtu.be/3lniXgrWaxc

AI-Enhanced OWASP ZAP Vulnerability Scanner
Automated Web Security Testing | AI-Powered Risk Scoring |  Interactive HTML Reports
An AI-augmented vulnerability scanner built on OWASP ZAP, combining traditional security scanning with machine learning to detect and prioritize web vulnerabilities (SQLi, XSS, SSRF, etc.).

Key Features
OWASP ZAP Integration: Automated spidering + active scanning via ZAP API.

Hybrid AI Model:
     SVM for vulnerability classification (e.g., CWE-89 for SQLi).
     Neural Network for severity prediction (1–10 risk score).
Prioritized Reporting: Generates HTML reports with remediation guidance.
User-Friendly GUI: Tkinter interface for easy scanning.
Excel-Based Training: Uses vulnerabilities.xlsx to train the AI model.

Tech Stack
Python 3.12 | TensorFlow | scikit-learn | pandas
OWASP ZAP API (python-owasp-zap-v2.4)

Install dependencies:
pip install tensorflow python-owasp-zap-v2.4 pandas openpyxl

Run OWASP ZAP in daemon mode:
zap.sh -daemon -port 8080 -config api.key=YOUR_KEY

Launch the scanner:
python main.py


