# Practical-Application-Assignment-5.1
Analysis of customer coupon acceptance patterns using behavioral and contextual data.

**UC Berkeley Executive Education – Machine Learning and Artificial Intelligence Program**  
**Author:** Jonathan O’Dea  
**Date:** October 2025 

**Objective**
The objective for this practical assignment is to analyze the dataset provided in order to come to conclusions as to what kind of customers accept targeted coupons and what are the conditions in which they do so. The end goal is to build the skills and thought process in which machine learning models and AI could be trained in order to enhance coupon acceptance rates and customer targeting, though at this stage and for this assignment, it is not considered. 

Additionally, part of the exercise is to practice and evaluate the ability to clean and process data sets in order to obtain clear and actionable insights from it.

**Dataset**
The dataset, titled `coupons.csv`, has been provided by Emeritus and UC Berkeley as a CSV which has been downloaded locally and worked on. The dataset itself has not been modified, only adjusted within this notebook.

**Notebook**
This notebook, `Practical_Assignment_5.1_Jonathan_O'Dea.ipynb`,contains the following section:
- Project prompt
1. Data Loading and Review
2. Data Preparation
3. Initial Data Review and Observations
4. Investigating the Bar Coupons
5. Independent Investigation
6. Findings and Conclusion

**Summary of Findings**
Through this analysis it was evident to see some reocurring trends in coupon acceptance rates which could help in future offer predictions and modelling. Across all coupon categories, the overall acceptance rate was 56.8%. Bar coupons were less frequently accepted overall (41%), yet showed the strongest response among drivers under 30 and those who visit bars more than once per month, with acceptance rates of roughly 70%, compared with ~30% for infrequent visitors.

Additional behavioral and demographic patterns included:

- Timing: Most accepted coupons were used within a one-day expiration window and outside home/work trips, indicating more planned decisions rather than impulsive ones.
- Demographics: Acceptance was highest among younger drivers, particularly those who were single or married with a partner.
- Income: While acceptance spans all income brackets, there is a slight skew toward lower to middle incomes, aligning with the younger demographic most responsive to Bar coupons.

**Actionable ideas**
- Target drivers by habit and timing: Focusing on drivers with over two visits a month.
- Perform testing on coupon expiry: Perform A/B testing on coupon acceptance using the 1 day expiration as a base.
- Target timing with venues/ coupons: Bars for after office hours, mornings for coffee, etc.
- Amplify time windows and offers: Targeting for less frequent coupon users.
- Bundle coupons: See if combining or bundling coupons in various categories for bigger rewards can be achieved.

**How to Run**

1. The public project repository can be located at: https://github.com/Jonny802/Practical-Application-Assignment-5.1
2. Download the project file `Practical_Assignment_5.1_Jonathan_O'Dea.ipynb` and `coupons.csv` csv locally
3. The dataet should be located in /data locally
4. Run cells top-to-bottom.


**Grading Rubric**

**Project Organization**
· A READMe file with a summary of findings and a link to your Jupyter notebook
· Jupyter notebook with headings and text appropriately formatted
· No unnecessary files
· Directories and files have appropriate names and locations

**Syntax and Code Quality**
· Libraries are imported and aliased correctly
· Code does not contain errors
· No long strings of code output
· Demonstrates competency with pandas
· Demonstrates competency with seaborn
· Comments are used appropriately to explain code
· Variables are sensible
**Visualizations**

· Appropriate plots for categorical and continuous variables are utilized
· Plots contain human readable labels
· Plots contain descriptive titles
· Axes are legible
· Subplots are used when appropriate
· Plots are scaled appropriately for readability

**Findings**
· Clearly stated problem for specific coupon group
· Visualizations that demonstrate exploring differences in those who accepted and rejected the coupon
· Interpretation of descriptive and inferential statistics is correct and concise
· The findings are clearly stated in their own section with actionable items highlighted
· Next steps and recommendations
