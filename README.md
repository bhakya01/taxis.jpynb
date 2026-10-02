# 🚕 Taxis Dataset — Exploratory Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Seaborn **Taxis dataset**.

The main objective is to clean the dataset, handle missing values, and create different visualizations using **Pandas, Matplotlib, and Seaborn** to understand taxi trip patterns, fares, distances, tips, payment methods, and pickup locations.

---

## 🎯 Objectives

The project covers:

* Loading the Seaborn Taxis dataset
* Checking and handling missing values
* Imputing missing numerical and categorical values
* Removing rows where critical information cannot reasonably be imputed
* Analyzing taxi fares over time
* Comparing fares across pickup boroughs
* Understanding payment methods
* Studying distance and fare distributions
* Analyzing relationships between numerical variables
* Comparing taxi trips across pickup zones and boroughs


## 📊 Dataset

The dataset is loaded directly from Seaborn:

### Dataset Features

Some important columns used in this project include:

* `pickup` — Pickup timestamp
* `dropoff` — Drop-off timestamp
* `pickup_borough` — Pickup borough
* `pickup_zone` — Pickup zone
* `payment` — Payment method
* `distance` — Trip distance
* `fare` — Fare amount
* `tip` — Tip amount
* `tolls` — Toll amount
* `total` — Total trip amount

---

# 🧹 1. Handling Missing Values

First, missing values are checked using:

To identify only columns containing missing values:

### Missing Value Strategy

Different strategies are applied depending on the column type.

### Numerical Columns

For numerical columns, the **median** can be used because it is less affected by extreme values.

### Verify Missing Values

# 📈 2. Matplotlib / Pandas Visualizations

## 📅 Line Chart — Fare Over Time

# 🏙️ 3. Bar Chart — Total Fare by Pickup Borough

# 💳 4. Pie Chart — Payment Method Distribution

# 📏 5. Histogram — Distance Distribution

# 💰 6. Box Plot — Tip Distribution by Pickup Borough


    f
```
