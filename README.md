# CMP7239-CW1
NETWORK INTRUSION DETECTION USING MACHINE LEARNING

The study evaluates six different algorithms, including traditional ensemble methods and Deep Learning architectures, to find the optimal balance between detection accuracy and computational efficiency.

🚀 Key Features
Data Preprocessing: Robust cleaning involving the removal of redundant metadata (Flow IDs, IPs) and zero-variance features, resulting in a 52-feature baseline.

Intelligence Layer Optimisation: Dimensionality reduction using the ANOVA F-Test to select the top 45 features, reducing computational latency.

Multi-Model Comparison: Evaluation of Random Forest, SVM, Decision Trees, KNN, Naive Bayes, and LSTM (RNN).

Performance Analysis: Use of Precision, Recall, and F1-score to assess model reliability against imbalanced network traffic.

📊 Results Summary
The Random Forest model was selected for the final "Intelligence Layer" due to its superior balance of speed and reliability:

Accuracy (99.2%): Overall correctness of the model across all traffic types.

Precision (0.99): The ability of the IDS to identify actual attacks without raising false alarms on legitimate traffic.

Recall (0.99): The critical ability of the system to detect all malicious activities (minimising "False Negatives").

F1-Score (0.99): The harmonic mean of Precision and Recall, proving the robustness of the 45-feature subset.

🚀 Optimised Pipeline
Preprocessing: Cleaned raw traffic into a 52-feature baseline by removing zero-variance and non-predictive metadata.

Feature Selection: Applied ANOVA F-test to isolate the top 45 features, significantly reducing computational overhead for real-time deployment.

Intelligence Layer: Implemented a high-speed ensemble classifier capable of sub-millisecond inference.

Source: https://www.kaggle.com/datasets/ericanacletoribeiro/cicids2017-cleaned-and-preprocessed/data
