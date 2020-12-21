<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>


# Does the gender gap have any influence on the world wellbeing? A study in pre-covid 19 world.

My final project for the my bootcamp in data analytics 

*[Claudia Stangarone]*


## Content
- [Project Description](#project-description)
- [Hypothesis](#hypotheses-questions)
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Organization](#organization)
- [Links](#links)

## Project Description
It could be very surprising to look at the top ten ranking countries in the Global Gender Gap report. The issue of the year 2020 (referring to the 2019, therefore a pre pandemic world) shows unexpected surprises when it comes to the top ten ranking, especially exploring the subcategories. While exploring the dataset of the 153 countries ranked, I wanted to dive into the aspects that make a county gender equal, but also understand its well-being. To do so I merge the Global Gender Gap report with the World Happiness report in order to have a clear picture from a sociological and economic point of view.

## Hypothesis
* Does the gender inequality have any influence on the world well being?
* And if yes what how it differenciate across the world?

## Datasets
I used two main data sources:
* [The Global Gender Gap Report 2020](https://www.weforum.org/reports/gender-gap-2020-report-100-years-pay-equality) 
* [The World Happiness Report 2020](https://worldhappiness.report/ed/2020/)
* [Demographic data]() (population 2020)
* [Economic]() data (wages differences, % of seats in parliament held by women, Average hours of unpaid domestic work)
 

## Cleaning
Merging the dataframes required some cleaning, because some countries had missing values. Most of all there was an intense cleaning of the name of the countries which could have had a different geographical across the datasets. The cleaning procedure and EDA analysis can be found in the jupyter [notebook](https://github.com/clastanga/A_Study_on_Gender_Equality_and_Happiness/tree/main/Notebooks) called 1_Final_project_Merging datasets.ipynb:


## Analysis
Visual and statistical analysis have been carried out, on Tableau and Python. 
Linear regression analysis and check for linear correlation and statistical significance can be found in the [notebook](https://github.com/clastanga/A_Study_on_Gender_Equality_and_Happiness/tree/main/Notebooks) called 2_Final_project_EDA and statistics.ipynb.
The linear correlation between the global gender gap and the happiness score is extremely significant. The p-value is < 0.0001. However, the data are quite spread and if we divide this plot in quadrants we are talking about 153 countries and from the outlier countries we can infer that not always a gender equal country is happy, and a happy country is gender equal. Of course it is expected that those countries that are in war or in extreme poverty of course cannot perceive themselves as happy. However I reduced the dataset at those country that are actually above the average of the gender gap score and I looked at the correlation in a scatter plot. The correlation is still significant from a statistical point of view: the higher the gender gap score, the happier is the country. 


## Conclusion
To conclude my study, I wanted to see which factors contribute the most to the perception of happiness, keeping in mind that gender equality significantly correlates with happiness and therefore I included the subcategories of the global gender gap in a dataset together with the subcategories of the happiness report to see which of them is more important. I Enlarged the datasets with other datasets (wages, unpaid domestic work, labour participation) and I run a correlation matrix based on the gender gap score. And these are the results considering the 153 countries: Labour force is extremly significant. It is followed by social support, freedom to make life choices and healthy life expectancy which are significant too. Surprisingly GDP per capita seems to be not significant.
In conclusion we can infer that a world where women have equal rights and are included in the political and economic decisions is a happier world
 
## Organization
The repository is organised into 4 different folders:
- [Datasets](https://github.com/clastanga/A_Study_on_Gender_Equality_and_Happiness/tree/main/Datasets) that contains all the datasets used and generated
- [Notebooks](https://github.com/clastanga/A_Study_on_Gender_Equality_and_Happiness/tree/main/Notebooks) that contains the code used to clean and analyse the data
- [Tableau](https://github.com/clastanga/A_Study_on_Gender_Equality_and_Happiness/tree/main/Tableau) where the major part of the work happend, containing the workbook
- [Presentation](https://github.com/clastanga/A_Study_on_Gender_Equality_and_Happiness/tree/main/Presentation) where you can find the pdf of the presentation

## Links
[Repository](https://github.com/clastanga/A_Study_on_Gender_Equality_and_Happiness)  
[Tableau Public(viz)](https://public.tableau.com/profile/claudia1368#!/vizhome/Final_Project_2_16079003596600/cover)  
