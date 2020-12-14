# School_District_Analysis

The purpose of the school district analysis is to provide key statistics through DataFrames for each school in the various districts. The following are the key metrics present in this report:

    1. District summary for 15 schools
    2. Summary per school
    3. Spending summary 
    4. School size summary
    5. School type summary 

The data sets used in this analysis are:
- Data Source: schools_complete.csv, students_complete.csv
- Software: Anaconda, Jupyter Notebook, Python 3.7.9

## Results:
Presented below are the key insights that will aid Maria in understanding the school district landscape. The summary presented will have two types of data: initial data and adjusted data (after removing 9th grade grades from Thomas High School).

### How is the district summary affected?
__Initial Findings:__
![Initial District Summary](https://github.com/patrickryanpo/School_District_Analysis/blob/main/Resources/screenshots/district_summary_df_initial.png)

__Adjusted Findings:__
![Adjusted District Summary](https://github.com/patrickryanpo/School_District_Analysis/blob/main/Resources/screenshots/district_summary_df_adjusted.png)

Looking at the data frame's presented, it can be concluded that the adjustment of Thomas High School 9th grades had little impact on the district summary. The average math score dropped by 0.1 points and the average reading score stayed the same. When it comes to the % passing columns, the percentage for math dropped by 0.2%, the percentage for reading dropped by 0.1%, and the overall passing experienced the highest drop of 0.3%. 

### How is the school summary affeced?
__Initial Findings:__
![Initial School Summary](https://github.com/patrickryanpo/School_District_Analysis/blob/main/Resources/screenshots/per_school_summary_df_initial.png)
__Adjusted Findings:__
![Adjusted School Summary](https://github.com/patrickryanpo/School_District_Analysis/blob/main/Resources/screenshots/per_school_summary_df_adjusted.png)

When it comes to the school summary, we can see that the average scores for both math and reading were significantly impacted registering an average math score of 83.35 and an average reading score of 83.89 for Thomas High School. In line with this, the passing percentages also experienced a significant uptick for math, reading, and overall, at 93%, 97%, and 90%, respectively. 

### How does replacing the ninth graders' math and reasing scores affect Thomas High School's performance relative to the other shcools?

![Top Schools](https://github.com/patrickryanpo/School_District_Analysis/blob/main/Resources/screenshots/top_schools.head_adjusted.png)

As evidenced by the dataframe of the top 5 schools presented above, it is conclusive that replacing the ninth graders' math and reading scores have allowed Thomas High School to be a part of the top 5 performing schools in the district. 

### How does replacing the ninth-grade scores affect the following:

- Math and reading scores by grade
- Scores by school spending
- Scores by school size
- Scores by school type

## Summary 