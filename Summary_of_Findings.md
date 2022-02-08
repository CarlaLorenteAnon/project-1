# Summary of Findings

**1. What region of the country has the highest rate of covid cases, covid deaths and heart disease?**
- The heatmap below is created based on Heart Disease, with a max intensity of 600 out of 100,000 population (0.6% of the population). The red pins show the top 5 places with COVID Cases per Capita and the black dots show the top 5 COVID places with deaths per capita. As seen in the map, east coast states had higher previous heart disease problems prior to the pandemic, and thus higher number of covid cases and covid deaths in 2020-2022 (possible limitation of data points in states in the middle west might be affecting the results). 

![heatmap_heart_disease](output_images/heatmap_heart_disease.png)

- In the boxplots below, we see the distribution of covid deaths and covid cases among states during the pandemic. This also shows how east code states (e.g. Alabama, Arkansas, Florida, Georgia, Kentucky, Mississippi, North Carolina, Pennsylvania, South Carolina) have higher average deaths per capita than Mid East states (e.g. Michigan, Minnesota, Missouri, Nebraska, North Dakota, Utah, Wyoming)

![state_cases_per_capita_N-Z](output_images/state_cases_per_capita_N-Z.png)

![state_cases_per_capita_A-M](output_images/state_cases_per_capita_A-M.png)


**2. How did covid cases and covid deaths progressed over time?**
- COVID cases first lightly spiked in Apr 2020 and then highly increased in Feb 2021. COVID deaths spiked in Apr 2020 and increased slightly since then. This concludes that the proportion of covid deaths to covid cases has decreased over time. One possible explanation is the introduction of the vaccine early 2021. 

![covid_over_time](output_images/covid_over_time.png)


**3. How does political affiliation affect vaccination, covid deaths, and heart disease?**
- When studying the main differences between the republican and democratic parties, one can see that there are significant differences in terms of vaccination, death rates, income and heart disease.
- As seen in the histogram below, republican counties have significantly lower vaccination rates, and therefore higher COVID death rates than the democratic counties. In the boxplots below, it is also visible that republicans have higher rates of heart disease and lower income.

![political_t-tests](output_images/political_t-tests.png)

![political_boxplots](output_images/political_boxplots.png)

**4. What is the correlation between Median Income, Vaccination Rates and Covid Deaths?**
- Looking at the rightmost boxplot, we can see that the median income is not correlated with the number of covid cases (0.23 cases per capita, independently of the median income.

![income_v_cases_boxplot](output_images/income_v_cases_boxplot.png)

- Nevertheless, as observed in the leftmost boxplot, states with high incomes had lower rates of death by covid. Those whose median income range greater than 70K annually had 0.002 deaths per capita compared with 0.0035 for those counties with median income range below 50K.

![income_v_deaths_boxplot](output_images/income_v_deaths_boxplot.png)

**5. How did heart disease rates in the years previous to COVID  affect the number of covid deaths in 2020?**
- When accounting for income, high rates of heart disease made you significantly more likely to have an abnormally high rate of death