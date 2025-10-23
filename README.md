Customer Behavior Data Analytics Project
📌 Overview

This project analyzes customer behavior using Python, SQL, and Power BI to uncover actionable business insights. It demonstrates a complete end-to-end data analytics workflow — from data ingestion, cleaning, and exploration to SQL querying, dashboard creation, and reporting.

The objective is to identify key purchasing patterns, segment customers effectively, and support data-driven decision-making.

📊 Dataset

Name: Customer Behavior Dataset

Source: (Add source here — e.g., Kaggle or internal data)

Description: Contains detailed customer purchase history, demographics, promotional engagement, and spending behavior.

Size: ~ (add number of rows/columns)

Key Columns:

customer_id

age, gender, region

purchase_amount, discount_applied, promo_code_used

purchase_date

🛠️ Tools & Technologies
Category	Tools Used
Programming	Python (Pandas, NumPy, Matplotlib, Seaborn)
Database	PostgreSQL + pgAdmin
Visualization	Power BI
Documentation	Jupyter Notebook, Gamma App
Version Control	Git & GitHub
🔍 Project Steps
1. Data Loading

Loaded the dataset into Python using Pandas.

Connected to PostgreSQL using SQLAlchemy and imported the cleaned data into a database table.

2. Exploratory Data Analysis (EDA)

Conducted univariate and bivariate analysis to explore distributions and relationships.

Visualized trends and outliers using Matplotlib and Seaborn.

Identified patterns in customer spending and regional performance.

3. Data Cleaning

Handled missing, duplicate, and inconsistent data.

Standardized column names and formats.

Encoded categorical variables for analysis.

4. SQL Analysis

Executed analytical queries using PostgreSQL to extract business insights, such as:

Top customers by revenue

Most responsive regions to promotions

Discount effectiveness on sales volume

5. Power BI Dashboard

Built an interactive Power BI dashboard displaying key metrics:

Total revenue & average purchase value

Regional & demographic segmentation

Promotional performance metrics

6. Reporting & Presentation

Compiled a concise analytical report summarizing insights and recommendations.

Designed a Gamma presentation for professional storytelling and business presentation.

📈 Dashboard Preview

(Add a Power BI dashboard screenshot here — e.g., /assets/dashboard_preview.png)

The dashboard provides a clear, interactive summary of customer insights and sales performance.

🧾 Results & Insights

Identified high-value customer segments driving major revenue.

Found strong correlation between discounts and repeat purchases.

Highlighted regional patterns that can improve marketing strategies.

Provided data-driven recommendations for future promotional planning.

▶️ How to Run
1. Clone the Repository
git clone https://github.com/Aryan-nitA/customer-behavior-analytics.git
cd customer-behavior-analytics

2. Install Dependencies
pip install -r requirements.txt

3. Run the Python Script
python load_data.py

4. Access PostgreSQL

Open pgAdmin or use terminal to connect to your PostgreSQL server.

Verify that the customer table is created and populated.

5. Open Power BI Dashboard

Launch Power BI Desktop.

Open the .pbix file to explore and interact with visualizations.

📬 Contact

👤 Author: Aryan Giri
📧 Email: aryangiri198@gmail.com

🔗 LinkedIn: linkedin.com/in/aryan-giri-1298212b1

💻 GitHub: github.com/Aryan-nitA
