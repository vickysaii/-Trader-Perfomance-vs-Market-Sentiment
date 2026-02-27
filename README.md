Trader Performance vs Market Sentiment

📌 Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear/Greed) and trader behavior and performance on the Hyperliquid platform.
The objective is to derive actionable insights and simple predictive signals that can inform smarter trading strategies.

⚙️ Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/trader-sentiment-analysis.git
cd trader-sentiment-analysis
2️⃣ (Optional) Create a Virtual Environment
python -m venv venv
source venv/binactivate      # Mac/Linux
venv\Scripts\activate        # Windows
3️⃣ Install Dependencies
pip install -r requirements.txt

📦 Required Libraries
pandas
numpy
matplotlib
seaborn
scikit-learn

▶️ How to Run the Project
Option 1: Run Locally (Jupyter Notebook)
jupyter notebook
Open Assignmnet-0.ipynb
Run all cells from top to bottom

Option 2: Run in Google Colab
Upload Assignmnet-0.ipynb to Google Colab
Upload dataset files into the data/ folder

Run all cells sequentially

📝 Notes
Analysis is performed at daily granularity to align trader behavior with market sentiment.
The focus is on interpretability and actionable insights, not heavy model tuning.
No external APIs or credentials are required.

🏁 Output
Running the notebook will generate:
Data quality summaries
Visual comparisons between Fear and Greed regimes
Trader behavior insights
Actionable trading strategy recommendations
A bonus predictive model for next-day profitability

👤 Author
Annarapu Virupaksh
Data Science Intern Applicant – Primetrade.ai
