#🧠 Mental Health in Tech - Data Analysis Project
This project explores mental health among tech employees using real-world survey data. It includes data preprocessing, visualizations, and statistical analysis to uncover key patterns, correlations, and workplace factors that influence mental health treatment.

📁 Project Structure
MentalHealth.ipynb — Main Jupyter Notebook for data analysis and visualizations.

survey.csv — Dataset containing responses from tech employees regarding mental health.

images/ — Folder for exported visualizations (charts, graphs, heatmaps).

README.md — Project overview and documentation.

🔍 Objectives
Analyze mental health trends across age groups and genders.

Investigate the effect of family history on seeking treatment.

Study workplace benefits and wellness programs in relation to mental health.

Use correlation heatmaps to identify influential variables.

📂 Dataset
File: survey.csv

Source: Kaggle - Mental Health in Tech Industry Survey

Attributes Include:

Age, gender, work location

Mental health history

Treatment seeking behavior

Employer-provided benefits (e.g., wellness programs, care options)

📊 Key Insights
1. Gender vs. Age Seeking Help
Males are more likely to seek mental health support in the age group of 25–35.

Female respondents showed lower treatment-seeking rates overall.

2. Family History Impact
39% of participants reported a family history of mental illness.

74% of those are currently undergoing treatment, compared to just 35% among those without such a history.

3. Correlation Analysis
Variable Pair	Correlation
seek_help & wellness_program	0.59
treatment with any other variable	< 0.3

Strongest relationship found between workplace wellness programs and seeking help.

Weak links between actual treatment and benefits point to external blockers like stigma or fear of disclosure.

🛠️ Tools & Technologies
Python (Pandas, NumPy)

Visualization: Matplotlib, Seaborn

Notebook: Jupyter

Statistical Analysis: Correlation matrix, percentage plots, pie charts

🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone <repo-url>
Install dependencies:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook MentalHealth.ipynb
Run all cells to reproduce visualizations and insights.

✅ Skills Demonstrated
Data Cleaning and Validation

Exploratory Data Analysis (EDA)

Statistical Inference

Insightful Data Visualization

KPI Tracking & Reporting

🏁 Conclusion
This project reveals significant factors influencing mental health behavior in tech workplaces. It emphasizes how proactive company programs can improve employee wellbeing, while also showing gaps where awareness and access still lag.

