🛡️ AI Phishing Detector
A smart, real-time phishing detection system that uses an ensemble machine learning model to protect users from malicious websites. This project analyzes URLs to provide a clear, explainable verdict on their safety.

✨ Core Features
Multi-Signal Analysis: The system doesn't just look at the URL. It analyzes over 150 signals including lexical patterns, webpage content, domain age, and SSL certificate validity.


Ensemble ML Model: Combines multiple machine learning algorithms (like Random Forest and Gradient Boosting) to achieve high accuracy (>95%) and robustness.


Clear, Three-Tier Verdicts: Instantly classifies any URL into one of three easy-to-understand categories: Allow (Safe), Warn (Suspicious), or Block (Malicious).


Explainable AI: Builds trust by providing a simple, clear list of reasons behind every detection decision.

⚙️ How It Works
The system follows a simple yet powerful pipeline to determine if a URL is malicious:


Input: A user submits a URL for analysis.


Feature Extraction: The system rapidly gathers lexical, content, and network-level data from the URL.


ML Inference: The features are fed into our pre-trained ensemble model, which calculates a risk score.


Decision & Explanation: The score is translated into an Allow/Warn/Block decision, and the key contributing factors are presented to the user
