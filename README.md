# GHSA
Global Health Statistics Analysis (2000–2024)
Objective of the Project:
This report analyzes global health statistics from 2000 to 2024 to identify patterns in disease prevalence, mortality, recovery rates, healthcare access, and vaccine effectiveness. The analysis offers insights to improve health policies and treatment strategies.
Problem Being Addressed:
Global health systems face evolving challenges with both communicable and non-communicable diseases. Understanding disease trends, gender-based impacts, and treatment efficacy is critical to allocating resources and improving outcomes.
Key Datasets and Methodologies:
Data was visualized using Power BI, utilizing bar, pie, and line charts. Aggregations were performed across disease types, countries, gender, and treatment types. Filters enabled breakdown by year, age group, and location.

3. Story of Data
Data Source:
Compiled from global health records, WHO databases, and aggregated epidemiological surveys between 2000 and 2024.
Data Structure:
•	Rows: Individual or grouped health outcome records.
•	Columns: Disease name, incidence rate, mortality, country, gender, vaccine availability, healthcare access, treatment type.
Important Features:
•	Incidence Rate: Tracks how often diseases occur annually.
•	Mortality Rate: Highlights severity and fatality.
•	Prevalence Rate by Country: Shows disease concentration globally.
•	Healthcare Access: Segmented by disease category.
•	Treatment Type: Tied to recovery effectiveness.
Data Limitations or Biases:
•	Vaccine impact is shown only in a 5-year improvement window.
•	Country data focuses only on top 5 regions.
•	No individual-level medical history or treatment adherence included.

4. Data Splitting and Preprocessing
Data Cleaning:
Numeric data was normalized; no inconsistent values are visible from KPIs and graphs.
Handling Missing Values:
Not explicitly shown; assumed removed or excluded from visuals.
Data Transformations:
Aggregations done for incidence rate, mortality by disease, and vaccine-based outcome splits.
Data Splitting:
•	Dependent Variables: Mortality, Recovery Rate, Incidence Rate
•	Independent Variables: Country, Disease Type, Gender, Vaccine Availability, Treatment Type
Industry Context:
This data applies to global health monitoring, public policy, epidemiology, and medical research domains.
Stakeholders:
•	WHO and national health ministries
•	Medical researchers and epidemiologists
•	Pharmaceutical and vaccine developers
•	Global humanitarian health organizations

5. Pre-Analysis
Key Trends Identified:
•	Incidence rate fluctuates year-on-year, peaking in 2004 and again around 2023 (305.1K, 304.9K).
•	Russia and Mexico show the highest prevalence rates (>507K).
•	Mortality is highest for Cancer, closely followed by COVID-19.
Potential Correlations:
•	Vaccine availability shows marginal but consistent improvement in outcomes (Yes: 2.501M vs No: 2.500M).
•	Gender impact is nearly equal, indicating uniform disease exposure across populations.
Initial Insights:
•	Access to healthcare is nearly balanced across disease categories, suggesting systemic improvements in delivery.
•	Surgery and therapy outperform medication and vaccination slightly in recovery rates.

6. In-Analysis
Unconfirmed Insights:
•	Despite global focus on COVID-19, Cancer remains the deadliest, suggesting resource reallocation or awareness gaps.
•	Marginal difference in vaccine effectiveness may imply challenges in availability or administration in certain regions.
Recommendations:
•	Conduct regional audits to understand why countries like Russia and Mexico lead in prevalence.
•	Expand vaccination campaigns alongside other treatment protocols to maximize combined recovery impact.
Analysis Techniques Used:
•	Multi-year line graphs for trend tracking
•	Gender-segmented pie charts
•	Bar charts for comparative mortality, recovery, and vaccine impact
•	KPI tiles for quick summary insights

7. Post-Analysis and Insights
Key Findings:
•	Total Prevalence Rate: 10.05M
•	Recovery Rate: 74.50%
•	Mortality Rate: 10.00
•	Top Mortality Cause: Cancer (254.89K)
•	Highest Prevalence Countries: Russia (509.05K), Mexico (507.42K)
•	Vaccine Availability Impact: ~1K difference over 5 years
•	Best Treatment (Recovery %): Surgery (25.06%)
Comparison with Initial Findings:
Initial assumptions about vaccine superiority were challenged; therapy and surgery also contribute comparably to recovery. Mortality distribution reaffirms the importance of chronic disease attention.

8. Data Visualizations & Charts
Charts and Graphs Used:
•	Line Graph: Incidence over time
•	Bar Charts: Mortality by disease, recovery by treatment, prevalence by country
•	Pie Chart: Gender breakdown
•	Dual Bar: Impact of vaccine availability
Explanation of Visuals:
•	Line chart offers a 24-year trendline showing disease outbreaks and recoveries.
•	Mortality bars clearly compare major diseases.
•	Pie chart simplifies gender distribution insights.
•	Treatment effectiveness chart shows close performance levels, guiding intervention strategies.

9. Recommendations and Observations
Actionable Insights:
•	Strengthen cancer care and early detection globally.
•	Combine vaccine programs with physical treatments like surgery and therapy.
•	Investigate healthcare quality in high-prevalence nations.
Optimizations:
•	Integrate more granular data filters (age, income, lifestyle factors).
•	Extend vaccine improvement metric to 10-year windows.
•	Include real-time tracking post-2024.
Unexpected Outcomes:
•	Gender parity in disease impact was surprising—often overlooked in policy targeting.
•	Minimal difference in 5-year outcomes between vaccinated and non-vaccinated segments warrants deeper exploration.

10. Conclusion
Key Learnings:
•	Global incidence remains volatile, requiring flexible response frameworks.
•	Mortality varies by disease, not geography alone.
•	Vaccine programs help, but need integration with broader care models.
•	Equal gender impact calls for gender-neutral public health campaigns.
Limitations:
•	Limited age breakdown and socioeconomic segmentation
•	Vaccine impact measured only in binary form (Yes/No)
Future Research:
•	Explore mental health statistics and chronic illness burdens
•	Add regional health funding and infrastructure data
•	Analyze time-to-treatment metrics and their effects on mortality

11. References & Appendices
References:
•	Power BI Dashboard: Global Health Statistics
•	Data Export: Global Health Statistics.png
Appendices:
•	KPI tiles and thresholds
•	Vaccine availability segmentation
•	Country-wise and disease-wise raw pivot tables

