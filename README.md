# Traffic Analysis Dashboard

## What this project is about

This project helps people understand how busy a road is at different times of the day and week. It takes traffic data, turns it into charts, and shows a simple picture of road conditions.

Instead of reading a large spreadsheet, users can quickly see:

- whether traffic is light, normal, or heavy
- how many vehicles are on the road
- which types of vehicles are most common
- how traffic changes across a week
- whether a different route or time might be better

## Why this project matters

Traffic affects everyone every day. People want to know:

- Is the road busy right now?
- Will it take longer to travel during peak hours?
- Are cars, bikes, buses, or trucks making up most of the traffic?
- Is there a better time to travel?

This dashboard makes that information easier to understand and use.

## What the dashboard shows

The app includes:

- a date selector
- a time selector
- a road selector
- a pie chart showing vehicle distribution
- a weekly traffic bar chart
- a weekday traffic line chart
- a traffic status message such as normal, heavy, or light
- simple suggestions for travel planning

## Simple example

If a user selects a road and time, the dashboard can show:

- 45% cars
- 30% bikes
- 15% buses
- 10% trucks

It can also tell the user that traffic is heavy and suggest taking an alternate route or traveling at another time.

## Project structure

This repository contains:

- `README.md` — project guide
- `Traffic_Analysis.ipynb` — main notebook that builds the dashboard
- `filtered_output_updated.csv` — traffic dataset used by the project

## Technologies used

This project uses:

- Python
- Pandas for data handling
- Dash for the interactive web dashboard
- Plotly for charts and visualizations
- Jupyter Notebook for development and execution

## How to run the project

### 1. Install Python
Make sure Python 3.7 or newer is installed.

### 2. Install the required libraries
Open a terminal and run:

```bash
pip install dash plotly pandas jupyter
```

### 3. Open the notebook
Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open the file:

```text
Traffic_Analysis.ipynb
```

### 4. Run all notebook cells
When the notebook opens, run every cell in order. The dashboard will build and load in the browser.

## How to use the app

1. Open the dashboard in your browser.
2. Select a date.
3. Choose a time.
4. Pick a road.
5. Click the Analyze button.
6. Review the charts and traffic status.
7. Use the result to decide whether to travel now or wait.

## What makes this useful

This project is helpful for:

- commuters who want to avoid traffic
- local transport teams monitoring road conditions
- students learning about traffic data analysis
- anyone who wants to understand road patterns through simple visuals

## Important note

This project uses a CSV dataset and is designed for analysis and visualization. It does not connect to live traffic sensors or real-time city traffic systems.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Summary

This project turns raw traffic information into a simple dashboard so people can understand road conditions at a glance. It helps answer basic travel questions quickly and clearly, without needing to read complex data tables.
