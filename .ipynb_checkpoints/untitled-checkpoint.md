# Project 1

### Problem Statement

The U.S. Department of Education wants to promote preparation for global competitiveness and intends to announce a new grant program. The hypothesis is that additional funding to the states will increase the states' SAT participation and SAT scores. This project examines the relationship between per pupil funding, the SAT participation and SAT scores for the years 2018 and 2019, with a recommendation on how to best distribute the additional funding. 

### Contents:
- Outside Research
- SAT 2018 Data Import & Cleaning
- SAT 2019 Data Import & Cleaning
- Total Average Spend per Student (USD) Data Import & Cleaning
- Exploratory Data Analysis
- Data Visualization
- Conclusions and Recommendations

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|sat_merged.csv|Name of State|
|sat_18_participation|float64|sat_merged.csv|2018 SAT Percent of Participation by state| 
|sat_18_ebrw|int64|sat_merged.csv|2018 SAT Reading & Writing Mean Score by state| 
|sat_18_math|int64|sat_merged.csv|2018 SAT Math Mean Score by state| 
|sat_18_total|int64|sat_merged.csv|2018 SAT Total Mean Score by state|
|sat_19_participation|float64|sat_merged.csv|2019 SAT Percent of Participation by state| 
|sat_19_ebrw|int64|sat_merged.csv|2019 SAT Reading & Writing Mean Score by state| 
|sat_19_math|int64|sat_merged.csv|2019 SAT Math Mean Score by state| 
|sat_19_total|int64|sat_merged.csv|2019 SAT Total Mean Score by state|
|code|object|sat_merged.csv|State Code| 
|funding_18_dollars|int64|sat_merged.csv|Total Average Spent per Student (USD) in 2018| 
|funding_19_dollars|int64|sat_merged.csv|Total Average Spent per Student (USD) in 2019| 
|dif_participation|float64|sat_merged.csv|SAT Percent of Participation change year-on-year by state| 
|dif_total_score|int64|sat_merged.csv|SAT Total Mean Score change year-on-year by state|
|dif_funding|int64|sat_merged.csv|Total Average Spent per Student (USD) change year-on-year by state| 


### Conclusions
1. SAT scores are inversely correlated with participation rates. As low participation means those who are participating tend to be higher achieving, and high participation means diluted quality of performance.

2. Total Average Spend per Student (USD) is moderate positive linear relationship with SAT Participation rate. The higher spent per student correspond with higher SAT participation rates. This is because better-funded state, the schools would be able to get more resources, increase enrollment in rigorous coursework, providing additional student support (in and out of school), increasing student and family awareness of college accessibility and may expand the expectations of their staff to establish a “college going culture.”

3. Total Average Spend per Student (USD) and SAT Total score clearly demonstrate a weak negative relationship. Total Average Spend per Student has virtually mild effect on SAT scores. In fact the average state saw SAT scores decline by 0.6%. 

### Recommendations
1. The best way to distribute the additional funding is to increase SAT participation rate by incentivize states with improved SAT scores. Thus, the schools able to increase student of college accessibility and expand the expectations of their staff to establish a “college going culture.”
2. Proposed recipients
    - Utah
    - Hawaii 
    - South Dakota
    - Nevada
    - Nebraska
    
### References

1. https://www.empirecenter.org/publications/ny-per-pupil-school-spending-topped-25k-in-2018-19/
2. https://www.silive.com/education/2021/05/how-much-does-new-york-spend-on-each-student.html
3. https://www.insidehighered.com/news/2021/05/26/state-higher-ed-funding-increased-29-last-year
4. https://www.applerouth.com/blog/2019/10/15/sat-annual-report-releases-score-trends-in-2018/
5. https://newsroom.collegeboard.org/over-22-million-students-class-2019-took-sat-largest-group-ever
6. https://www.census.gov/data/tables/2018/econ/school-finances/secondary-education-finance.html
7. https://www.census.gov/data/tables/2019/econ/school-finances/secondary-education-finance.html
8. https://www.hanoverresearch.com/media/Best-Practices-to-Increase-SAT-Participation-1.pdf