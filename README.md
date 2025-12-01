# Adarsh Ramanujam's Portfolio
This portfolio contains projects Adarsh Ramanujam has done in Python, R, and SQL. He is currently a junior at UNC Chapel Hill who is pursuing data science and seeking experience in AI, Machine Learning, and other coding endeavors. 

# Project 1: Geospatial Analysis of Death in North Carolina: How Income and Flu Vaccinations Contribute to Disparities 
• Multivariate Regression Analysis: Developed and implemented a multiple linear regression model to examine the relationship between county-level death rates (dependent variable) and two predictors: flu vaccination rates and median income (as a proxy for socioeconomic status) across North Carolina counties (2020-2025).
• Statistical Findings and Interpretation: Found that median income was a highly significant predictor of death rates, while the direct effect of flu vaccination rates was not statistically significant when controlling for income. This suggested that socioeconomic factors have a stronger, more statistically significant relationship with overall county death rates in the context of this model.
• Data Preparation and Spatial Visualization: Performed extensive data wrangling, including filtering to isolate North Carolina data, cleaning string variables (e.g., removing commas), and calculating death rates per population. Employed the sf and tmap packages to create choropleth maps visualizing the spatial distribution of flu vaccination rates, death rates, and model residuals across NC counties. 
• Tool Stack: Utilized a comprehensive set of R packages, including tidyverse (for data manipulation), sf and tmap (for spatial data handling and visualization), tigris (for boundary data), and arcpullr (for data extraction), demonstrating proficiency in a diverse analytical and visualization tool stack.

# [Project 2: Marching into Madness](https://github.com/AdarshRamanujam/Marching-Into-Madness)  
### Languages Used: Python  
• Analyzed 20 years of NCAA Division I men’s basketball data (350+ teams) to explore correlations between regular season stats and postseason outcomes  
• Built predictive models using multiple linear regression and k-NN clustering to forecast March Madness placement; achieved 85% accuracy for UNC’s 2025 postseason outcome  
