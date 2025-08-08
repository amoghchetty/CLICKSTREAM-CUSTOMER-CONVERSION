# 🛒 Clickstream Customer Conversion Analysis

## 📌 Overview
This project analyzes customer clickstream data to predict purchasing behavior and understand user patterns on an e-commerce platform.  
It uses **classification**, **regression**, and **clustering** models, and provides an interactive **Streamlit dashboard** for data exploration, predictions, and visualization.

The application supports:
- Uploading your own train/test CSV files
- Viewing exploratory data analysis (EDA) results
- Running pre-trained models for classification, regression, and clustering
- Row-level feature visualizations for deeper insights

---

## 📊 Features
- **Data Upload**: Upload train/test datasets directly in the app
- **Classification**: Predict whether a customer will purchase
- **Regression**: Predict target values (e.g., revenue or time on site)
- **Clustering**: Group customers based on similar clickstream behaviors
- **EDA**: Visualize distributions, correlations, and trends
- **Interactive UI**: Built with [Streamlit](https://streamlit.io)

- ## 📂 Project Structure
- project-CLICKSTREAM CUSTOMER CONVERSION/
├── app.py # Streamlit application
├── requirements.txt # Python dependencies
├── README.md # Project documentation
├── data/ # Dataset folder (empty by default)
│ ├── train.csv
│ └── test.csv
├── models/ # Model folder (empty by default)
│ ├── classifier_model.pkl
│ ├── regression_model.pkl
│ └── clustering_model.pkl
│ ├── CLICKSTREAM_CUSTOMER_CONVERSION.ipynb


---

## 📥 Datasets & Model Files
Due to GitHub's file size limits, the datasets and trained model files are hosted on **Google Drive**.

### 📊 Datasets
- **Train and Test Dataset**: [Download here](https://drive.google.com/drive/folders/1oesa87_YNPYWpsMr9gsor_d1Pn9aBjKu?usp=drive_link)

Place both CSV files inside the `data/` folder:
├── CLICKSTREAM CUSTOMER CONVERSION.datasets/
│ ├── train.csv
│ └── test.csv


---

### 🤖 Trained Model Files
- **Classifier,Regression & Clustering Model**: [Download here](https://drive.google.com/drive/folders/1IX_NlBMIL3f511PYG0yI_ITQLRZpU6lO?usp=drive_link)

Place all `.pkl` files inside the `models/` folder:
project-root/
├── CLICKSTREAM CUSTOMER CONVERSION.model/
│ ├── classifier_model.pkl
│ ├── regression_model.pkl
│ └── clustering_model.pkl


---

## ⚙️ Installation
1. **Clone the repository**
```bash
git clone https://github.com/your-username/clickstream-customer-conversion.git
cd clickstream-customer-conversion



