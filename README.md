Project Description

This project focuses on analyzing and detecting cyberattacks (such as DDoS, port scanning, and other anomalous network behaviors) using Recurrent Neural Networks (RNN) and similar models like LSTM. The primary goal is to identify abnormal behaviors in network traffic through labeled datasets and deliver accurate and optimized models.

Key Features

 • Data Used:
 • Datasets like CICIDS 2017 or KDD Cup 99 containing network traffic features such as source IP, destination IP, protocol type, timestamps, and attack labels.
 • Machine Learning Model:
 • Design and train a simple RNN model using robust libraries like TensorFlow or PyTorch.
 • Evaluation Metrics:
 • Measure model performance with metrics such as F1-score, ROC-AUC, recall, and accuracy.
 • Model Optimization:
 • Implement optimization techniques like Dropout and hyperparameter tuning to improve performance.
Technologies Used

 • Programming Languages:
 • Python
 • Libraries and Tools:
 • TensorFlow, PyTorch
 • NumPy, Pandas for data preprocessing
 • Matplotlib, Seaborn for data visualization

Installation and Execution

 1. Clone the repository:

git clone https://github.com/YourUsername/CyberAttackDetection-RNN.git
cd CyberAttackDetection-RNN


 2. Create a virtual environment and install dependencies:

python -m venv env
source env/bin/activate  # For Windows, use `env\Scripts\activate`
pip install -r requirements.txt


 3. Run the code:

python train_model.py

Results

 • Performance of the RNN model on the test dataset:
 • Accuracy: 94%
 • Recall: 92%
 • F1-score: 93%
 • Successfully detected abnormal network behaviors such as port scanning and DDoS attacks.
License

This project is licensed under the MIT License. See the LICENSE file for details.# CyberAttackDetection
