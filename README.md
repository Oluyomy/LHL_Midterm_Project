# Midterm-Project

## Project/Goals
- COVID-19 created an unprecendented volatile labour market. The goal of the project is to explore the trend in job dataset from World Bank Data and produce insights about the current job market that is valuable for recruitment and selection strategies. The understanding in the job market will assist with resource allocation to assist businesses and goverment regulation to make better informed decision. The project analyze a real life dataset from World Bank Data that included information about employement and development of the top 58 global economies from 2000 to 2016. Gross domestic product (GDP) is the measure of a country economic activities base on the total values of all of the good and services it produces within a specific period time. A statistic model is created to learn about the relationship of educational level within the labor force and unemployement rate regarding to GDP growth.
- Questions for the project framework:
    1. How socio-economic factor affect unemployment rate? 
    2. What socio-economic factor variable will affect the unemployment rate?
    3. How does the GDP growth correlates with the proportion of labor force with basic education?
    4. Are there any significant difference in GDP Growth and the educational attainment of the labor force?
 

## Process

### Step 1: Obtaining data
- Dataset were extracted from World Bank Data. (https://databank.worldbank.org/source/world-development-indicators)
- The dataset included information about employment and development  the top 58 global economies  according to the global economy.(https://www.theglobaleconomy.com/rankings/gdp_share/)
### Step 2: Loading and understanding the dataset.
- Working with Work Bank Data glossary and metadata to understand the each variables included in the dataset. 
- Research and educate on general information about the relationship between employment and the economy.
### Step 3: Data pre-processing.
- Structure the data for efficient analysis.
- Split the raw data frame into 3 smaller dataframe with one general population (df_population) dataframe and 2 gender ( df_female and df_male) dataframe. Create a search function to split the the column contains key word " male" from the raw dataframe. Then filter out "female" to create thefemale dataframe.
- Extract 4 different datasets based on the data structure provided from World Bank Data.
### Step 4: EDA
- Create a pairplot to look at the distributions of different variables and their correlation. Learn the trend and detect outlier or possible factor that can affect the statistical model.
- Utilize tableau to learn about the relationship of educational and GDP growth and how different socio-economic factor affect the unemployment rate.
- Create heatmap to take for a closer look at the corellation.
### Step 5:Building a regression model.
- Since the dataset contain a continuous numerical data, a multiple linear regression is used to estimate the relationship between multiple independent variables and one dependent variable for each questions. The correlation and residual can be used to create a prediction model for the project.



## Results
(Fill in which Option you chose, either 1 or 2. List the dataset you selected for the project if you selected Option 2. Also, discuss the visualizations you created, and why. For Option 2, also identify what your data question was, and how you went through the prompts.)
<img src=![Alt text](<Screenshot 2023-07-14 at 12.49.07 PM.png>)>
### GDP and labor force educational level results:
- The result indicates potential pattern or trend in the dataset that is ploting GDP growth against labor forces with different educational level. There is likely a corellation between GDP and different level of education with R-squared indicate 63% of the variance in the dependent variable (GDP Growth) that can be predicted by independent variables included in the linear regression model. It also show that the model is the best fit for this analysis.
- The second result show the contribution of each educational level to GDP growth and there is no difference in the growth of these educational attainment per year. 



## Challenges 
(discuss challenges you faced in the project)
- 

## Future Goals
(what would you do if you had more time?)
1. Expand the model by using all the variables from the dataset to expand the stats model and perform supervised learning to create a machine learning model that can help assess the current job market and the economy.
2. Create a deployment to help predict the job market condition.
3. Possible question to answer: Are we really heading toward a recession? The current dataset obtain from World Bank Data only information up to 2016. World Bank Data has "World Development Indicator" dataset which contained the job dataset as a subcategories with up-to-date information. Extracting more information and create a stats model to help analysis of the 2008 recession to the current job market and economic condition. 


