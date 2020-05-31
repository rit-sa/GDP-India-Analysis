# GDP-India-Analysis

## Project Brief

You are working as the chief data scientist at NITI Aayog, reporting to the CEO. The CEO has initiated a project wherein the NITI Aayog will provide top-level recommendations to the Chief Ministers (CMs) of various states which will help them prioritise areas of development for their respective states. Since different states are in different phases of development, the recommendations should be specific to states as well.
The overall goal of this project is to help the CMs focus on areas which will foster economic development for their respective states. Since the most common measure of economic development is the GDP, you will analyse the GDP of the various states of India and suggest ways to improve it.

## Understanding GDP

Gross domestic product (GDP) at current prices is the GDP at the market value of goods and services produced in a country during a year. In other words, GDP measures the 'monetary value of final goods and services produced by a country/state in a given period of time'.
Per Capita GDP and Income
Total GDP divided by the population gives the per capita GDP (which roughly measures the average value of goods and services produced per person). The per capita income is closely related to per capita GDP (though they are not the same). In general, the per capita income increases when per capita GDP increases and vice-versa. For instance, in the financial year 2015-16, the per capita income of India was Rs 93,293, whereas the per capita GDP of India was $1717 which roughly translates to Rs 1,11,605.

## Data

The data is sourced from (https://data.gov.in/) - an Open Government Data (OGD) platform of India. The download instructions are provided in the next segment. The data for GDP Analysis of Indian States is divided into two parts:
Data I-A: This dataset contains the GSDP (Gross State Domestic Product) data for the states and union territories.
Data I-B: This dataset contains the distribution of GSDP among three sectors: the primary sector (agriculture), the secondary sector (industry), and the tertiary sector (services) along with taxes and subsidies. There is separate dataset for each of the states. You are expected to read the dataset for the available states and join these (in Python) if needed.

## Problem Description

•	Remove the rows: '(% Growth over the previous year)' and 'GSDP - CURRENT PRICES (` in Crore)' for the year 2016-17.
•	Calculate the average growth of states over the duration 2013-14, 2014-15 and 2015-16 by taking the mean of the row '(% Growth over previous year)'. Compare the calculated value and plot it for the states. Make appropriate transformations if necessary to plot the data.
•	Which states have been growing consistently fast, and which ones have been struggling?
•	Curiosity exercise - what has been the average growth rate of your home state, and how does it compare to the national average over this duration?
•	Identify the top-5 and the bottom-5 states based on total GDP
•	Identify the top-5 and the bottom-5 states based on GDP per capita.
•	Find the ratio of highest per capita GDP to the lowest per capita GDP.
•	Plot the contribution of the sub-sectors as a percentage of the GSDP of each category.
•	How does the GDP distribution of the top states (C1) differ from the others?
•	Which sub-sectors seem to be correlated with high GDP?
•	Which sub-sectors do the various categories need to focus on?
