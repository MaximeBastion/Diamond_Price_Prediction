# Diamond Price Prediction

## Goal
Training a Machine Learning algorithm that predicts the price of diamonds using their features.

## Data
The dataset contains data on 54 000 diamonds ([data source](https://www.kaggle.com/shivam2503/diamonds)).

For each diamond, we have its:
* price: price in US dollars (\\$326 - $18,823)
* carat: weight of the diamond (0.2 - 5.01 ct)
* cut: quality of the cut (Fair, Good, Very Good, Premium, Ideal)
* color: diamond color, from J (worst) to D (best)
* clarity: a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
* x: length in mm (0 - 10.74 mm)
* y: width in mm (0 - 58.9 mm)
* z: depth in mm (0 - 31.8 mm)
* depth: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43 - 79)
* table: width of top of diamond relative to widest point (43 - 95)

## Notes
In this project, I want to focus on modeling.
I will therefore not go too deep on data exploration & data cleaning.
I am conscious of the fact that these steps are crucial to get the best model, but here my goal is just to practice feature selection & hyerparameter optimization.

#### If you want more explanation or to see the code, please open the notebook file.