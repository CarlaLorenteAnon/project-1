# Summary of Findings

**1. What region of the country has the highest rate of covid cases, covid deaths and heart disease?**
- East coast states had higher previous heart disease problems prior to the pandemic, and thus higher number of covid cases and covid deaths in 2020-2022 (possible limitation of data points in states in the middle west might be affecting the results). 


**2. How did covid cases and covid deaths progressed over time?**
- COVID cases first lightly spiked in Apr 2020 and then highly increased in Feb 2021. COVID deaths spiked in Apr 2020 and increased slightly since then. This concludes that the proportion of covid deaths to covid cases has decreased over time. One possible explanation is the introduction of the vaccine early 2021. 

![covid_over_time](covid_over_time.png)


**3. How does political affiliation affect vaccination, covid deaths, and heart disease?**
- When studying the main differences between the republican and democratic parties, one can see that there is significant differences in terms of vaccination, death rates, income and heart disease.
- As seen in the histogram below, republican counties have significantly lower vaccination rates, and therefore higher COVID death rates than the democratic counties. In the boxplots below, it is also visible that republicans have higher rates of heart disease and lower income.

![political_t-tests](political_t-tests.png)
![political_boxplots](political_boxplots.png)

**4. What is the correlation between Median Income, Vaccination Rates and Covid Deaths?**
- Looking at the rightmost boxplot, we can see that the median income is not correlated with the number of covid cases (0.23 cases per capita, independently of the median income.
![income_v_cases_boxplot](income_v_cases_boxplot.png)

- Nevertheless, as observed in the leftmost boxplot, states with high incomes had lower rates of death by covid. Those whose median income range greater than 70K annually had 0.002 deaths per capita compared with 0.0035 for those counties with median income range below 50K.
![income_v_deaths_boxplot](income_v_deaths_boxplot.png)

**5. How did heart disease rates in the years previous to COVID  affect the number of covid deaths in 2020?**
- When accounting for income, high rates of heart disease made you significantly more likely to have an abnormally high rate of death