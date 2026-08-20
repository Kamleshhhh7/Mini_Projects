# Customer Rating Analysis & Product Recommendation

## About the Project

This is a small project I created while learning Python and working with data.

The project uses customer information stored in a JSON file. I practiced loading the data, cleaning it, handling different rating formats, removing duplicate users, and finding some basic insights from the ratings.

I also added a simple rule-based recommendation based on the customer's rating.

## What I Practiced

* Reading and working with JSON data
* Lists and dictionaries
* Functions
* Basic data cleaning
* Converting rating values into numbers
* Removing duplicate records
* Calculating average ratings
* Finding customers with lower ratings
* Using conditional logic for recommendations

## Project Workflow

```text
Customer Data
     ↓
Load JSON Data
     ↓
Clean the Data
     ↓
Remove Duplicates
     ↓
Analyze Ratings
     ↓
Generate Recommendation
```

## Analysis

The project calculates:

* Average customer rating
* Number of customers with poor ratings
* Percentage of poor ratings
* Customers who gave lower ratings

## Recommendation

A simple rule-based approach is used:

```text
Rating >= 4  → Apple
Rating < 4   → Samsung
```

This is a basic rule-based recommendation and is not a machine learning model.

## Files

* `customer_rating_analysis.ipynb` — Main Jupyter Notebook
* `store_data.json` — Customer data used in the project

## What I Learned

This project helped me understand how to work with structured data in Python and how data can be cleaned and analyzed before using it to make simple decisions.

It also gave me practice in breaking a small problem into different steps instead of writing everything in one place.

## Future Improvements

I would like to improve the recommendation logic and try the project with a larger and more realistic dataset as I learn more about data analysis and machine learning.

---

**Project Type:** Mini Project
**Focus:** Python & Basic Data Analysis
**Status:** Learning Project
