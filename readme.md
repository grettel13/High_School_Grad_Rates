# High School Graduation Rates

The national average high school graduation rates have had a positive trend over the last few years. While this is positive news, the national average for graduation rates of black students remains considerably under the national average, while white student graduation rates are above that average.

> What aspects of a school may be correlated with the lower high school graduation rates of black students?

This project looks to find more informatin about low black graduation rates. It is beneficial to all for awareness and exposure of the need for both equality and equity in eduation. It identifies where the focus of educators and influencers should be to close the gap between black graduation rates and white graduation rates by identifying in what cases the black graduation rate loses correlation to the overall graduation rate. Future work would dive deeper into that segment of cases.

---
# Approach:

1. Collect data by scraping
2. Analyze/clean data
3. Identify features with highest volume
4. Use linear regression to identify correlations
3. Use Lasso to narrow down features

# Data used:

- Data scraped from [Great! Schools](https://www.greatschools.org/). This is a non-profit that collects information from several government agencies to make available for parents to choose the right school for their child
- National statistics gathered from the National Center for Education Statistics ([NCES](https://nces.ed.gov/)), under the US Department of Education

# Features used:

24 features were selected from 190 based on data available for high volumes of schools.

The following features were provided as % of total students (overall), but also broken down by ethnicity.

| Feature | Breakdown
| --------------- | --------------
| Graduation Rates | Overall, Black, White, Hispanic
| Population Rates | Overall, Black, White, Hispanic
| Suspension Rates | Overall, Black, White
| Chronically Absent Rates | Overall, Black, White
<br/>

Additional School Features:
| Feature | Description
| --------------- | --------------
| Grades | Grades offered at school. Traditional 9-12 grade or "other"
| School Type | Public or Public Charter
| Students | Number of students at school
| Dual Enrollment Rate | % of students enrolled in dual enrollment
| AP course rate | % of students enrolled in AP courses
| Teacher experienced rate | % of teachers with 3 years experience or more
| Avg teacher salary | Average teacher salary
| Teacher cert rate | % of teachers with certification
| Student : Teacher Ratio | Number of students per 1 teacher
| Student : Counselor Ratio | Number of students per 1 counselor

<br/>

# Tools Used:

- Selenium
- Beautiful Soup
- Seaborn
- Matplotlib

