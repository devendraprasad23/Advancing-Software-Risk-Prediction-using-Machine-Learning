# Advancing-Software-Risk-Prediction-using-Machine-Learning
🚀 Advancing Software Risk Prediction in Requirements Engineering
Hi! 👋 I'm Devendra Prasad, and this is my B.Tech final year project where I worked on building an intelligent and explainable system for predicting software risks during the Requirements Engineering (RE) phase using Machine Learning.

Traditional approaches usually rely on binary classification or manual judgment, which often miss out on the complexity of real-world software projects. So, I set out to design a system that not only predicts risks more accurately but also explains why those risks exist.

🧠 What This Project Does
🔍 Classifies Software Risks into Multiple Categories
Instead of just saying something is "risky" or "not risky", the system tells you what kind of risk it is—like ambiguity in requirements, stakeholder conflicts, technical challenges, etc.

📋 Generates Human-Readable Rules
Using the Random Forest algorithm, the model extracts “if-then” rules that explain the reason behind every prediction—bringing in much-needed transparency.

📂 Handles Real-World Requirement Data
The model is trained on practical requirement documents, and I engineered features from text data to improve both accuracy and explainability.

🛠️ Tech Stack I Used
Python – for everything from data preprocessing to modeling
Scikit-learn – to build and evaluate the Random Forest classifier
NLTK/spaCy – for text preprocessing and ambiguity detection
Matplotlib / Seaborn – for visualizing results and insights
(Optional) Flask/Tkinter – for building a simple UI for non-technical users

🎯 My Main Objectives
Predict and classify risks early in the SDLC to avoid project delays and failures
Make the system explainable so project managers can actually trust and act on the results
Create a practical, real-world solution—not just a theoretical model

💡 Sample Output Example
Risk Type: Technical Risk
Extracted Rule:
If requirement is vague AND lacks acceptance criteria AND involves multiple stakeholders, THEN classify as Requirement Risk.

📈 Model Evaluation
Accuracy, Precision, Recall, F1-Score – to ensure good performance
Rule Quality – measured using support and confidence metrics


