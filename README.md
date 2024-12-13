# Customer Insights and Spending Behavior Analysis

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Visualizations and Insights](#visualizations-and-insights)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Insights](#insights)
- [Contributing](#contributing)
- [License](#license)
  
## Overview
This project focuses on analyzing customer behavior and spending patterns using a comprehensive dataset. Through advanced data visualization and analysis techniques, we aim to uncover actionable insights to improve marketing strategies, optimize product targeting, and enhance customer engagement.

## Features
- **Detailed Data Analysis**: Analyze customer demographics, behavior, and spending patterns.
- **Interactive Visualizations**: Present insights through visually appealing and meaningful plots.
- **Segmentation Analysis**: Explore how attributes like age, education, marital status, and household size affect spending.
- **Campaign Effectiveness**: Examine campaign response rates and their correlation with spending.

## Dataset
The dataset contains the following features:

### **People**
- `ID`: Unique customer identifier
- `Year_Birth`: Year of birth
- `Education`: Education level
- `Marital_Status`: Marital status
- `Income`: Yearly household income
- `Kidhome`: Number of children
- `Teenhome`: Number of teenagers
- `Dt_Customer`: Enrollment date
- `Recency`: Days since last purchase
- `Complain`: Complaints in the last 2 years

### **Products**
- `MntWines`: Spending on wine
- `MntFruits`: Spending on fruits
- `MntMeatProducts`: Spending on meat
- `MntFishProducts`: Spending on fish
- `MntSweetProducts`: Spending on sweets
- `MntGoldProds`: Spending on gold

### **Promotion and Campaigns**
- `NumDealsPurchases`: Number of purchases with discounts
- `AcceptedCmp1` to `AcceptedCmp5`: Campaign acceptance indicators
- `Response`: Acceptance of the most recent campaign

### **Place**
- `NumWebPurchases`: Purchases via the website
- `NumCatalogPurchases`: Purchases through catalogs
- `NumStorePurchases`: Purchases in-store
- `NumWebVisitsMonth`: Website visits in the last month

## Visualizations and Insights
### Key Visualizations
1. **Age Distribution**: Analyzed age groups of customers to identify the dominant age range.
2. **Spending by Product**: Highlighted spending trends across product categories.
3. **Campaign Effectiveness**: Assessed campaign response rates and correlations.
4. **Website Visits vs Online Purchases**: Explored the relationship between website visits and purchases.
5. **Income vs Total Spending**: Examined how income correlates with overall spending.
6. **Spending by Household Size**: Showed spending variations by household composition.
7. **Education and Spending**: Analyzed spending behavior by education levels.

### Insights
- Older customers spend significantly more, especially on wine and meat products.
- Single-person households have the highest spending across most categories.
- Recent campaigns have better response rates, indicating improved targeting.
- Spending on luxury items like wine and gold is correlated with higher income.
- Customers with complaints show lower spending, emphasizing the importance of customer satisfaction.

## Technologies Used
- **Python**: For data processing and visualization.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib**: Plotting and visualization.
- **Seaborn**: Advanced statistical visualizations.
- **NumPy**: Numerical data handling.


## Usage
- Use the `Consumer Personality Analysis.py` script to generate all visualizations.
- The results and visualizations are saved in the `output/` directory for further use.

## Contributing
We welcome contributions to improve the analysis and add more features. To contribute:
1. Fork the repository.
2. Create a feature branch:
    ```bash
    git checkout -b feature-name
    ```
3. Commit your changes and push them:
    ```bash
    git push origin feature-name
    ```
4. Create a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
