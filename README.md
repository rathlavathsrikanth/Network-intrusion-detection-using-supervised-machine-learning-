 Network Intrusion Detection using Supervised Machine Learning with Feature Selection
 
📌 OVERVIEW

This project builds an Intrusion Detection System (IDS) that automatically detects whether network traffic is normal or an attack using supervised machine learning algorithms. 
It uses the NSL-KDD dataset, which is a standard benchmark dataset used worldwide for testing intrusion detection systems.

🎯OBJECTIVE

To classify network connections as either:

Normal — legitimate network traffic
Attack — malicious/intrusive network activity (DoS, Probe, R2L, U2R attacks)

📂 DATASET — NSL-KDD

An improved version of the classic KDD Cup 99 dataset
Contains network connection records with 41 features each
Labels each record as normal or one of several attack types

PROJECT STRUCTURE

NSL-KDD-Dataset/ — Dataset folder
IDS.py — Main Python script
clean.txt — Cleaned/preprocessed data
run.bat — Batch file to run the project
README.md — Project documentation

⚙️ How It Works

Data Loading — NSL-KDD dataset is loaded and read
Preprocessing — Data is cleaned, encoded, and normalized
Feature Selection — Most important features are selected to improve accuracy
Model Training — Supervised ML models are trained on the data
Prediction — Model predicts if new traffic is normal or an attack
Evaluation — Accuracy, precision, and recall are measured

🤖 Machine Learning Models Used

Random Forest
Decision Tree
Neural Network (via Keras + TensorFlow)

🛠️ Technologies Used

Python — Core programming language
scikit-learn — ML algorithms and feature selection
TensorFlow / Keras — Deep learning
pandas / numpy — Data handling and processing
matplotlib / seaborn — Graphs and visualizations
OpenCV / imutils — Image-based utility support

HOW TO RUN

Step 1 — Clone the repository:
git clone https://github.com/rathlavathsrikanth/Network-intrusion-detection-using-supervised-machine-learning-.git
Step 2 — Install required libraries:
pip install pandas numpy scikit-learn matplotlib seaborn tensorflow opencv-python imutils
Step 3 — Run the project:
python IDS.py
📈 Expected Output

Accuracy scores for each ML model
Comparison of models to find the best performer
Graphs showing model performance
Prediction results on test data

💡 Real-World Use Case
This system is used by cybersecurity teams in companies, banks, and government organizations to monitor networks 24/7 and automatically 
flag suspicious activity without needing a human to check every connection manually.
GitHub: https://github.com/rathlavathsrikanth

How to add this to GitHub:

Open Notepad on your laptop
Copy and paste everything above into it
Click File → Save As
Navigate to C:\Users\rathl\Projects\network-ids
Set filename as README.md
Set Save as type to All Files (*.*)
Click Save

Then run these commands in CMD:
cd C:\Users\rathl\Projects\network-ids
git add README.md
git commit -m "Add README file"
git push
