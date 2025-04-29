# Server Health Monitoring Dashboard

## Overview
This project presents a **basic server health monitoring dashboard** built with **Power BI**.  
It simulates a data center's server status snapshot over a given month.

The project is designed to demonstrate:
- Server health status tracking
- Dashboard design principles in Power BI

## Project Motivation
Data center environments rely heavily on constant monitoring of server health.  
This dashboard provides an example of how server usage (memory, cpu, disk) and temperature can be visualized clearly for fast operational awareness.

*Note: The data used is randomly generated using Mockaroo for educational and portfolio purposes.*

## Dataset Details
- **Server Name** (text)
- **timestamp** (date)
- **CPU Usage Percentage** (decimal)
- **Disk Usage Percentage** (decimal)
- **Memory Usage Percentage** (decimal)
- **Status** (calculated field):
  - "Warning" if `CPU Usage Percentage`>85% OR `Temperature (C)` > 75, else "OK"

## Skills Demonstrated
- Data modeling and transformation
- DAX calculations
- Dashboard design and layout in Power BI

## How to View
- Download the `.pbix` file provided in this repository
- Open it using Power BI Desktop (free download available from Microsoft)

## Future Improvements
- Incorporate historical trend data (uptime over time)
- Add server location mapping
- Create automated alert systems for server failures

## Acknowledgements
- [Mockaroo](https://mockaroo.com/) for synthetic data generation
