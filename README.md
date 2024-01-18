# athletic_sales_analysis
The focus of the project was analyze sales data to gain insights into which cities in the U.S. have sold the most athletic wear over two years. The overall intent is for python education, training and learning.

## Project Description
The overall intent is for python education, training and learning. The focus of the project was to analyze sales data to gain insights into which cities in the U.S. have sold the most athletic wear over two years. By running this data we can determine which retailers had the greatest total sales for athletic wear, and which retailers sold the most women's athletic footwear

### Prerequisites

The file with the started code (atheletic_sales_analysis_starter_cod.jbynb, athletic_sales_2020.csv, athletic_sales_2021.csv) and additional steps and comments to complete the project.

### Installing

The repo is public and can be cloned at:
#### https://github.com/itzme-CAVA8816/athletic_sales_analysis

## Testing

Basic testing was used in Visual Studio Code.

The final output was tested for the follwoing funtionality with the associated grading points for the assignment:

Combine and Clean the Data (15 points) 

The two DataFrames have been combined on the rows using an inner join and the index has been reset. (10 points)

The "invoice_date" column has been converted to a datetime data type. (5 points)

Determine which Region Sold the Most Products (15 points) 

A groupby or pivot_table function has been used to create a multi-index DataFrame with the "region", "state", and "city" columns. (10 points)

The aggregated column has been renamed to reflect the aggregation of the data in the column. (1 point)

The results are sorted in ascending order to show the top five regions, including the state and city that sold the most products. (4 points)

Determine which Region had the Most Sales (15 points) 

A groupby or pivot_table function has been used to create a multi-index DataFrame with the "region", "state", and "city" columns. (10 points)

The aggregated column has been renamed to reflect the aggregation of the data in the column. (1 point)

The results are sorted in ascending order to show the top five regions, including the state and city that generated the most sales. (4 points)

Determine which Retailer had the Most Sales (15 points)

A groupby or pivot_table function has been used to create a multi-index DataFrame with the "retailer", "region", "state", and "city" columns. (10 points)

The aggregated column has been renamed to reflect the aggregation of the data in the column. (1 point)

The results are sorted in ascending order to show the top five retailers along with their region, state, and city that generated the most sales. (4 points)

Determine which Retailer Sold the Most Women's Athletic Footwear (20 points) 

A filtered DataFrame is created that shows only women's athletic footwear sales data. (8 points)

A groupby or pivot_table function has been used to create a multi-index DataFrame with the "retailer", "region", "state", and "city" columns. (7 points)

The aggregated column has been renamed to reflect the aggregation of the data in the column. (1 point)

The results are sorted in ascending order to show the top five retailers along with their region, state, and city that had the most women's athletic footwear sales. (4 points)

Determine the Day with the Most Women's Athletic Footwear Sales (15 points) 

A pivot table is created that has the "invoice_date" column as the index and the "total_sales" column assigned to the values parameter. (10 points)

The aggregated column has been renamed to reflect the aggregation of the data in the column. (1 point)

The resample function is used on the pivot table, the data is placed into daily bins, and the total sales for each day is calculated. (2 points)

The results are sorted in ascending order to show the days that generated the most women's athletic footwear sales. (2 points)

Determine the Week with the Most Women's Athletic Footwear Sales (5 points) 

The resample function is used on the pivot table, the data is placed into weekly bins, and the total sales for each week is calculated. (3 points)

The results are sorted in ascending order to show the weeks that generated the most women's athletic footwear sales. (2 points)

## Built With

Visual Code Basic, ChatGPT and GitHub Copilot

## Contributing

* edX Boot Camps LLC

## Authors

* **edX Boot Camps** - *Initial work* 
* **Chris Alvarez** - *final work* 

## License

This project is not licensed. 
