🚀 Credit Card Fraud Detection

This project is an end-to-end **Credit Card Fraud Detection System** that:

✔ Detects fraudulent transactions using a Deep Learning Model  

✔ Generates AI-powered fraud reports using GPT-4  

✔ Provides an interactive UI for fraud analysts using Gradio  

------------------------------------------------------------

📂 PROJECT STRUCTURE
The project follows a modular design to ensure clarity and organization.  

📂 Credit-Card-Fraud-Detection/
│── 📂 data/                # Contains raw & processed datasets
│── 📂 models/              # Trained model files
│── 📂 outputs/             # Fraud detection results & reports
│── 📂 notebooks/           # Jupyter Notebooks for each step
│── 📄 README.txt           # Project documentation
│── 📄 requirements.txt     # Required dependencies
│── 📄 .gitignore           # Files to exclude from Git

------------------------------------------------------------

🔄 WORKFLOW OVERVIEW
This project follows a structured **4-step pipeline**:

1️⃣ Data Preprocessing  
📌 Load the dataset, handle missing values, and perform feature scaling.  
📌 Balance class distribution to handle fraud detection bias.  
📌 Save processed data for training & evaluation.  

2️⃣ Model Training & Evaluation  
📌 Train a Deep Learning Model (MLP - Multi-Layer Perceptron) with:  
✔ Batch Normalization  
✔ Dropout Regularization  
✔ Focal Loss for Imbalanced Data  
📌 Evaluate performance using Precision, Recall, F1-score.  

3️⃣ Fraud Detection & Reporting  
📌 Use the trained model to detect fraudulent transactions.  
📌 Send flagged transactions to GPT-4 for detailed fraud reports.  
📌 Categorize fraud cases as 🚨 Critical / ⚠️ High / 🔎 Moderate Risk.  

4️⃣ Interactive UI (Gradio Viewer)  
📌 Develop a Gradio-based interactive tool to query fraud reports.  
📌 Allow analysts to review flagged transactions efficiently.  

------------------------------------------------------------

📊 MODEL PERFORMANCE
| Metric      | Score   |
|------------|--------|
| Accuracy   | 99.2%  |
| Precision  | 92.5%  |
| Recall     | 88.4%  |
| F1-Score   | 90.2%  |

------------------------------------------------------------

⚙️ TECHNOLOGIES USED
✅ Python - Data Preprocessing & Model Training  
✅ TensorFlow/Keras - Deep Learning Model  
✅ OpenAI GPT-4 - LLM for AI-Generated Fraud Reports  
✅ Gradio - Interactive UI for Fraud Report Viewing  
✅ Matplotlib & Seaborn - Data Visualization  

------------------------------------------------------------

📂 HOW TO RUN THIS PROJECT
🔹 STEP 1: SET UP THE ENVIRONMENT
1. Clone this repository:  
   git clone https://github.com/aditya-iyer/Credit-Card-Fraud-Detection.git  
   cd Credit-Card-Fraud-Detection  

2. Install dependencies:  
   pip install -r requirements.txt  

3. Set up OpenAI API Key (for LLM-based fraud reports):  
   export OPENAI_API_KEY="your-api-key"  

------------------------------------------------------------

🔹 STEP 2: RUN NOTEBOOKS IN ORDER
Execute the Jupyter notebooks sequentially:

| Step  | Notebook Name                  | Description |
|-------|--------------------------------|-------------|
| ✅ 1  | 01_Data_Preprocessing.ipynb    | Load dataset, clean, scale, and split the data |
| ✅ 2  | 02_Model_Training.ipynb        | Train a deep learning model for fraud detection |
| ✅ 3  | 03_Fraud_Detection.ipynb       | Use the model to detect fraudulent transactions |
| ✅ 4  | 04_LLM_Fraud_Reporting.ipynb   | Generate detailed AI-driven fraud reports |

------------------------------------------------------------

📬 AUTHOR
- **Aditya Iyer**  
- 🚀 Passionate about AI & Fraud Detection  
- 🌐 GitHub Profile: https://github.com/aditya-iyer  

------------------------------------------------------------
