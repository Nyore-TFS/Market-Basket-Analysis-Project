# Market Basket Analysis Project
Market Basket Analysis (MBA) is a powerful technique used to uncover purchasing patterns by analyzing what products customers typically buy together.

## Goal
The main objective of this project was to identify relationships between products to help businesses:

- Optimize product placement.
- Create targeted promotions.
- Enhance the overall customer experience.

## How Does It Work?
MBA examines transaction data to reveal:

- Frequent item combinations.
- Product associations.
- Insights into customer buying habits.

## Real-World Applications
- Optimizing shelf placements and promotional strategies.
- Developing personalized product recommendations.
- Identifying items frequently bought together.

## Business Impact
Insights gained from MBA can help businesses:

- Improve customer experience.
- Offer joint promotions effectively.
- Strategically place items that are often purchased together.

## Project Overview
I began by exploring the dataset in Excel to gain an understanding before diving into analysis. The dataset consists of 541,909 transactions with 8 columns. After loading the data into Python using `pd.read_excel`, I ensured that the data was correctly formatted for
manipulation.
I conducted data cleaning by checking for duplicates and removing empty rows. The dataset was then transformed into a one-hot encoded Boolean array, making it ready for analysis.
I applied the Apriori Algorithm to mine frequent itemsets and generate association rules, using the confidence metric for this analysis.

## Key findings included:

- Highest lift value: 18.59
- Lowest lift value: 6.59
- Confidence values ranging from 80% to 32%

To enhance promotional strategies, I proposed a discount plan using a lift threshold of 5.0 and a confidence threshold of 0.4.

## Conclusion
This project highlights how Market Basket Analysis can help businesses make smarter decisions and improve customer interactions. By using data insights, companies can refine their products and create better experiences for their customers.


