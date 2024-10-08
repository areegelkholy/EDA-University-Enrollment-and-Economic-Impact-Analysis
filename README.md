# University Enrollment and Economic Impact Analysis

This project covers exploratory data analysis and regression models to analyze trends and correlations between university enrollment and economic impact, particularly in Egypt, Ethiopia and Germany between 2005 and 2015.
We use pandas and numpy for handling data and calculations, scikit-learn for regression and matplotlib for plotting.

## Dataset Description

The dataset contains the following:

- **GDP Total, Yearly Growth:** Based on Gapminder‘s GDP per capita that tracks the growth or decline in a nations GDP (1801to 2013)
- **Population:** Total population annually and also calculates expected future
  populations (1800 to 2100)
- **Income per Person (GDP/capita, PPP$ inflation-adjusted):** GDP per person in InternationalDollars adjusted for differences in currencies purchasing power based on 2017 fixed prices and ICP
- **Enrollment in Primary, Secondary and Upper Secondary Education Levels:** Each levels of education is divided into Male, Female, and Total categories with the Total being given as a count while Male and Female is given in the form of a ratio
- **Labor Force Participation & Unemployment:** Gives a count for the number of people in the labor force and the unemployment is the percentage of the labor force that is unemployed
- **Public Expenditure on Education:** Split in to two variables, public expenditure on education given as a percentage of the GDP and basic access to computers by the three levels of education mentioned in the enrollment dataset

## Findings

### Enrollment and Income

### Enrollment and Unemployment

![](/charts/perc-unemployment-across-years.png)

- Ethiopia had lowest unemployment rate despite being the most underdeveloped nation.
- Germany and Egypt had similar unemployment rates dating as far back as 2005, but these continue to drop for Germany but increase for Egypt.
- The increase in unemployment rates for Egypt could be due to political and economic instability.

### Enrollment and Unemployment (in terms of Gender)

![](/charts/avg-unemployment-gender.png)

- Avg. Unemployment rates in Germany are similar between males and females.
- Avg. Unemployment rates in Ethiopia differ by 1.4% with females being less likely to be employed.
- Avg. Unemployment rates in Egypt show a huge discrepancy between male and female unemployment, with females unemployment rates being 3 times more higher.

<img src="/charts/university-enrollment-gender-years.png" width="50%"/><img src="/charts/unemployment-gender-years.png" width="50%"/>

- Males enrollment ratios were slightly higher than Female enrollment ratios in all countries.
- This trend is the same for unemployment rates except for Egypt, where enrollment ratios are significantly different between the two genders.

<img src="/charts/regression-gender.png" />

- After fitting a regression line between enrollment and unemployment, we can see that there is a huge negative correlation between Female enrollment in higher education and unemployment.

### Enrollment and Expenditure

<img src="/charts/expernditure-across-years.png" />

### Contributions

Equal contributions by Areeg Elkholy, Tuqa Aboelwafa and Shahd Eldanasory.
