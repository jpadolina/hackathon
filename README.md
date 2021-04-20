# hackathon
This repository houses the files and readme for a hackathon competition done in Spring 2021: AggieHacks x Google Cloud COVID-19 Challenge. This competition is open to MBA and MSBA programs around the nation, is 2 weeks long, and is completely virtual. Submissions are judged by a panel of academic and corporate judges.

# Overview
The hackathon calls for an analysis of downstream effects from COVID-19. This can cover any business sector or social setting. It requires the analysis to result in recommendations to drive business or social impact.

My team decided to analyze the effects of COVID-19 on animal shelter outcomes. This was inspired by the boom in adoptions that occurred in the months after COVID-19. Even though animal shelters nationwide had to close and conduct limited adoption appointments, people found themselves at home and with more capacity to care for animals in ways unprecedented. This resulted in empty shelters for the first time in years. However, a common concern is what would happen to owners and their animals once people return to work. In our analysis, we explore trends in adoption and intake of a specific animal shelter as a case study.

# Data Source
Our data comes from Austin Animal Center. Their shelter data extends back to 2013 and is available on Austin's Open Data Portal: https://data.austintexas.gov/
It can also be accessed through this Kaggle page: https://www.kaggle.com/jackdaoud/animal-shelter-analytics?select=Austin_Animal_Center_Outcomes.csv
This dataset has inspired countless data projects throughout the years, which can be found with a Google search and through various Github repos. While many of these projects explore what factors make animals more or less adoptable, our analysis looks more closely at adoption and intake trends rather than animal characteristics.

# Analysis
We performed extensive EDA in Tableau and Python to familiarize ourselves with the data. In our Tableau workbook, more emphasis is placed on the live release rate for different animals. In our Python script, we focus on animal characteristics and visualize trends. One goal of our analysis is to forecast adoption and intake during the COVID-19 pandemic, if the shelter had operated under normal conditions. This was done by cutting off the data just before the shelter closed on 3/16/2020, and forecasting the period of a year afterwards. We then compared that period to the actual trends in Tableau. 

# Conclusions
We observe that both adoptions and intake were reduced compared to expectations under normal conditions; however, intake is taking longer to catch up to expectations, while adoption faced a boon thanks to the surge in interest during the pandemic. Shelters may be empty now but the reality is that there may be more animals being turned down due to lack of capacity, resources, and the need to preserve a favorable live release rate.
The culmination of this analysis resulted in a hypothesis that intake was severely restricted by the pandemic, despite there being a visible need for higher intake due to the pandemic forcing people out of jobs and homes and needing to give up their animals. Additionally, increasing intake leads to more adoptions (the public cannot adopt if there are not enough animals available). We found that the live release rate for cats dipped severely in May 2020 (Tableau workbook, not in repo). Increase intake and adoptions may remedy this. Our pitch deck (not in repo) also lay out other recommendations for practically reaching this goal.

# Technologies Used
EDA done in Tableau
Data cleaning and further EDA done in Python
Modeling done in Google BigQuery
