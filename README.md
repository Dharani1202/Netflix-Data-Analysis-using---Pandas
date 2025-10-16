# Netflix Data Analysis Using Pandas

* <a href="https://github.com/Dharani1202/Netflix-Data-Analysis-using---Pandas/blob/main/Netflix%20Data%20Analysis.ipynb"> View the Project </a>

## About

This project focuses on analyzing the **Netflix dataset** using **Python** and **Pandas** to extract meaningful insights about TV shows and movies available on the platform.
The main goal is to explore data patterns, handle missing values, find duplicates, and visualize important trends like release years, popular categories, and top actors/directors.

---

## Tools and Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## Project Overview

The dataset (`netflix.csv`) contains information such as show ID, type, title, director, cast, country, date added, release year, rating, duration, and category.
Each step of the analysis focuses on understanding, cleaning, and exploring this data to uncover insights.

---

## Steps Performed in the Analysis

### 1. Data Loading and Inspection

* Loaded the Netflix dataset using **Pandas**.
* Displayed the first few rows using `head()` and checked data types using `info()`.
* Examined overall structure and size of the dataset.

### 2. Handling Duplicates

* Checked for duplicate records using `duplicated()`.
* Removed duplicate rows, if any, to ensure data accuracy.

### 3. Handling Missing or Null Values

* Checked for null values in each column using `isnull().sum()`.
* Handled missing values appropriately (either removed or filled based on the column type).

### 4. Unique and Duplicate Checks

* Found **unique values** for each column using `unique()` and `nunique()`.
* Ensured no unwanted duplication in key features like titles or IDs.

### 5. Filtering and Grouping Data

* Filtered data to find:

  * All **Movies** released in **2020**.
  * All **TV Shows** released in **India**.
* Grouped the data by **year** and **category** to count releases.

### 6. Key Insights and Analysis Performed

#### a. Director of “House of Cards”

* Extracted the **director name** for the show *“House of Cards”*.

#### b. Year with Maximum Releases

* Found the **year** in which the highest number of **TV Shows and Movies** were released.
* Displayed results using a **bar chart**.

#### c. Total Number of TV Shows and Movies

* Counted how many **TV Shows** and **Movies** are available in the dataset.
* Represented using a **count plot**.

#### d. Movies Released in 2020

* Filtered and displayed all **Movies** released in **2020**.

#### e. TV Shows Released in India

* Displayed only the **titles** of all **TV Shows** that were released in **India**.

#### f. Top 10 Directors

* Identified the **Top 10 Directors** who contributed the highest number of TV Shows and Movies to Netflix.

#### g. Movies with Comedies / UK Category

* Displayed all records where **Category is “Movies”** and **Type is “Comedies”** or **Country is “UK”**.

#### h. Tom Cruise Appearances

* Found in how many **Movies/Shows Tom Cruise** acted.

#### i. Netflix Ratings

* Listed all different **Ratings** defined by Netflix.

#### j. Country with Maximum TV Shows

* Found which **country** has the **maximum number of TV Shows**.

---

## Visualizations

Used **Matplotlib** and **Seaborn** to create:

* Bar charts showing yearly release trends.
* Count plots for categories (Movies vs TV Shows).
* Graphs highlighting top directors, countries, and actor appearances.

---

## Key Results

* Cleaned and refined dataset by removing duplicates and handling missing values.
* Identified most frequent release years and popular categories.
* Found top-performing directors and countries contributing to Netflix content.
* Presented insights visually for easier interpretation.

---

* <a href="https://github.com/Dharani1202/Netflix-Data-Analysis-using---Pandas/blob/main/Netflix%20Data%20Analysis.ipynb"> View the Project </a>



