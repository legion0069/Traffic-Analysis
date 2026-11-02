# Traffic Analysis Dashboard

## What this project is about

This project is a simple traffic dashboard that helps people understand how busy a road is at different times of the day and week. It looks at traffic information such as the number of vehicles, the type of vehicles, and traffic patterns over time.

The goal is to make traffic data easier to read and use, even for people who are not familiar with technical tools or data analysis.

## Why this matters

Traffic affects everyone:

- People commuting to work or school
- Drivers planning their route
- City planners trying to reduce congestion
- Transport teams monitoring road conditions

This dashboard helps answer questions like:

- Is the road busy right now?
- Which times of the day are the busiest?
- Are cars, bikes, buses, or trucks making up most of the traffic?
- Is there a better time or route to travel?

## What the app does

The dashboard lets a user:

- Choose a date and time
- Pick a road or route
- View how much traffic there is
- See what types of vehicles are using the road
- Review weekly traffic trends
- Check if road conditions are normal, light, or heavy
- Get a simple suggestion for a better route or travel time

## Main features

### Easy traffic overview
Users can look at a road's traffic at a specific time and instantly see whether traffic is light, normal, or heavy.

### Vehicle breakdown
The app shows how much of the traffic is made up of:

- Cars
- Bikes
- Buses
- Trucks

This helps users understand the type of traffic on the road.

### Weekly pattern view
The dashboard shows how traffic changes throughout the week so users can spot busy days and quieter days.

### Prediction and guidance
Based on the current traffic data, the app can suggest whether a different route or travel time would be better.

## How to run the project

### 1. Install Python
Make sure Python 3.7 or newer is installed on your computer.

### 2. Install the required tools
Open a terminal and run:

```bash
pip install dash plotly pandas
```

These are the main libraries used to build the dashboard and display charts.

### 3. Prepare the traffic data
The project expects a CSV file containing traffic information. In this repository, the file is named:

```text
filtered_output_updated.csv
```

If the file is located somewhere else, update the file path in the script so Python can find it.

### 4. Start the app
Run:

```bash
python app.py
```

After the app starts, it will open a local web page in your browser at:

```text
http://127.0.0.1:8050/
```

## How to use the dashboard

1. Open the app in your browser.
2. Select a date.
3. Choose a time.
4. Pick a road.
5. Click the button to analyze the traffic.
6. Review the charts and status summary.
7. Use the results to decide whether to travel now or wait for a better time.

## Simple example of what you will see

- A pie chart showing the mix of vehicles on the selected road
- A bar chart showing traffic volume across the week
- A line chart showing how traffic changes from weekday to weekday
- A status label showing whether the road is currently normal, heavy, or light

## Who this project is for

This project is useful for:

- Everyday commuters
- Local transport planners
- Traffic monitoring teams
- Students learning about data analysis
- Anyone who wants to understand traffic patterns more clearly

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Summary

In simple terms, this project turns raw traffic data into clear, visual information that anyone can understand. It helps people quickly see when roads are busy, what kind of vehicles are using them, and whether a different time or route might be better.
