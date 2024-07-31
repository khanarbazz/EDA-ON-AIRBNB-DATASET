## EDA ON AIRBNB DATASET

## Description
This project involves performing Exploratory Data Analysis (EDA) on an Airbnb dataset to uncover insights and provide solutions for business challenges. The dataset includes 48,895 rows and 16 columns, containing a variety of data types such as integers, floats, objects, with many nulls and some duplicate values.

Dataset Overview
Dataset Name: airbnb_df
Columns: 16
Rows: 48,895
Missing Values:
0.03% and 0.02% null values in names and host_names columns.
20% null values in last_review and reviews_per_month columns.
Duplicates: None

## Business Objective
"To create a world where anyone can belong anywhere."


## Analysis Results

### Room Preferences and Neighborhood Analysis:
- Preferred room types: Entire home/apt > Private rooms > Shared rooms.
- Identified privacy concerns and stunted growth in shared rooms.

### Price Distribution
- Most bookings fall within the price range of $0 to $2000.
- Opportunities exist to add more rooms in this price range, especially private and entire homes.

### Host Listings Distribution
- Manhattan has the highest number of listings, while Staten Island and the Bronx have the least.
- Listings are concentrated in Manhattan's Financial District.

### Average Booking Price
- The average booking price has declined from 2011 to 2019, with notable variations across neighborhoods.

### Revenue and Growth Visualization
- Revenue shows exponential growth in the last year.
- Seasonal trends observed include growth in the spring and end-of-year months.

### Correlation Analysis
- **Positive Correlations:**
  - Availability, reviews, and minimum nights are positively correlated with price.
- **Negative Correlations:**
  - Latitude is negatively correlated with listings.
  - Longitude is negatively correlated with price.
 
## Python Libraries Used
- **Pandas**
- **Numpy**
- **Seaborn**
- **Matplotlib**

## Operations Performed
- **Data Cleaning:** Handled null values and duplicates.
- **Data Wrangling:** Manipulated and normalized data for analysis.
- **Data Visualization:** Created visualizations to communicate insights.

## Manipulations Performed
- Dropped null values in `names` and `host_names` columns.
- Removed `last_review` and `reviews_per_month` columns to preserve data integrity.

## Solutions and Recommendations
- **Expand Listings:**
  - Increase reach in high-performing areas like Manhattan while exploring growth opportunities in other neighborhoods.
- **Focus on Revenue Growth:**
  - Leverage the observed revenue growth trends to strategize future expansions.
- **Address Privacy Concerns:**
  - Analyze reasons for the lower preference for shared rooms and adjust offerings accordingly.
- **Enhance Business Strategy:**
  - Monitor competitors and maintain competitive advantage in key neighborhoods.

## Conclusion
The analysis indicates that Airbnb is experiencing growth and offers diverse options for various customer segments. Addressing identified challenges will be crucial for sustained business success.

## Files Included
- `airbnb_df.csv`: Original dataset
- `eda_notebook.ipynb`: Jupyter notebook with EDA and visualizations
- `README.md`: Project description and documentation

## License
This project is licensed under the MIT License.


## Installation

1. Clone the repository: `git clone https://github.com/khanarbazz/EDA-ON-AIRBNB-DATASET.git`
2. Navigate into the project directory: `cd EDA-ON-AIRBNB-DATASET`


## Setup
```python
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
from datetime import datetime as dt











