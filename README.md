# Portfolio - Daniel Nunes Vital
### nunesvitald@gmail.com
I have listed below a few projects I have completed using R, Python, and LaTeX. *More projects can be found [here]().*

# Exploring the PNADc  
 In this project, I used the PNADcIBGE package to collect data from the Continuous National Household Sample Survey (PNADc), which surveys general characteristics of the Brazilian population, such as education, income, and labor. Using the obtained microdata, it is possible to calculate multiple variables and rates for the brazilian economy. Among the various information I calculated, some are:  
* Brazilian unemployment rate: 6,32%
* Unemployment rate of the Recife Metropolitan Region: 11,81%
* Average income of the brazilian population: 3267.7 reais, average income of the brazilian woman: 2817.6 reais, average income of the brazilian man: 3605.2 reais and the average income of the black woman in the state of Pernambuco: 2151.2 reais.
* The percentage of white women between the ages of 20 and 30 who are currently unemployed: 8,479%.
* The racial composition of the Brazilian population (approximated values): 42% are white, 10% are black, 0.6% are asians, 46% are brown, 0.4% are indigenous, 0,01% ignored. (The definition of each race is according to the Brazillian institute of Geography and Statistics).

*All the information is from the third quarter of 2024*  
The research offers significant contributions to a wide range of applications. The derived data enables a thorough assessment of the country's economic state. With the package I used, it is possible to select specific variables from the survey without the need to download all the information collected by the IBGE, however, it still is a large quantity of data to work with. 
[Click here to access the code](https://github.com/Danieldnv/portfolio_english/blob/main/codes/pnad_portfolio_en.R)  

# Default on the credit portfolio of individuals and legal entities in Brazil
With the package that accesses data through the Central Bank of Brazil's API, I computed the monthly default rate for both individuals and corporations (please, check the definition) from 2011 to 2024. Utilizing ggplot2, I generated a graph and animated it to depict the dynamic changes in the rates over time.  
<p align="center">
  <img src="images/animated_plot_better.gif" width="50%"> 
</p>  

The Definition according to the website of the Central Bank of Brazil is: *Percentage of the National Financial System's loan portfolio with at least one installment more than 90 days overdue. This includes operations contracted in both the free credit and directed credit segments.* [Verify here](https://dadosabertos.bcb.gov.br/dataset/21083-inadimplencia-da-carteira-de-credito---pessoas-juridicas---total)  

[Click here to access the code](https://github.com/Danieldnv/portfolio_english/blob/main/codes/animated_plot_portfolio.R)  

# Closing prices of Tesla and Apple stocks  
Utilizing the "yfinance" library, I collected information about Tesla and Apple stocks, through Yahoo Finance's APIs. From the obtained data, I separeted the closing prices and generated a visual representation, illustrating, for both stocks, the main impact of the COVID-19 pandemic on the prices and the highest price of both stocks between 01/01/2019 and 10/01/2024. 
It can be observed that, despite a significant drop during COVID-19, the prices of both stocks demonstrated a strong recovery.

<p align="center">
  <img src="images/64ccf5c5-06d2-4960-9183-5b563b4b5b5c.png" width="70%"> 
</p>  

[Click here to access the code](https://github.com/Danieldnv/portfolio_english/blob/main/codes/tesla_apple.ipynb)  

# MGLU3, dollar, and Ibovespa  
In this project, also using "yfinance", I conducted an analysis of BOVA11 (an ETF that tracks the Ibovespa index) and MGLU3 (a company called Magazine Luiza. It is one of the main retailers in Brazil), visualizing the results in a graph, which includes the closing prices and Magazine Luiza's moving average.
Additionally, I collected information about the ibovespa index and the US dollar (quoted in reais). An important point to highlight is the performance following the adjustment of the SELIC rate (Brazil's basic interest rate): The dollar did not respond as expected to a rise in interest rate, indicating that the country's fiscal and political situation is suppressing the effects of the SELIC adjustments. Subsequently, a 1% increase occurred in December 2024, and yet, the dollar reached historic highs.
<p align="center">
  <img src="images/fe304f73-6fe9-44ff-97f8-81afeed51e6f.png" width="70%"> 
</p>  

<p align="center">
  <img src="images/df038b54-5218-4829-abdc-59bac0a7caa6.png" width="100%"> 
</p> 

[Click here to access the code](https://github.com/Danieldnv/portfolio_english/blob/main/codes/stock_dolar_ibov.ipynb)  

# LaTeX  
While not directly related do data science , with the skills I developed while creating these projects, I can provide a great contribution with professional LaTeX documents, which are important for producing high-quality reports for clients or internal company use. This programming language is great for writing  math symbols, equations, plotting graphics, and text, with a technical caracteristic.  

## Calculus - LaTeX  
<p align="center">
  <img src="images/Captura de tela 2025-01-04 133542.png" width="50%"> 
</p>  

[Click here to access the code](https://github.com/Danieldnv/portfolio_english/blob/main/codes/calculustex.tex)  

## Statistics - LaTeX
<p align="center">
  <img src="images/Captura de tela 2025-01-04 133437.png" width="40%"> 
</p>  

[Click here to access the code](https://github.com/Danieldnv/portfolio_english/blob/main/codes/statisticstex.tex)  
