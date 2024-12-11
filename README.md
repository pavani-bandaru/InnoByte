# InnoByte
# Amazon Sales Analysis

This repository contains a Jupyter Notebook that performs an exploratory analysis of Amazon sales data. The notebook includes steps for loading, inspecting, and analyzing the dataset.

## Dataset
The dataset used in this notebook is `Amazon sale report.csv`, which includes the following columns:

- **Order ID**: Unique identifier for each order.
- **Date**: Order date.
- **Status**: Current status of the order (e.g., Shipped, Cancelled).
- **Fulfilment**: Indicates whether the order was fulfilled by Amazon or a merchant.
- **Sales Channel**: Sales platform (e.g., Amazon.in).
- **Category**: Product category (e.g., T-shirt, Shirt, Blazzer).
- **Size**: Product size.
- **Courier Status**: Status of the courier service.
- **Qty**: Quantity ordered.
- **Amount**: Order amount.
- **ship-city**, **ship-state**, **ship-country**: Shipping details.

## Prerequisites
To run the notebook, ensure you have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- seaborn

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn
```

## Steps Performed
1. **Data Loading**
   - The dataset is loaded into a pandas DataFrame.

2. **Data Inspection**
   - Displays the structure of the dataset using `info()`.
   - Provides an overview of the data with `head()`.

3. **Null Value Analysis**
   - Identifies missing values in the dataset.

4. **Exploratory Analysis**
   - Analyzes key metrics such as order quantities, amounts, and statuses.
   - Visualizations can be created to uncover patterns in the data.

## Usage
To run the analysis:

1. Clone the repository or download the notebook file.
2. Ensure the dataset (`Amazon sale report.csv`) is in the same directory as the notebook.
3. Open the notebook in Jupyter Notebook or JupyterLab.
4. Run the cells sequentially to perform the analysis.

## Future Enhancements
- Add advanced visualizations for sales trends.
- Perform predictive analysis for sales forecasting.
- Clean and preprocess missing data for deeper insights.

## Contact
For any queries or suggestions, please contact [Your Name/Email].

