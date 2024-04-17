# Research Proposal: Did the increase in Work From Home during and following the COVID 19 pandemic have an impact on the quantity of Startups being developed?
By Keith Cheung, Danny Hubert, Josh Simon

## Research Question

The inspiration for our final project originates from the impact of the COVID-19 pandemic. We want to analyze how the recent shift in work from home (WFH) during and after the pandemic influences the quantity of startups developed. We plan on using prior work on WFH, employee attitude towards WFH, and various lists of startups to help us understand the relationship between the shift in WFH and the quantity of startups created. First, we need to assess the startups on a macro scale. Generally, we are asking the following questions: 

1. What drives the creation of startups? 
2. Why are startups being developed?  

We plan on looking at general trends across time and comparing the amount of startups developed each year to the proportion of WFH. Some of the specific questions we are answering to assess the amount of startups developed include: 

1. Does the increase in WFH due to the COVID-19 pandemic have a direct impact on the amount of startups that have been developed?
2. How is WFH correlated with the amount of startups created? 

Our hypothesis is that we believe that there will be a strong correlation between the increase of WFH since 2015 and the amount of startups that have been created. With an increase in WFH flexibility, more people are starting their own businesses. Our goal is to find a relationship that shows a correlation between WFH and the amount of startups created. 

## Data
For our dataset, we are using a sample period from 2015 to 2023. We are observing the percentage of WFH in each year and the total number of startups developed. Some of the sample conditions include restricting ourselves to these years and to the amount of startups, not on the logevity or success in order to judge if the increease in flexibility from WFH inspires creation. The necessary variable are % of WFH (WFH total / total workforce) and the total number of startups. Some of the optional variables are sentiment variables for showing WFH being favored over going into the office. Below is a list of prior work: 

- Prior work:
    - https://www.kaggle.com/datasets/mohamedelzeini/the-impacts-of-working-remotely-and-in-an-office/data
         - Shows percentage of people that have experienced work from home and who prefers it.
    - https://www.kaggle.com/code/shubhamksingh/work-from-home-employee-opinions
         - Employee attitude to work from home in Singapore; can be used for comparison to U.S. data.
    - https://www.statista.com/topics/6565/work-from-home-and-remote-work/
         - WFH and Remote Work statistics; share of employees working primarily remotely worldwide 2015-2023
    - https://www.statista.com/topics/4733/startups-worldwide/#topicOverview
         - Global startup statistics & facts; Statistics on high performing startups and their market values, useful for final presentation.
    - https://www.kaggle.com/code/takkimsncn/us-startups-over-time-analysis/notebook
         - Startups since 2020; useful data includes number of startups has been growing since 2020 and entrepreneurs have strong passion for business despite the pandemic.
    - https://www.kaggle.com/datasets/nsfranck/y-combinator-startup-list
         - Startup list; can be used in a similar manner to the "S&P500" file if needed.

## Methodology
In order to find a relationship between the WFH and startup quantity, we will be making a regression model using the data we collected on the quantity of startups from 2015 - 2023 and the trend of WFH from those years. Our X (independent) variable is the statistical amount of WFH from that year and the y (dependent) variable is the amount of startups developed from the corresponding year in order to create a regression model that accurately reflects our predictive relationship. The unit of observation from this regression model will be ###


We plan on continuing our research by going through datasets online as well as reaching out to Lehigh Libraries. Our general plan for obtaining the data is to download the csv and excel files we found online and manipulate them into a dataframes that we can use to test our hypothesis. We would have to merge multiple datasets and use information on variables that would useful for identifying the relationship for WFH and startups. We plan on having an inputs folder with subfolders to keep WFH data and startup data separate during the data cleaning process. More specifically, we would download the raw data and perform eda techniques to identify outliers, missing data, or other unusual data and errors. Then, we will combine and merge all the data into one dataframe that we can use to create visualizations. We are planning on including different visualizations to give us more context to our answers about WFH and the amount of startups created. We are going to use regression across the sample time frame to see if there is a relationship between our variables. 






