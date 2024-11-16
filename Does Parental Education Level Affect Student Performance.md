**Investigating the Influence of Parental Education on Student Performance**

**DSC 530 Data Exploration and Analysis**

**Project**

**Hasnaa Elidrissi**

**November 16, 2024**

**Bellevue University**

This study examines whether parental education impacts student performance, specifically we are analyzing the effects of mother’s (Medu) and father’s (Fedu) education levels on final grades (G3). The primary question is: Does higher parental education correlate with better academic outcomes?

**Outcome of EDA**:

Exploratory data analysis (EDA) showed that parental education is generally high among students, with most achieving moderate grades. A Probability Mass Function (PMF) comparison suggested that students with higher parental education were more likely to attain higher grades.

Additionally, study time positively correlated with performance, while previous failures showed a negative correlation with grades. However, interaction effects between these variables and parental education were not explored, which might reveal compounded influences.

The analysis did not invetigate non-linear relationships or potential temporal trends in the dataset, such as how the effects of parental education may have changed over time or differ across contexts.

**Gaps and Limitations:**

Several limitations emerged during the analysis:

- **Socio-Economic Status (SES):** SES was not included, which is a potential confounder that could influence academic performance. SES could help isolate the effect of parental education from broader socio-economic advantages.
- **Parental Involvement:** No data was available on the time or effort parents directly invest in their childrens education, which might explain part of the variance in grades.
- **Lifestyle and Support Systems:** Factors like sleep patterns, peer influence, and access to tutoring or extracurricular activities were not considered but might play significant roles.
- **Interaction Effects:** The analysis did not consider interactions between Medu, Fedu, and other variables like study time and failures, potentially missing insights into compounded influences.

**Interpretation of Results:**

Regression analysis found a significant positive effect of mothers education (Medu) on G3, suggesting a possible supportive role of maternal influence. However, fathers education (Fedu) showed no significant effect. The low R-squared value of the model indicates that parental education alone explains only a small fraction of the variance in grades, pointing to other influential factors like SES, study habits, and school quality.

When comparing distributions using the PMF, students with higher parental education levels were more likely to achieve higher grades. However, the assumption of a linear relationship between parental education and grades might oversimplify the dynamic, as non-linear relationships were not tested.

**Conclusion:**

While maternal education shows a modest correlation with student grades, it's clear that parental education alone does not strongly predict academic outcomes. Other factors, such as socio-economic status, study habits, lifestyle, and school quality, likely play more significant roles. This finding aligns with the t-test results, which suggested differences in G3 based on parental education but also underscored the importance of other variables.

**Challenges and Learning Points:**

- Distinguishing Correlation from Causation: It is difficult to discern whether parental education directly influences grades or serves as a proxy for other factors, such as SES or motivation.
- Interpreting PMFs: Ensuring the clarity of insights from distribution comparisons and their implications for academic performance reqired attention to detail.
- Inclusive Data Collection: The study highlighted the need for more comprehensive data collection, particularly regarding SES and other potentially confounding factors, to draw accurate and unbiased conclusions.