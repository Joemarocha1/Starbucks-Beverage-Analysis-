# Starbucks-Beverage-Analysis-

Key Features:
Nutrient Group Statistics:

The script groups beverages by their category (Beverage_category) and calculates aggregated statistics (mean, median, standard deviation, minimum, and maximum) for selected nutrient markers such as:
Dietary Fibre (g)
Protein (g)
Calories
Sugars (g)
Correlation Analysis:

Computes the Pearson correlation matrix for key nutritional metrics:
Calories
Total Carbohydrates (g)
Sugars (g)
Total Fat (g)
Protein (g)
Displays a heatmap using seaborn to visualize correlations between nutrients.
Category-Specific Protein Totals:

Groups beverages by Beverage_category and calculates the total protein content for each category.
Generates a bar chart to visualize the protein totals across beverage categories.
Beverage Category Counts:

Counts the number of entries in each Beverage_category.
Outputs a summary table showing beverage category names and their respective counts.
Identifying the Beverage with the Highest Calories:

Identifies the beverage category with the highest calorie count and prints the result.
Visualizations:
A heatmap displaying correlations between key nutrient variables, helping to identify relationships such as:
The impact of calories on sugars and fats.
The relationship between protein and other nutrients.
A bar chart showing the total protein content for each beverage category, highlighting nutrient-rich categories.
How to Run:
Ensure you have the following Python libraries installed:

pandas
numpy
matplotlib
seaborn
Install them using pip if needed:

bash
Copy code
pip install pandas numpy matplotlib seaborn
Provide a CSV file or DataFrame as the input data, ensuring it contains the following columns:

Beverage_category
Protein (g)
Calories
Total Carbohydrates (g)
Sugars (g)
Total Fat (g)
Execute the script to generate:

Nutrient summary tables.
Correlation heatmaps.
Bar charts of protein content.
Expected Outputs:
Tabular summaries of nutrient statistics for each Beverage_category.
A printed correlation matrix and its corresponding heatmap.
A bar chart showing the total protein for each category.
The beverage category with the highest calorie count.
This script is a useful tool for nutritional analysis and visualization, helping identify trends, correlations, and category-specific insights in beverage data.
