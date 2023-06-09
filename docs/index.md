---
title: "📚 Project Title"
date: 20 March 2023
date-meta: 20 March 2023
---

# 🤖 Project Title
Should You Drop-Out?

**Team members:** 

- [Leo]()
- [Alberto]()
- [Seyi]()
- [Alua]()

## 📝 Project Description

Our project aims to evaluate the effect of education on professional success. As students, we hope to investigate if education drives our future salaries and whether the time we spend at educational facilities is actually worth it in the long term. 

The relationship between education and income is a well-studied topic in the social sciences, and researchers have used a range of methods to understand this relationship. 

Our main hypothesis is based on the human capital theory. This theory suggests that education is an investment in an individual's human capital, which can lead to higher wages and greater earning potential over their lifetime. Human capital theory suggests that education is a key determinant of an individual's income, and that higher levels of education are associated with higher levels of income.

While regression analysis can be used to estimate the relationship between education and income, given we cannot control for every potential confounder, we will use correlation analysis to examine the strength of the relationship between education and income. 

 Given the limited timeframe of this project, we will focus on Unites States alone to test our hypothesis.

## 📊 Data

For the purpose of conducting our project, we refer to the data from Census.Gov that provides information on educational levels, educational institutions, and salaries in U.S. counties.  First, educational levels represent the percentage of people above 25 years old with Bachelor's degree. Then, from the "Firms" API, we were able to retrieve the number of educational centers per county. Lastly, we used an Excel file from the Economic Bureau to retrieve GDP per county, representative of our salary data. From the Census database, we have chosen two datasets–the Economic Census Survey(ECS) and the American Community Survey(ACS)–containing our variables of interest.

## 📈 Analysis

1) Data Collection: collected data through the API from the Census.gov. 

2) Data Cleaning: removing unnecessary columns, keeping only California states for initial analysis. Here are  the steps taken to clean the data from the ACS survey database:

*screenshot*

Here, we change the type of the variables of interest from the ECS Census Database. Then, we prepared it to be merged with the other pandas dataframe from the ACS data.

*screenshot*

3) Data Merging: merging the three final datasets together, establishing a merging point, and formatting the final pandas dataframe.

We used a list of counties from the census to create pandas dataframe we could merge to the combined Census dataframe to get the name of the counties.

*screenshot*

The first merge was between the two previously mentioned Census databases based on the county number. We had some difficulties due to the ECN dataset including more counties than the ACS dataset, 48 compared to 40 respectively, for the California state. While this reduced our sample size,  we are still able to explore trends in California.

4) Transforming our Data:

*screenshot*

5) Data Visualisation: creating a scatter plot to easily visualise and notice a possible trend between education and salary. 

*screenshots*

## 🖼️ Results

## 🖋️ Conclusions

## 📚 References
