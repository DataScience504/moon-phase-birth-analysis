🌕 Birth Analysis by Lunar Phase
This project explores the relationship between the lunar phase and the number of births per day using historical data. The goal is to determine whether moon phases influence birth patterns and to explore variations by weekday and month.

📊 Objective
Analyze if there's any statistically significant relationship between the moon phase and the number of births in Malaysia between 2004 and 2023. The analysis also explores potential patterns by weekday and by month.

🔧 Tools and Technologies
Python (Pandas, Matplotlib, Seaborn, Scipy, Statsmodels)

Jupyter Notebook

Export to Excel for visualization

Dataset from the Government of Malaysia

🧠 Methodology
The notebook includes the following steps:

Data loading and cleaning: Outlier detection and filtering.

Lunar phase calculation: Using the moon's age to assign a phase to each date.

Exploratory data analysis: Boxplots, heatmaps and group summaries.

Statistical analysis:

ANOVA to test if the mean number of births differs between lunar phases.

Tukey's HSD test to compare differences between weekdays and months.

📁 Dataset
The dataset contains daily birth records in Malaysia from 1920 to 2023 and was published by the Government of Malaysia. It includes fields such as:

Date

State

Number of births

Data source:
🗂️ https://data.gov.my/data-catalogue/births
Published by the Department of Statistics Malaysia (Jabatan Perangkaan Malaysia).

📈 Key Findings
There is no statistically significant effect of the moon phase on birth frequency.

There are significant differences by weekday and by month in birth counts.

A small number of extreme outliers (2 days per year) were removed to improve clarity.

🔬 Statistical Results
ANOVA (Lunar Phase): p-value > 0.8 → No significant difference.

Tukey Test (Weekdays): Several weekday pairs showed significant differences in average births.

Tukey Test (Months): Differences found, particularly between months like January and December.

🧪 Visualizations
Several boxplots and heatmaps are used to support the analysis.

(Note: Visuals are included in the notebook and can be reused for presentations or web embedding.)

📄 Notebook
The main notebook (NacFaseLunar.ipynb) contains all analysis steps, explanations and output.
There is also a Spanish version available for Spanish-speaking audiences.

🌐 License and Use
This project is shared under the MIT License.
You're free to explore, reproduce and adapt the analysis with proper attribution.

