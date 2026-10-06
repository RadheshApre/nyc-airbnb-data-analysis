# 🏠 NYC Airbnb Data Analysis

## 📌 Project Overview

This project performs an exploratory data analysis of Airbnb listings in New York City.

The objective is to understand Airbnb pricing, room types, neighbourhood popularity, reviews, availability, and host listing behaviour.

The analysis was performed using Python and popular data analysis and visualization libraries.

---

## 🎯 Objectives

The project answers the following questions:

- What is the average Airbnb price by neighbourhood group?
- Which room types are most popular?
- Which neighbourhoods have the most listings?
- Which neighbourhoods receive the most reviews?
- How does Airbnb pricing vary across boroughs?
- What is the relationship between price and number of reviews?
- Do hosts with many listings have different pricing or availability?
- What relationships exist between important numerical variables?

---

## 📊 Dataset

The project uses the **New York City Airbnb Open Data** dataset.

The dataset contains information about:

- Airbnb listings
- Hosts
- Neighbourhoods
- Room types
- Prices
- Minimum nights
- Reviews
- Availability
- Geographic coordinates

Dataset source:

**New York City Airbnb Open Data**

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Google Colab
- Jupyter Notebook

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Checked dataset structure
- Identified missing values
- Filled missing `reviews_per_month` values with 0
- Handled missing listing names
- Removed duplicate records
- Converted `last_review` to datetime
- Removed listings with zero price
- Identified and handled extreme price outliers using the IQR method

---

## 📈 Exploratory Data Analysis

The project analyzes:

### Average Price by Neighbourhood Group

Comparison of average Airbnb prices across NYC boroughs.

### Room Type Analysis

Analysis of the popularity and distribution of:

- Entire home/apartment
- Private room
- Shared room

### Neighbourhood Analysis

Identified neighbourhoods with the highest number of Airbnb listings and reviews.

### Price Analysis

Examined Airbnb price distribution and differences between boroughs.

### Reviews Analysis

Studied the relationship between listing prices and the number of reviews.

### Host Analysis

Analyzed whether hosts with multiple listings have different pricing and availability patterns.

### Correlation Analysis

A correlation heatmap was used to examine relationships between numerical variables.

---

## 📊 Visualizations

### Average Price by Borough

![Average Price](screenshots/price_by_borough.png)

### Room Type Distribution

![Room Types](screenshots/room_type_distribution.png)

### Top Neighbourhoods

![Top Neighbourhoods](screenshots/top_neighbourhoods.png)

### Price Distribution

![Price Distribution](screenshots/price_distribution.png)

### Price vs Reviews

![Price vs Reviews](screenshots/price_vs_reviews.png)

### Correlation Heatmap

![Correlation Heatmap](screenshots/correlation_heatmap.png)

---

## 💡 Key Insights

- Airbnb prices vary significantly across NYC neighbourhood groups.
- Entire homes/apartments and private rooms represent the majority of listings.
- Certain neighbourhoods have substantially more Airbnb listings than others.
- Review counts provide an indication of customer activity and listing popularity.
- Price and review relationships can be explored using correlation and scatter plots.
- Hosts managing multiple properties may use different pricing and availability strategies.

> Note: Specific findings should be updated based on the results generated in the final cleaned dataset.

---

## 📁 Project Structure

```text
nyc-airbnb-data-analysis/
│
├── screenshots/
|   |   Required_Libraries.png
│   |   download_dataset.png
│   |   load_dataset.png
│   ├── missing_percentage.png
│   ├── null_values.png
│   ├── describe_data.png
│   └── column_markdown.png
|   |   clean_dataset.png
    |   Test_Visualization.png
│
├── NYC_Airbnb_Data_Analysis.ipynb
├── README.md
└── requirements.txt
