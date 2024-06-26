# Predicting Optimal crop for Sowing

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

### Introduction
Measuring essential soil metrics such as nitrogen, phosphorous, potassium levels, and pH value is an important aspect of assessing soil condition. However, it can be an expensive and time-consuming process, which can cause farmers to prioritize which metrics to measure based on their budget constraints.

Farmers in Nigeria have various options when it comes to deciding which crop to plant each season. Their primary objective is to maximize the yield of their crops, taking into account different factors. One crucial factor that affects crop growth is the condition of the soil in the field, which can be assessed by measuring basic elements such as nitrogen and potassium levels. Each crop has an ideal soil condition that ensures optimal growth and maximum yield.

The dataset `soil_measures.csv` contains the following:

- `"N"`: Nitrogen content ratio in the soil
- `"P"`: Phosphorous content ratio in the soil
- `"K"`: Potassium content ratio in the soil
- `"pH"` value of the soil
- `"crop"`: categorical values that contain various crops (target variable).

Each row in this dataset represents various measures of the soil in a particular field. Based on these measurements, the crop specified in the `"crop"` column is the optimal choice for that field.  

## Summary

* The dataset mostly has numerical data
*  our model got an accuracy score of 65% and our analysis revealed that the phosphorous content of the soil emerged as the most influential feature in our predictive model. This underscores the critical role of phosphorous in crop growth and productivity. This highlights the importance of soil testing in sustainable farming practices.

As we continue to refine our model and incorporate more features, we anticipate further improvements in its predictive accuracy, ultimately contributing to the advancement of precision agriculture in Nigeria.

### Built With

```
pandas
seaborn
matplotlib
sklearn
```
