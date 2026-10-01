# Taxi Data Analysis

## Project Overview

This project focuses on cleaning, analyzing, and visualizing taxi trip data using Python.

The goal is to understand taxi trip patterns, fares, payment methods, distances, tips, and pickup locations through data analysis and visualization.

## Dataset

The dataset contains 14 columns:

* `pickup` – Pickup date and time
* `dropoff` – Drop-off date and time
* `passengers` – Number of passengers
* `distance` – Trip distance
* `fare` – Trip fare
* `tip` – Tip amount
* `tolls` – Toll amount
* `total` – Total trip amount
* `color` – Taxi color
* `payment` – Payment method
* `pickup_zone` – Pickup location zone
* `dropoff_zone` – Drop-off location zone
* `pickup_borough` – Pickup borough
* `dropoff_borough` – Drop-off borough

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## Data Cleaning

The dataset was cleaned before performing the analysis.

The following steps were performed:

* Checked for missing values
* Identified columns containing missing data
* Converted pickup and drop-off columns to datetime format
* Filled missing numerical values with the median when required
* Filled missing categorical values with the mode
* Checked the dataset again after cleaning

## Data Visualization

### Matplotlib / Pandas

The following visualizations were created:

* **Line Chart** – Average fare over time
* **Bar Chart** – Total fare by pickup borough
* **Pie Chart** – Trips by payment method
* **Histogram** – Distribution of trip distance
* **Box Plot** – Tip distribution by pickup borough

### Seaborn

* **Count Plot** – Number of trips by pickup borough
* **Scatter Plot** – Relationship between distance and fare
* **Heatmap** – Correlation between numerical variables
* **Pair Plot** – Relationships between distance, fare, tip, and total
* **Violin Plot** – Fare distribution by payment method

## Questions Answered by the Visualizations

### Line Chart

* How does the average taxi fare change over time?
* Are there noticeable changes in fares across different days?

### Bar Chart

* Which pickup borough generates the highest total fare?
* How does total fare vary between pickup boroughs?

### Pie Chart

* Which payment methods are most commonly used?
* What is the distribution of trips across payment methods?

### Histogram

* What is the distribution of taxi trip distances?
* Are most trips short or long?

### Box Plot

* How do tip amounts vary across pickup boroughs?
* Are there any unusually high or low tip values?

### Count Plot

* Which pickup borough has the most taxi trips?
* How are trips distributed across boroughs?

### Scatter Plot

* Is there a relationship between trip distance and fare?
* Does fare generally increase as trip distance increases?

### Heatmap

* Which numerical variables have strong relationships with each other?
* How are distance, fare, tip, tolls, and total related?

### Pair Plot

* How do distance, fare, tip, and total relate to each other?
* Do these relationships differ across pickup zones?

### Violin Plot

* How is fare distributed across different payment methods?
* Which payment methods show greater variation in fare?

## Analysis Areas

The project focuses on:

* Taxi trip patterns
* Fare analysis
* Trip distance
* Payment methods
* Tips and tolls
* Pickup boroughs and zones
* Relationships between numerical variables
* Distribution of taxi trips

## Conclusion

This project demonstrates a basic data analysis workflow using Python, from data cleaning and handling missing values to exploratory analysis and visualization.

It provides practical experience with Pandas, Matplotlib, and Seaborn while working with a real-world taxi dataset.
