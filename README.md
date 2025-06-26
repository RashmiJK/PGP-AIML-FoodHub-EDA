![](key_recommendations.jpg)

[Analysis Notebook](analyze_foodhub_orders.ipynb) <br>
[Slide Deck](FoodHubAnalysisSummary.pdf)

## Problem Statement

A food aggregator company aims to enhance its customer experience by understanding the demand patterns across various restaurants and cuisines. As a Data Scientist, your task is to perform an exploratory data analysis (EDA) on the company's order dataset. The analysis should uncover insights into customer preferences, restaurant popularity, order costs, delivery and preparation times, and customer ratings. Your findings will help the company identify trends, address operational bottlenecks, and make data-driven decisions to improve business performance.

### Dataset Overview

The dataset contains detailed information about food orders placed through the company's online portal. Each record includes:

- **order_id**: Unique identifier for each order
- **customer_id**: Identifier for the customer who placed the order
- **restaurant_name**: Name of the restaurant fulfilling the order
- **cuisine_type**: Type of cuisine ordered
- **cost_of_the_order**: Total cost of the order
- **day_of_the_week**: Indicates if the order was placed on a weekday (Monday–Friday) or weekend (Saturday–Sunday)
- **rating**: Customer rating for the order (out of 5)
- **food_preparation_time**: Time (in minutes) taken by the restaurant to prepare the food
- **delivery_time**: Time (in minutes) taken by the delivery person to deliver the food

Your EDA should address key business questions, reveal actionable insights, and provide recommendations for improving customer satisfaction and operational efficiency.

### Quick setup
1. Python virtual environment:

```bash
# Create a virtual environment
python -m venv .venv

# Activate the virtual environment
# On Windows
.venv\Scripts\activate
# On macOS/Linux
source .venv/bin/activate
```

2. Install Required Packages

After activating the virtual environment, install the necessary packages listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

3. Deactivate the Virtual Environment

To deactivate the virtual environment, simply run:

```bash
deactivate
```