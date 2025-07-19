#### Historical-Automobile-Sales-Analysis-and-Dashboard

## Overview

This project provides an interactive dashboard for analyzing historical automobile sales data, with a special focus on trends during recession periods. Utilizing Python, Dash, Pandas, and Plotly Express, the dashboard enables users to explore and visualize key patterns in automobile sales, advertising expenditure, and economic factors from 1980 to 2023. 

## Features

- **Yearly Sales Analysis:** Visualizes trends in automobile sales across years and months.
- **Recession Period Analysis:** Highlights changes in sales, advertising, and vehicle type performance during recession years.
- **Custom Charts:** Includes line charts, bar charts, and pie charts for intuitive data exploration.
- **Dynamic Filtering:** Select specific years or analysis types via dropdown menus.
- **Responsive Layout:** Clean and informative layout suitable for business and academic use.

## Technologies Used

- Python 3.x
- Dash (for dashboard creation)
- Pandas (for data manipulation)
- Plotly Express (for interactive visualizations)
- HTML/CSS (for dashboard styling)

## Getting Started

### Prerequisites

- Python 3.7+
- pip

By default, the app will launch at `http://127.0.0.1:8050/`.

### Data Source

- The dashboard loads the dataset directly from an IBM cloud-hosted CSV:  
  `https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/historical_automobile_sales.csv`

## Usage

- **Select "Yearly Statistics"** to analyze automobile sales trends for a given year and visualize sales by vehicle type and monthly totals.
- **Select "Recession Period Statistics"** to focus on economic downturn periods, comparing advertising expenditure and vehicle type resilience.
- Explore interactive plots that update based on dropdown selections.

## Dashboard Visualizations

- **Line Chart – Automobile Sales Over Time**
- **Bar Chart – Average Vehicles Sold by Vehicle Type**
- **Pie Chart – Advertising Expenditure Share by Vehicle Type**
- **Bar Chart – Effect of Unemployment Rate on Sales by Vehicle Type**

## Folder Structure

```
.
├── dashboard.py
└── README.md
```

## License

This project is provided for educational and analysis purposes.

Developed as part of a data visualization and analysis assignment, leveraging Matplotlib, Seaborn, Folium, and Dash to communicate key business insights from historical automobile sales data.
