# AI Learn to invest - for Saturdays AI Euskadi.

## Machine Learning project applied to make investing easier to understand for newbies.

### 1. Investing ratios webscrapping. 
We have scrapped with beautifoulSoup investing data related to the companies selected from NYSE market. 

### 2. Dataset creation.
We have randomly simulated 500.000 investments in the last 10 years with a horizon between 1 day and 2 years.  The dataset has been cleaned and prepared for machine-learning modelling by applying categorization or normalization techniques among others. Resulting dataset has been saved into 'datasets/transactions_variables.csv' if you want to use it. 

### 3. Data Modelling and optimization. 
After screening with pycaret which classification models were better for our problem, we have selected Decission Trees for its easier interpretation. Keep in mind that our goal is not to make better investments but to make investment accessible to a broader spectrum of people. 
Decission tree has been optimized and results have been visualized thanks to Graphviz. 

