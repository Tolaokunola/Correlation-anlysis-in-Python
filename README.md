
Movie Industry Correlation Analysis in Python

This project performs a comprehensive statistical and correlation analysis on a movie industry dataset using Python. The primary goal is to identify which film features (such as budget, votes, company, or genre) have the most significant impact on a movie's gross revenue.

Project Overview

In the competitive film industry, understanding the financial drivers behind a movie's success is critical. This project walks through the complete data science workflow from data cleaning and feature engineering to advanced visualization and correlation mapping to uncover hidden patterns governing film revenue.

Key Findings

• Budget vs. Gross: Demonstrates the highest positive correlation; higher budgets strong align with higher gross returns.
• Votes vs. Gross: User engagement (votes) shows a strong, secondary positive correlation to financial returns.
• Categorical Drivers: Exploratory mapping evaluates whether production companies, directors, or specific star talent yield disproportionate revenue boosts.

Technical Stack & Dependencies

The project is built entirely within a Jupyter Notebook environment using core Python data science libraries:
• Data Manipulation: Pandas & NumPy
• Data Visualization: Matplotlib & Seaborn
• Statistical Modeling: Python's built-in statistical packages (Pearson correlation coefficient)

Analysis Workflow

The notebook is divided into clear operational phases:

1. Data Cleaning & Preprocessing

• Handling missing values (dropna and inputations).
• Correcting misaligned data types (e.g., stripping decimals from year and float records).
• Standardising release dates to isolate a clean "Year" column.
• Eliminating duplicate records to protect statistical integrity.

2. Exploratory Data Analysis (EDA)

• Constructing scatter plots with regression trends using Seaborn to visualize the relationship between budget and gross earnings.
• Visualizing user votes against revenue metrics.

3. Correlation Mapping

• Computing a numeric correlation matrix using the Pearson method.
• Generating interactive, color-coded heatmaps to quickly isolate strong vs. weak variables.

4. Categorical Matrix Encoding

• Numerically encoding high-cardinality string columns (Company, Director, Genre, Star).
• Factoring these encoded variables back into a full-scale correlation matrix to ensure non-numeric features aren't overlooked.

Getting Started

Follow these steps to run the analysis locally on your machine:

1. Clone the Repository

bash
git clone https://github.com
cd Correlation-anlysis-in-Python
Use code with caution.

2. Set Up a Virtual Environment (Recommended)

bash
# For macOS/Linux
python3 -m venv venv
source venv/bin/activate

# For Windows
python -m venv venv
.\venv\Scripts\activate
Use code with caution.

3. Install Required Libraries

bash
pip install pandas numpy matplotlib seaborn jupyter
Use code with caution.

4. Run the Analysis

Launch the Jupyter interface and open the notebook file:
bash
jupyter notebook Movies_Correlation_Analysis.ipynb
