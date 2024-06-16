# Marketing Analysis Project


## Overview

The Marketing Data Analysis Project is an in-depth exploration of marketing data aimed at providing valuable insights into user behavior and interactions with a company's e-commerce. The project uses Python, pandas, and Plotly to process, visualize, and interpret marketing data. This analysis is particularly important for the marketing sector as it uncovers critical metrics, conversion rates, and user engagement.

## Objective

The primary objective of this project is to understand and optimize marketing strategies by analyzing user journeys, identifying potential areas of improvement, and measuring the effectiveness of marketing campaigns. The analysis covers various aspects of user behavior, including website visits, navigation, product views, intention to purchase, and checkout rates.

## Key Metrics

#### Website Views

- The project starts by counting the number of unique users who visited the company's website, providing insights into the overall reach.

#### Navigation

- This metric focuses on users who navigated the website, filtering by specific page types like search listing pages and listing pages.

#### Product Views

- Product views are analyzed by tracking users who viewed product pages, helping to understand user interest.

#### Intention to Buy

- The analysis identifies users who demonstrated the intention to purchase by adding products to their carts.

#### Checkout

- The number of users who successfully completed a purchase is counted, offering a critical conversion metric.

#### Conversion Rate

- The conversion rate is calculated as the percentage of users who completed a purchase out of total website visitors, providing a clear measure of campaign success.

#### Conversions per Month

- The project includes a breakdown of conversions (purchases) per month, helping to identify trends and seasonal variations in user behavior.

#### Average Time Spent

- The average time users spend on the website is determined, offering insights into user engagement and content relevance.

#### Return Rate

- The return rate measures the percentage of users who return to the website after their initial visit, helping to gauge user loyalty.

#### Shopping Cart Abandonment Rate

- Shopping cart abandonment is calculated by comparing the number of completed purchases to the number of products added to the cart, revealing potential friction points in the checkout process.

## Acknowledgments

While reviewing this project, it's important to note that certain aspects of the code and data have been altered to preserve the confidentiality of the company. To uphold privacy and security measures, fictitious names have been used for tables and columns. These alterations were made with the utmost care to maintain the integrity of the project while safeguarding sensitive information.

By implementing these changes, I aim to demonstrate my commitment to ethical considerations and my dedication to maintaining the confidentiality of proprietary data. The fictitious elements in no way diminish the significance of the project's technical achievements.

I appreciate your understanding of these precautions and their significance in a real-world business context. If you have any inquiries regarding the methodology or specific technical aspects, please don't hesitate to get in touch.

Thank you for your interest in exploring this project, and I'm available to provide any further insights or clarifications you may require.

## Files

1. [marketing-analysis-project.ipynb](https://github.com/erreduarte/marketing-analysis-project/blob/ddc6b355934dfcc592d6393deca6189c10120ec5/marketing_analysis.ipynb): The Jupyter Notebook where analysis took place.
2. [data_set_da_test.csv](https://github.com/erreduarte/marketing-analysis-project/blob/29528d04de795a736293a49b905dc3ad2fbca42a/data_set_da_test.zip): CSV file used to run the analysis.
   

## Getting Started

To run this analysis on your own data, follow these steps:

### Prerequisites

Before running the analysis, ensure you have the following installed:

- Python (3.x)
- pandas
- Plotly
- Jupyter Notebook (optional)

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/marketing-data-analysis.git

2. **Navigate to the Project Directory:** Change to the project directory:

   ```bash
   cd marketing-data-analysis

3. **Install the Required Python Libraries:** Before running the code in this project, ensure you have the necessary Python libraries installed. You can install them using `pip`, the Python package manager. Here are the required libraries along with the installation commands:

   - **pandas**: A powerful data manipulation and analysis library.
   ```bash
   pip install pandas
   ```

   **or**

      ```bash
   import pandas as pd
   ```
      


   - **numpy**: A library for numerical computations in Python.
   ```bash
   pip install numpy
   ```
   
   **or**

      ```bash
   import numpy as np
   ```
      


   - **plotly**: An interactive graphing library for creating interactive visualizations.
   ```bash
   from plotly import graph_objects as go
   ```
   

   - **datetime**:  Module that provides classes and functions for working with dates and times.
   ```bash
   pip install datetime
   ```
      **or**

      ```bash
   import datetime
   ```


Make sure you have Python and pip installed on your system before running these commands. Once you've installed the required libraries, you should be all set to run the code and explore the project.


4. **Download Your Own Dataset:** Replace the example dataset file path in the code with your own dataset:

   ```bash
   df = pd.read_csv("data_set_da_test.csv")

5. **Run the Jupyter Notebook:** Execute the Jupyter Notebook to perform the analysis:

   ```bash
   jupyter notebook marketing_data_analysis.ipynb

This will open the Jupyter Notebook interface in your web browser, allowing you to execute each step of the analysis.
