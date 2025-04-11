# Sonar-Based-Mine-vs-Rock-Identification-Comparative-Machine-Learning-Analysis-Project



📌 Overview
This project performs a comparative study of four machine learning algorithms — Logistic Regression, K-Nearest Neighbours (KNN), Decision Tree, and Support Vector Machine (SVM) — to classify underwater sonar signals as either mines or rocks. The models are trained and tested using sonar data obtained from bouncing sound waves off metal cylinders and rocks, with the goal of improving underwater object identification for applications in maritime safety, exploration, and defense.




🧪 Machine Learning Models Used
- Logistic Regression
- K-Nearest Neighbours (KNN)
- Decision Tree
- Support Vector Machine (SVM)




📊 Evaluation Metrics
To ensure a nuanced and insightful performance comparison, the following metrics were used:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix




🛠 Tools and Libraries
- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn




🧹 Data Preprocessing
- Checked and confirmed no null or duplicate values
- Addressed class imbalance using upsampling
- Performed visualization with histograms and spectral envelopes
- Split data into training (90%) and testing (10%)




📈 Results Summary
Model	Accuracy :
Logistic Regression	82.6%
KNN (k=5)	95.6%
Decision Tree	82.6%
SVM	86.9%





🟢 K-Nearest Neighbours (k=5) performed the best in terms of precision, recall, and F1-score.




🔮 Future Scope
- Implement feature reduction techniques (e.g., PCA)
- Expand to advanced models like Random Forest, Gradient Boosting, or Neural Networks
- Apply to real-time sonar signal systems for defense and mineral exploration




📚 Dataset
- Source: Kaggle - Sonar Dataset
- Features: 60 frequency-based energy values per sample
- Labels: M = Mine, R = Rock




📄 License
This project is intended for educational and research purposes. Please cite appropriately if you build upon it.

