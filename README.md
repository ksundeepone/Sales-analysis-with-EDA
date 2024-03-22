**SALES ANALYSIS**

We begin by tidying our dataset, which involves:

- Eliminating rows with missing values
- Deleting rows that meet specific criteria
- Converting column data types (e.g., to numeric, to date/time formats, or using astype)

After refining our dataset, we proceed to the data exploration phase. Here, we delve into five overarching business inquiries related to our dataset:

1. Which month achieved the highest sales, and what was the revenue?
2. Which city had the highest number of products sold?
3. At what times should advertisements be shown to increase the chances of purchases?
4. Which products are frequently purchased together?
5. Which product had the highest sales, and what are the possible reasons for its success?

To address these questions, we employ various pandas & matplotlib techniques, including:

- Merging multiple CSV files into a single DataFrame (using pd.concat)
- Adding new columns
- Extracting new columns by parsing existing ones as strings (.str)
- Applying functions with the .apply() method
- Conducting aggregate analysis with groupby
- Creating bar charts and line graphs for visual analysis
- Annotating our visuals for clarity
