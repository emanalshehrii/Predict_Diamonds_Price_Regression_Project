## Diamonds Price Prediction

### Overview

Diamonds belong to a unique class of products, In this project, we are going to work on a dataset that consists of information about the diamond's price, and other aspects such as Clarity, Carat, etc. When we work on this data, we need to see which columns are important for us and which is not. The main goal of this project is predicting the prices of diamonds based on many features using a regression model.

### Goals

- Which variables are significant in predicting the price of a diamonds
- Build a model to predict the diamonds price.
- Choose the model that give us the best predict. 


### Data Collection

In this project We will obtain our dataset for this study by scraping data from an online website that offers one of the largest collections of diamonds available for sale.
- Web scraping from website https://www.brilliantearth.com/
- Sample size is 119,000 rows and 10 features.

Target: Diamonds price

Features:

- id: unique number of the products
- Shape: outline shape of the diamond
- Color: Diamond color 
- Clarity:is a measure of the purity and rarity of the stone 
- Cut:is a style or design guide used when shaping a diamond for polishing
- Carat: specific unit of measurement used to specify the weight of a diamond
- LW:Length-to-Width Ratio compares the length of a diamond to its width to show how elongated a fancy-shaped diamond appears when viewed from the top.
- Type: types of the diamond (natural,lab)
- Report:certificate of diamond
- Price: The original price.

### Tools

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Patsy
- Sklean
- LinearRegression
- Statsmodels.formula.api
- Statsmodels.api
- BeautifulSoup 
- Selenium webscraping
