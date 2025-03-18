# Exploratory-Data-Analysis--Cinema-Hall-Ticket
## Project Overview
This project performs an Exploratory Data Analysis (EDA) on a dataset related to cinema hall ticket sales. The analysis aims to understand ticket pricing patterns, customer demographics, and key insights that can help improve business decisions.
Dataset Information
The dataset contains information on cinema hall ticket sales, including:
- **Ticket_ID**: Unique identifier for each ticket.
- **Age**: Age of the customer.
- **Ticket_Price**: The price paid for the ticket.
- **Movie_Genre**: The genre of the movie (Comedy, Drama, Horror, etc.).
- **Seat_Type**: Type of seat (Standard, VIP, etc.).
- **Number_of_Person**: Number of people in the group (Alone, 3, 4, etc.).
- **Purchase_Again**: Whether the customer is likely to purchase again (Yes/No).

## Objectives
1. Identify the range of ticket prices and customer ages.
2. Calculate central tendencies (mean, median, mode) for key variables.
3. Analyze the distribution of ticket prices and customer age.
4. Examine correlations between different numerical variables.
5. Profile non-numerical variables and their impact on sales.
6. Identify trends based on movie genre and seat type.
7. Evaluate customer retention based on the "Purchase_Again" column.

## Analysis Conducted
### 1. Summary Statistics
- **Minimum and Maximum Ticket Prices**: Identified the lowest and highest ticket prices.
- **Minimum and Maximum Age**: Found the youngest and oldest customer.
- **Mean, Median, Mode**: Computed for both ticket price and age.
- **Standard Deviation**: Measured the spread of the data.
- **Quantile Statistics**: Analyzed the distribution across quartiles.

### 2. Data Visualization
- **Distribution Plots**: Created histograms to visualize ticket prices and customer ages.
- **Box Plots**: Used to identify outliers in pricing and customer demographics.
- **Correlation Analysis**: Examined the relationship between ticket price and age.
- **Movie Genre Analysis**: Compared ticket prices across different genres.
- **Seat Type Analysis**: Identified pricing variations between Standard and VIP seats.
- **Customer Retention Trends**: Analyzed factors influencing repeat customers.

## Key Findings & Conclusions
- **Ticket Prices**: The most frequently occurring price was identified using the mode.
- **Age Trends**: Younger and older customers showed different pricing preferences.
- **Movie Genre Influence**: Horror and VIP seats were priced higher on average.
- **Group Size Trends**: Customers in larger groups tended to buy Standard seats.
- **Customer Retention**: Customers who purchased VIP seats or attended dramas were more likely to return.
- **Outliers**: A few extreme values were found in ticket pricing, possibly due to premium seats or VIP screenings.
- **Correlation Insights**: There was no strong correlation between age and ticket price, indicating that ticket pricing may be influenced more by external factors like show timing and seat category rather than customer age.

## Requirements
To replicate this analysis, install the following Python libraries:
```
pip install pandas numpy matplotlib seaborn
```

## Running the Analysis
1. Ensure the dataset `cinema_hall_ticket_sales.csv` is in the same directory as the notebook.
2. Open and run `Cinema_hall_ticket.ipynb` in Jupyter Notebook.

## Future Improvements
- Investigate how movie genres impact ticket prices.
- Analyze peak vs. off-peak hour pricing.
- Segment customers based on purchase behavior to optimize marketing strategies.
- Conduct sentiment analysis on customer feedback to understand preferences better.

