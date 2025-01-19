# Marketing Data Analysis Project

![1st](https://github.com/user-attachments/assets/9aea6b5e-9c20-4e62-97d5-2f59869af0a2)

## Overview
The **Marketing Data Analysis Project** is an end-to-end data analysis workflow designed to transform raw marketing data into actionable insights. The project involves data cleaning, sentiment analysis, and visualization using **SQL**, **Python**, and **Power BI**. The dataset focuses on sports equipment such as basketballs, hockey sticks, running shoes, and volleyballs, capturing metrics like customer reviews, clicks, likes, and conversion rates.

## Workflow
### 1. Data Cleaning and Transformation (SQL)
- **Objective**: Prepare raw marketing data for analysis.
- **Process**:
  - **Joins**: Combined multiple tables containing customer interactions, product details, and sales metrics to create a unified dataset.
  - **Window Functions**: Calculated cumulative statistics such as total clicks, likes, and running totals for better insights into customer behavior over time.
  - **Data Cleaning**: Removed duplicates, handled null values, and standardized data formats.
- **Output**: A structured and clean dataset that includes key marketing metrics, ready for further processing.

### 2. Sentiment Analysis (Python)
- **Objective**: Analyze customer reviews to understand their sentiment and feedback.
- **Tools and Libraries**:
  - **pyodbc**: To connect and fetch data from the SQL database.
  - **pandas**: For data manipulation and preprocessing.
  - **nltk** or similar: For performing sentiment analysis.
- **Process**:
  1. Established a connection with the SQL database using `pyodbc`.
  2. Fetched cleaned data for customer reviews and loaded it into Python.
  3. Preprocessed the text data by:
     - Removing special characters and stopwords.
     - Tokenizing and normalizing text.
  4. Applied sentiment analysis techniques to score reviews as positive, negative, or neutral.
  5. Aggregated sentiment scores to calculate overall customer sentiment trends.
  6. Exported the enriched dataset, including sentiment scores, to a CSV file for visualization.

### 3. Data Visualization (Power BI)
- **Objective**: Visualize key marketing metrics and sentiment analysis results.
- **Process**:
  1. Imported the processed CSV file into Power BI.
  2. Designed interactive dashboards to display:
     - **Customer Conversion Rates**: Visualized the journey from clicks to purchases.
     - **Engagement Metrics**: Showcased customer views, clicks, likes, and reviews.
     - **Sentiment Analysis**: Highlighted trends in customer feedback across different products.
  3. Incorporated filters and slicers for detailed exploration of data.
- **Output**: Comprehensive dashboards offering actionable insights into marketing performance and customer behavior.

![2nd](https://github.com/user-attachments/assets/be3f15a7-19de-496c-a05b-e09b5553d158)

## Tools Used
- **SQL**:
  - Database: MySQL/PostgreSQL (or equivalent).
  - Key Features: Joins, window functions, data cleaning techniques.
- **Python**:
  - Libraries: `pyodbc`, `pandas`, `nltk` (or equivalent sentiment analysis library), `matplotlib` for preliminary data visualization.
- **Power BI**:
  - Interactive dashboards with custom visuals and slicers.

## Dataset
The dataset includes detailed marketing data for sports equipment, capturing metrics such as:
- **Product Categories**: Basketballs, hockey sticks, running shoes, volleyballs.
- **Engagement Metrics**: Customer views, clicks, likes, and reviews.
- **Customer Feedback**: Text reviews for sentiment analysis.
- **Conversion Rates**: Data tracking customer journey from interaction to purchase.

## Key Insights
- Identified patterns in customer behavior and engagement metrics across product categories.
- Derived actionable insights from sentiment trends to improve customer satisfaction.
- Provided data-driven visualizations to help stakeholders understand marketing effectiveness.

![3rd](https://github.com/user-attachments/assets/ec20173f-c2f5-47bb-a5b2-1313fbf3e7f8)
