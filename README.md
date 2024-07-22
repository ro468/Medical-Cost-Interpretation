**Medical-Cost-Interpretation**  

This project aims to determine the factors influencing insurance costs, including age, gender, BMI, region, smoking habits, and the number of children.   

**Project Overview**  

The goal is to analyze the medical insurance costs and understand why they vary from person to person. The analysis includes statistical methods and data preprocessing techniques to draw meaningful insights.  

**Dataset**  

The dataset includes the following columns:  

Age  
Gender  
BMI (Body Mass Index)  
Region (where the individual resides)  
Smoking habit (smoker or not)  
Children (number of children the individual has)  
Insurance cost   

**Steps Performed**

**Import Libraries:**

Imported necessary libraries for data manipulation, visualization, and statistical analysis.  

**Read the Dataset:**

Loaded the dataset into a pandas DataFrame for analysis.  

**Data Preprocessing:**      

- Handled missing values.  
- Performed descriptive statistics on various factors such as age, gender, BMI, region, smoking habits, and the number of children.  

**Statistical Analysis:**

- Applied the Central Limit Theorem.  
- Used preprocessing techniques and standard normal distribution.  
- Conducted inferential statistics, including:  
* Chi-square test  
* ANOVA test  
* Two-sample Z-test  

**Results:**  

The analysis provided insights into how different factors affect insurance costs. Detailed results and visualizations are available in the project notebooks.


1. **Age Distribution:** Most insured individuals are between 27-51 years old, with a uniform age distribution across the dataset.  

2. **Gender Insights:** Males (674) are slightly more numerous than females (661) among the insured, with males paying $1,500 more in insurance costs on average.  

3. **Regional Analysis:** Southeast region has the highest number of insured individuals (363), with people from this region paying the most for insurance. The Northeast follows, while the West pays slightly less compared to the East.  

4. **Regional Cost Variance:** Southeast residents pay the highest insurance costs, followed by the Northeast. The West pays comparably less than the East.  

5. **Gender and Region Costs:** Males from the Southeast pay the most for insurance.  

6. **BMI Distribution:** BMI is normally distributed with a skew toward higher values. Males and females have similar weight distributions, with most people weighing between 15-53.  

7. **Insurance Charges:** Insurance charges are right-skewed, with most individuals paying between $1,100 and $16,000.  

8. **Smoking vs. Non-Smoking:** Smokers are fewer than non-smokers. Non-smokers pay significantly less than smokers.  

9. **Children and Smoking:** 459 non-smokers and 115 smokers have no children. Conversely, 17 non-smokers and 1 smoker have five children.  

10. **Impact of Smoking:** Smoking has the most significant effect on insurance charges.  

**Inferential Statistics**

-**Chi-Square Test:** No significant effect of gender on smoking habits.  

-**ANOVA Test:** No significant relationship between insurance charges and regions.  

-**Two-Sample Z-Test:** Age and BMI do not significantly affect insurance charges.  

**Confidence Intervals:**

-95% confidence interval for the mean insurance cost: $5,961 to $19,284.  
-90% confidence interval for the mean insurance cost: $7,031 to $18,213.


