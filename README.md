🛡️ AI-Based DDoS Attack Detection System

📌 Project Overview

This project is a Machine Learning-based Network Intrusion Detection System (NIDS) designed to detect Distributed Denial of Service (DDoS) attacks in mobile communication networks (4G/5G).

Using the CIC-DDoS2019 dataset, the system focuses specifically on UDP Lag attacks—a volumetric attack type that saturates bandwidth and disrupts real-time applications like gaming and VoIP.

The model achieves an accuracy of 99.79% with a 100% recall rate, ensuring zero false negatives for attack traffic.

🚀 Key Features

Data Cleaning: Automated pipeline to handle infinite values, missing data, and column formatting inconsistencies.

Feature Selection: Optimized to use only the top 10 most relevant network flow features (e.g., Flow Duration, Packet Length Mean).

High Performance: Uses a Decision Tree Classifier for interpretable, high-speed detection suitable for edge devices.

Binary Classification: Effectively distinguishes between Benign (Normal) traffic and UDP-lag (Attack) traffic.

📊 Performance Metrics

The model was evaluated on a test set of 74,000+ network flows.

| Metric | Score | Meaning |
| Accuracy | 99.79% | Correctly classified almost all traffic. |
| Recall | 100.00% | Caught 100% of all actual attacks (Zero Misses). |
| Precision | 99.80% | Extremely low false alarm rate. |

(Optional: Upload a screenshot of your Confusion Matrix here and name it 'confusion_matrix.png')

🛠️ Technologies Used

Language: Python

Data Processing: Pandas, NumPy

Machine Learning: Scikit-Learn (Decision Tree)

Visualization: Matplotlib

📂 Dataset

This project uses the CIC-DDoS2019 dataset provided by the Canadian Institute for Cybersecurity (CIC).

Note: The dataset is not included in this repository due to size constraints.

Download UDPLag.csv from the official CIC source.

Place it in the root directory of the project.

⚙️ How to Run

Clone the repository:

git clone [https://github.com/your-username/ai-ddos-detection.git](https://github.com/your-username/ai-ddos-detection.git)



Install dependencies:

pip install pandas numpy scikit-learn matplotlib



Run the Jupyter Notebook:

jupyter notebook DDoS_Analysis.ipynb



📜 License

This project is open-source and available under the MIT License.
