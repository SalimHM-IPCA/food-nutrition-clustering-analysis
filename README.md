# Food Nutrition Clustering Analysis

This academic project explores nutritional patterns in food products using
unsupervised machine learning and association-rule mining.

## Project Objective

The objective is to identify meaningful nutritional groups among food products
and explore relationships between nutritional characteristics.

## Methods

- Data cleaning and missing-value treatment
- Feature selection
- Feature standardisation
- K-Means clustering
- Elbow method
- Silhouette analysis
- Principal Component Analysis (PCA)
- Apriori association-rule mining

## Principal Results

The analysis included 8,788 food records described by 11 nutritional
variables. The highest silhouette score was approximately 0.427,
corresponding to a three-cluster solution.

The clusters represented different nutritional profiles, including
lower-energy foods, energy-dense high-fat foods, and foods richer in
carbohydrates and micronutrients.

## Technologies

- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- mlxtend
- NetworkX
- Jupyter Notebook

## Running the Project

1. Download or clone this repository.
2. Install the required packages:

   `pip install -r requirements.txt`

3. Download the required dataset and place `ABBREV.csv` inside a folder
   named `data`.
4. Open `food_nutrition_analysis.ipynb`.
5. Run all notebook cells.

## Dataset

This project uses the USDA food nutrition dataset. The exact source and
licensing information should be added here before redistributing the dataset.

## Limitations

The results depend on the selected variables, preprocessing decisions,
K-Means assumptions and the thresholds used for association-rule mining.
The clusters should be interpreted as exploratory patterns rather than
definitive nutritional categories.

## Author

Salim Houmaidan  
Master’s student in Applied Artificial Intelligence at IPCA
