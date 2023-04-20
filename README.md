# Comparing Co2 Emissions from Different Countries
The purpose of this project is to compare the emission levels of the top 10 co2 emitters worldwide over the past 50 years. We examined how the numbers from those 10 countries compared to emissions from other countries with a histogram, and a boxplot with a swarm plot. This revealed how drastically the top few countries are responsible for world emissions compared to the rest of the countries. We also investigated how the emissions from those top 10 emitters changed over the past 30 years (1971-2020) and found that all but China have performed consistently while China has increased significantly.

Data:
The data set was pulled from Our World in Data, a large scientific publication with lots of reputable data. The link to my data: https://raw.githubusercontent.com/owid/co2-data/master/owid-co2-data.csv.
Downloaded on 03/29/2023.

Requirements:
We used python through Google's Jupyter notebooks hosted by Colab.

Data Processing:
Our first step for data processing was to clean the non-countries out of the country column. Non-countries are listed in line 3 and they were removed on line 4. We also checked for null values, but had no need to removed any from the data for our graphs. Additionally on line 5 we confirmed that all our data had the correct data type.

Author:
Carl Christopherson

License:
This project is licensed under the terms of the MIT license.
