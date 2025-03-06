# Amazon

# What Are Rich People Purchasing on Amazon?

Have you ever wondered what people with higher incomes spend their money on? Do they shop on the same platforms as the rest of us, or do their preferences tell a different story? This project dives into these questions by analyzing a dataset from the Harvard Dataverse, which tracks longitudinal purchase data from 5,027 Amazon.com users in the U.S. between 2018 and 2022. The findings might challenge your assumptions about how income shapes lifestyles and shopping habits.

## Dataset Overview

The dataset categorizes individuals into the following income brackets:
- Less than $25,000
- $25,000−$49,999
- $50,000−$74,999
- $75,000−$99,999
- $100,000−$149,999
- $150,000 or more

## Methodology

To compare purchasing patterns across income groups, the following steps were taken:
1. **Data Consolidation**: Over 1,000 product titles were consolidated into 10 broader categories for easier analysis.
2. **Order Calculation**: The total number of orders within each category was calculated, grouped by income level.
3. **Data Normalization**: The data was normalized by dividing the total orders by the number of people in each income group to ensure a fair comparison.

## Tools Used

- **Python**: For cleaning and analyzing the dataset.
- **Rawgraphs**: To create SVG files for visualizations.
- **Illustrator**: For editing and refining the visualizations.
- **ai2html**: To create responsive visualizations for web use.

## Key Insights

By analyzing the dataset, this project aims to uncover:
- How purchasing habits differ across income brackets.
- Whether higher-income individuals prioritize different product categories compared to lower-income groups.
- The impact of income on shopping preferences and lifestyle choices.

## Repository Structure

- **data/**: Contains the dataset used for analysis.
- **scripts/**: Includes Python scripts for data cleaning and analysis.
- **visualizations/**: Stores SVG files and responsive visualizations created using Rawgraphs, Illustrator, and ai2html.
- **README.md**: This file, providing an overview of the project.

## How to Use This Repository

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yl54610/Amazon.git
 
