PepsiCo Owns Less Than Half of Its Drink Portfolio
# PepsiCo Beverage Portfolio Ownership Dashboard

A Tableau dashboard that analyzes **who actually owns the beverage brands PepsiCo sells**.  
The main takeaway is simple: **PepsiCo owns less than half of the drink portfolio represented in this dashboard**. Much of the portfolio is driven by **distribution agreements and partnerships**, not direct ownership.

## Project Overview

This project was built to challenge the common assumption that PepsiCo owns every beverage brand it sells.  
Using a custom beverage dataset, the dashboard breaks the portfolio into three ownership types:

- **Owned**
- **Distributed**
- **Partnered**

The analysis focuses on beverage categories such as soda, water, tea, sports drinks, energy drinks, coffee, and mixers.

## Dashboard Highlights

### 1. Who Owns Each Drink Category
A stacked bar chart shows ownership by drink category.

Key findings:
- **Water** is fully owned in this dataset
- **Soda** is split between owned and distributed brands
- **Energy drinks** are mostly distributed, not owned
- **Tea** is fully partnered
- **Coffee** appears through partnership rather than direct ownership

### 2. PepsiCo Energy Drinks Ownership Type
A focused panel highlights one of the most interesting findings in the dashboard:
- **Alani Nu** is distributed
- **Celsius** is distributed
- **Rockstar (US)** is distributed
- **Rockstar (International)** is owned

This makes the energy category one of the clearest examples of PepsiCo acting more like a **distribution platform** than a pure owner.

### 3. Ownership Breakdown
The pie chart summarizes the beverage portfolio shown in the dashboard:

- **Owned:** 44.44%
- **Distributed:** 33.33%
- **Partnered:** 22.22%

## Key Insight

**PepsiCo is not just a beverage owner. It is also a major beverage distributor and partner platform.**  
That distinction matters because it changes how the company should be understood in the marketplace. Rather than simply owning a large portfolio, PepsiCo often controls shelf presence and consumer access through distribution and partnership agreements.

## Dataset

This project uses a custom CSV built specifically for Tableau.

### File
- `data/pepsico_beverages_clean.csv`

### Core fields
- `Brand Name`
- `Category`
- `Drink Type`
- `Ownership Type`
- `Region`
- `Parent Company`

### Notes
- **Alani Nu** is included as distributed through Celsius
- **Rockstar** is split between U.S. distribution and international ownership
- **Starbucks RTD**, **Lipton**, and **Pure Leaf** are represented as partnered brands
- **Dr Pepper**, **Crush**, and **Schweppes** are represented as distributed brands in this project dataset

## Tools Used

- **Tableau Public**
- **CSV / Excel**
- Manual data cleaning and categorization

## Repository Structure

```text
pepsico-beverage-ownership-dashboard/
│
├── data/
│   └── pepsico_beverages_clean.csv
│
├── images/
│   └── dashboard.png
│
├── tableau/
│   └── pepsico_beverage_dashboard.twbx
│
└── README.md
```

## Recommended GitHub Uploads

To make the repo look clean and complete, upload:

1. `pepsico_beverages_clean.csv`
2. A screenshot of the final dashboard as `dashboard.png`
3. Your Tableau workbook file (`.twb` or `.twbx`)
4. This `README.md`

## Suggested Repository Name

`pepsico-beverage-ownership-dashboard`

## Suggested GitHub Description

**A Tableau dashboard analyzing which beverage brands PepsiCo actually owns, distributes, and partners on.**

## Suggested Tags

- tableau
- data-visualization
- dashboard
- pepsico
- beverages
- analytics
- csv
- business-intelligence

## Future Improvements

- Expand the dataset to include more international beverage brands
- Add timeline context for major partnerships and distribution changes
- Build a companion dashboard comparing snacks vs beverages
- Publish an interactive Tableau Public version and link it here

## Author

Created by David Bolt.
