Tamil Nadu District GDP Analysis (1999-2007)

This project analyzes the district-level Gross Domestic Product (GDP) of Tamil Nadu, India, from 1999 to 2007. Using historical data, it explores GDP growth trends, identifies top contributing districts, and provides insights into economic patterns. The analysis is performed using Python with libraries like Pandas and Matplotlib for data cleaning, exploratory data analysis (EDA), and visualization.
Key highlights:

Tamil Nadu's overall GDP grew from approximately 25,000 Cr in 1999 to 200,000 Cr in 2007.
Top 5 contributing districts: Coimbatore, Chennai, Vellore, Kancheepuram, and Salem.
Visualizations include bar charts for district contributions, line graphs for growth over time, and more.

This project is ideal for understanding regional economic disparities and can aid policymakers, researchers, and economists.
Dataset

Source: Tamil Nadu District GDP Dataset (1999–2007) on Kaggle (Accessed August 2025).
File: gdp_Tamilnadu.csv (included in the repository).
Description: Contains year-wise GDP data (in Rs. Cr.) for 30 districts of Tamil Nadu, along with growth rates.

Sample Data Preview:

Year,Description,Chennai,Coimbatore,Cuddalore,...
1999-00,GDP (in Rs. Cr.),13215.12,11543.99,4080.01,...
2000-01,GDP (in Rs. Cr.),12725.53,12716.50,4430.56,...

YearDescriptionChennaiCoimbatoreCuddalore...1999-00GDP (in Rs. Cr.)13215.1211543.994080.01...2000-01GDP (in Rs. Cr.)12725.5312716.504430.56...
Project Goals

📊 Collect and clean district-level GDP data.
📈 Visualize GDP growth over the years.
🏆 Identify the top 5 contributing districts to the state’s GDP.
🔍 Compare growth patterns between districts.
📑 Provide insights for policymakers and researchers.

Approach

Data Collection: Sourced from Kaggle.
Cleaning & Preprocessing: Loaded into Pandas DataFrame, handled missing values, and computed totals/averages.
Exploratory Data Analysis (EDA): Calculated sums, means, and growth trends.
Visualization: Generated bar charts, line plots, and district-wise comparisons using Matplotlib.
Insights: Derived key statistics, such as average contributions and growth rates.

Requirements

Python 3.x
Libraries:

Pandas (pip install pandas)
Matplotlib (pip install matplotlib)
Jupyter Notebook (for running the analysis interactively)



Installation

Clone the repository:
textgit clone https://github.com/your-username/tn-gdp-analysis.git
cd tn-gdp-analysis


Run the Jupyter Notebook:
textjupyter notebook tn_gdp_project.ipynb


Usage

Open tn_gdp_project.ipynb in Jupyter.
Run the cells sequentially to load data, perform EDA, and generate visualizations.
Key sections:

Data Loading: Reads gdp_Tamilnadu.csv.
Visualizations: Plots for overall growth, top districts, and individual district trends (e.g., Coimbatore, Chennai).
Insights: Printed summaries like total GDP, averages, and growth from 1999 to 2007.



Example Output (from Notebook):

Total GDP for Coimbatore (1999-2007): 572,475.1 Cr (Average: 63,608.34 Cr).
Chennai contributed ~26% of the state's GDP.

Results & Insights

Overall Growth: Tamil Nadu's GDP increased 8-fold from 25,000 Cr to 200,000 Cr.
Top Contributors (1999-2007 Total GDP in Cr):

Coimbatore: 457,980.08
Chennai: 449,981.36
Vellore: 266,417.88
Kancheepuram: 266,013.6
Salem: 242,719.12


District-Specific Insights:

Coimbatore: Grew from 11,543.99 Cr (1999) to 16,670.5 Cr (2007). Average: 63,608.34 Cr.
Chennai: Grew from 13,215.12 Cr (1999) to 16,670.56 Cr (2007). Average: 12,725.53 Cr (26% of state GDP).
Vellore: Grew from 7,175.18 Cr (1999) to 66,604.47 Cr (2007). Average: 13,484.39 Cr.
Kancheepuram: Grew from 6,845.13 Cr (1999) to 66,503.4 Cr (2007). Average: 66,503.4 Cr.
Salem: Grew from 11,543.99 Cr (1999) to 16,670.5 Cr (2007). Average: 33,710.988 Cr.



Visualizations are saved in the images/ folder or generated in the notebook.
Presentation

View the full analysis in the PDF: tn_gdp.pdf.
Includes slides on data source, goals, approach, growth charts, and district breakdowns.



Author: Aabith
GitHub: aabith7
Email: aabith1853@gmail.com

Feel free to fork, contribute, or raise issues! 🙏 தமிழ் வாழ்க (Tamil Vaazhga)5.7sExpert
