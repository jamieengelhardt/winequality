# winequality
## Wine Quality with model building
### Background information:
Wine is an alcoholic drink made from fermented grape juice. The process that goes into making wine involves many chemical properties that make up the quality and taste. For example, wines with lower acidity need more sulfites than wines with higher acidity. The earliest evidence of wine was discovered in the northern Zagros Mountains of Iran. It dated back to the Neolithic period of 8500-4000 B.C. The most widely known types of wine are red wine and white wine. Red wine comes from dark-colored grapes which are harvested, crushed, fermented, and separated from the grape skins and seeds. Some examples of red wine are Cabernet Sauvignon, Merlot, and Zinfandel. White wine comes from green or yellow grapes and is produced the same way as red wine, but with one major difference. In the process of making white wine, the grape skins and seeds are separated before fermentation. Some examples of white wine are Chardonnay, Sauvignon Blanc, and Riesling.
Since the quality and taste of wine are dependent on the chemical makeup, I will be performing multinomial linear regression, decision trees, and random forest to find the best fitting model to predict wine quality and taste. For this project, I will be testing all independent variables with taste as my dependent variable, to compare the accuracy of these models for both white wine and red wine datasets. 
 
### Discussion of data source and nature of the variables involved:
This dataset is from the UCI Machine Learning Repository. There are two separate csv files, one for white wine and one for red wine. The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. I will be using both datasets for my project, so I will be performing six model tests, three models on two datasets. 
Number of Instances: red wine - 1599; white wine - 4898. 
Number of Attributes: 11 + output attribute which is “quality”.
Input variables (based on physicochemical tests):
1 - fixed acidity
2 - volatile acidity
3 - citric acid 
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol
Output variable (based on sensory data): 
12 - quality (score between 0 and 10)
