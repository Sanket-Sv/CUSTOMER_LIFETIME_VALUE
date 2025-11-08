# 🧠 Customer Lifetime Value Prediction

This project predicts **Customer Lifetime Value (CLV)** using machine learning techniques.  
It analyzes customer behavior, purchase frequency, and monetary value to estimate how valuable each customer will be to the business over time.

---

## 📂 Project Structure
customer-lifetime-value-prediction/
│
├── dataset/ # dataset used for training and testing
├── visuals/ # generated charts and visualizations
├── notebook/
│ └── customer-lifetime-value-prediction.ipynb
│
├── src/ # reusable functions and scripts (optional)
│ ├── data_preprocessing.py
│ ├── model_training.py
│ └── evaluation.py
│
├── requirements.txt # required dependencies
├── .gitignore # ignore unnecessary files
├── LICENSE # MIT license
└── README.md # project documentation


---

## 🚀 Features
- Data preprocessing and cleaning  
- Feature engineering for customer segmentation  
- K-Means clustering for behavioral grouping  
- Predictive modeling using **XGBoost** and **Scikit-Learn**  
- Interactive visualizations with **Plotly** and **Seaborn**

---

## 🧩 Tech Stack
- **Python 3.10+**
- **Libraries:** pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, xgboost

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/customer-lifetime-value-prediction.git
cd customer-lifetime-value-prediction

# Create and activate a virtual environment (optional)
python -m venv venv
source venv/bin/activate   # for macOS/Linux
venv\Scripts\activate      # for Windows

# Install dependencies
pip install -r requirements.txt


📊 Usage

Place your dataset inside the dataset/ folder.

Open the Jupyter notebook:

jupyter notebook notebook/customer-lifetime-value-prediction.ipynb


Run all cells to preprocess data, train the model, and visualize results.

🧠 Model Overview

The project follows a data-driven pipeline:

Data Preprocessing – handles missing values, feature transformations, and encoding.

Feature Engineering – builds RFM (Recency, Frequency, Monetary) features.

Clustering – segments customers with K-Means based on behavioral traits.

Prediction – uses XGBoost Regressor to estimate customer lifetime value.

Evaluation – measures performance using metrics such as RMSE and R².

📈 Results

Clustered customers into distinct behavioral segments.

Predicted CLV with strong correlation to actual purchase behavior.

Identified top-value customers for targeted marketing.

Improved retention strategy insights using data visualization.

🖼️ Visuals

Example charts (available in the visuals/ folder):

RFM Segmentation Scatter Plot

Feature Importance Graphs

Customer Distribution by Cluster

Predicted vs Actual CLV Chart

👨‍💻 Author

Sanket Kumar
📧 sanketsv11@gmail.com

Data Science | Machine Learning | AI Enthusiast
🌐 https://github.com/Sanket-Sv
https://www.linkedin.com/in/sanket-kumar-5sv/


