# Credit Card Fraud Detection using Graph Theory and Explainable AI (XAI)

## Overview
Credit card fraud detection remains a critical concern for financial institutions, as conventional rule-based and statistical approaches often fail to keep up with increasingly sophisticated fraudulent behavior. This project introduces an advanced fraud detection framework that combines **graph-based modeling** with **explainable artificial intelligence (XAI)** to improve detection accuracy and promote model transparency.

---

## Abstract
The solution models transaction data as a **bipartite graph**, where nodes represent **cardholders** and **transactions**, and edges capture their interactions. This structure enables the identification of non-obvious patterns and anomalous relationships that would likely be missed by traditional, flat machine learning models.

To enhance interpretability—a key requirement for adoption in real-world financial systems—we integrate **LIME (Local Interpretable Model-Agnostic Explanations)**, which provides human-readable insights into the model’s predictions.

---

## Key Contributions
-  **Graph-Based Fraud Detection**: Utilizes bipartite graph modeling to capture complex relationships and detect suspicious patterns.
-  **Improved Efficiency**: Enhances fraud detection accuracy by leveraging structural and relational features.
-  **Model Explainability**: Incorporates XAI tools like **LIME** to make model decisions transparent and trustworthy.
-  **Real-World Applicability**: Scalable design for deployment on large-scale financial datasets.

---

##  Features
- **Graph Construction**: Converts raw transaction data into a bipartite graph of cardholders and transactions.
- **Pattern Recognition**: Identifies clusters, outliers, and fraud-prone subnetworks using graph metrics.
- **Explainable Predictions**: Applies LIME to interpret the decisions of the classifier in a local context.
- **Scalable & Modular**: Built for easy integration with financial fraud detection pipelines.

---

##  Technologies Used
- **Python**: Core development language
- **NetworkX**: Graph construction and network analysis
- **Scikit-learn**: Preprocessing, model training, and evaluation
- **Graph Neural Networks (GNN)**: For future extension into deep graph learning
- **LIME**: Model-agnostic explanation of predictions
- **HTML/CSS**: For interactive visualization and reporting

---

##  Potential Extensions
- Integration of **Graph Neural Networks (GNNs)** for deeper representation learning
- Real-time fraud alert generation system
- Deployment via **FastAPI** or **Flask** with visual dashboards

---

##  Acknowledgements
This project is inspired by the growing need for **interpretable AI in fintech**, especially for improving transparency in high-stakes domains like fraud detection.

---

##  Contact
For questions or collaboration inquiries:  
 shrutic794@gmail.com  
🔗 [GitHub](https://github.com/shrutic794)  
🔗 [LinkedIn](https://www.linkedin.com/in/shruti-chandrasekar-2399022a2/)

---

*Building transparent AI systems to protect financial trust.*
