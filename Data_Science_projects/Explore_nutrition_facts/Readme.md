<h2><center><font color="blue"><b>Explore nutritional facts</b></font></center></h2>

### **Data Source**

[Open Food Facts](https://www.kaggle.com/openfoodfacts/world-food-facts) dataset from Kaggle available under the [ODbL](https://opendatacommons.org/licenses/odbl/1-0/)

### **Problem Statement**

The objective here is to answer the following questions:

1. Are the number of additives correlated with the nutrition score?
2. How the products are classified according to their risk?
3. Are there countries with more or less risky additives?
4. Which product categories have more risky additives?
5. Which product category is most prone to have many additives?
6. Which are the 5 most common ingredients in the dataset?
7. Which factors cause both a low or a high nutritional score?

The analysis contains also a partial time-series analysis in order to analyze:

* The mean time difference between the datetime of creation and modification of the dataset. 
* The total number of items created each month over the full timeline of the data. 

Note:
-----
The modified version incorporates the following:
1. (Task C): Commas separate most ingredients. Split the ingredients on the commas and then count them to find the most common ones.
2. (Task F): Quantify the strength of the relationship between the nutrition score and the other macro-nutrients. Numerical ordering of all correlations of the nutrition score with the other features.

