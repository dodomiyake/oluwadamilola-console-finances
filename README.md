# Oluwadamilola Console Finances app

## Overview

Welcome to the Console Finances app! This app is designed to analyze the financial records of a company using JavaScript. It provides key metrics and insights based on the provided financial dataset. The project aims to assist users in understanding the overall financial performance and trends over a given period.

## Table of Contents

- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis Metrics](#analysis-metrics)
- [Contributing](#contributing)

## Project Structure

```
├── starter
│ └── index.js
├── README.md
```

## Installation

**Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/Console-Finances.git
   cd Console-Finances
   ```

## The Console Finances App calculates the following:

- The total number of months included in the dataset.

- The net total amount of Profit/Losses over the entire period.

- The average of the **changes** in Profit/Losses over the entire period.
  * You will need to track what the total change in Profit/Losses are from month to month and then find the average.
  * (`Total/(Number of months - 1)`)

* The greatest increase in Profit/Losses (date and difference in the amounts) over the entire period.

* The greatest decrease in Profit/Losses (date and difference in the amounts) over the entire period.
