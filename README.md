# rfm-clustering-supermarket
# Supermarket Customer Segmentation
## Overview

This project focuses on segmenting supermarket customers based on their purchase behavior to improve marketing and product offerings. Using RFM analysis and clustering techniques (K-Means/DBSCAN), the project identifies distinct customer groups with unique purchase patterns, providing insights for targeted marketing campaigns, personalized communications, and optimized product assortments.

## Business Problem

Supermarkets lack deep understanding of customer behavior, leading to generic marketing strategies and missed opportunities for personalized offerings. This project addresses this problem by providing data-driven insights to improve customer engagement, loyalty, and sales.

## Data

The project utilizes a synthetic dataset for demonstration purposes. In a real-world scenario, this would be replaced with actual customer transaction data from supermarkets like Tesco, Sainsbury's, Aldi, and Asda. The data includes customer identifiers, recency of purchase, frequency of purchase, and monetary value of purchases.

## Methodology

1. **RFM Analysis:** Calculates Recency, Frequency, and Monetary scores for each customer to quantify their purchase behavior.
2. **Clustering:** Applies K-Means and DBSCAN clustering algorithms to group similar customers together based on their RFM scores.
3. **Profiling:** Analyzes the characteristics of each customer segment to understand their purchase patterns and preferences.
4. **Visualization:** Creates visualizations to illustrate the customer segments and their relationships.
5. **Findings and Recommendations:** Derives insights from the segmentation and provides actionable recommendations for supermarkets.

## Results

The project identifies distinct customer segments with varying purchase behaviors, such as "Loyal Weekly Shoppers," "Occasional Bulk Buyers," "Price-Sensitive Shoppers," and "New Customers." These insights can be used to:

* **Tailor loyalty programs:** Offer relevant rewards and incentives to specific customer segments.
* **Personalize communications:** Deliver targeted marketing messages based on segment preferences and purchase history.
* **Optimize product assortment:** Stock products that cater to the needs and preferences of each segment.
* **Improve store layout:** Arrange store layouts to guide customers towards products they are likely to purchase.
* **Target promotions:** Offer promotions and discounts to specific segments to maximize impact.

## Potential Impact

Implementing the recommendations derived from this project could potentially increase customer loyalty by 10-15% and boost sales by 5-8%.

## Technologies Used

* Python
* Pandas
* Scikit-learn (K-Means, DBSCAN, StandardScaler)
* Matplotlib
* Plotly

## How to Run

1. Clone the repository: `git clone [repository URL]`
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook Customer_Segmentation.ipynb`

## Contributing

Contributions are welcome! Please open an issue or submit a pull request to suggest improvements or add new features.

## License

This project is licensed under the MIT License.

## Author

Milind Bage
