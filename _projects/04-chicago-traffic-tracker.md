---
title: "Chicago Traffic Tracker"
excerpt: "A data-driven project analyzing semi-real-time congestion levels in Chicago using traffic sensor data and Power BI visualizations."
layout: single
collection: projects
permalink: /projects/chicago-traffic-tracker/
author_profile: true
show_pagination: false
header:
  teaser: /assets/images/teaser-p4.png
---

### Project Overview 📊
Chicago Traffic Tracker is a data analytics project aimed at uncovering semi-real-time congestion trends in the city of Chicago. By leveraging traffic sensor data provided by the Chicago Department of Transportation, we extracted insights that can support transportation planning, mobility improvements, and smarter city infrastructure. The objective is to classify and analyze congestion levels using segment-based speed data from bus-mounted traffic sensors.

### Dataset 🗂️
The project utilizes the **Chicago Traffic Tracker – Congestion Estimates by Segments** dataset. Key features include:

- Over 1,000 segments with real-time updates every 10 minutes
- Congestion estimates as a percentage of free-flow speed
- Average speed, 85th percentile speed, and vehicle count
- Timestamped data with geo-located segments (lat/long)

The data is publicly available via [Chicago’s Open Data Portal](https://data.cityofchicago.org/Transportation/Chicago-Traffic-Tracker-Congestion-Estimates-by-Se/n4j6-wkkf/about_data) in formats such as CSV, JSON, XML, and through an OData feed.

### Tools & Workflow 🛠
We used Microsoft Power BI for data ingestion, transformation, and interactive visualization:
- **Data Ingestion:** OData feed connected directly to Power BI
- **Transformation:** Power Query for filtering, reshaping, and cleaning
- **Visualization:** Custom route map visual to display congestion by segment

![Chicago Traffic Tracker - Workflow](/assets/images/workflow-p4.png)

### Live Dashboard 🔗
You can interact with the live dashboard below:

<iframe title="US Transit Data" width="100%" height="400" src="https://app.powerbi.com/view?r=eyJrIjoiYmZkNzExZWEtMjBlNC00NWY5LWI1OWQtOGRjN2NhOTIzNWJhIiwidCI6IjQxOWY3MTFlLTE2NDktNDA0Mi05YmIxLWRiNTc2ODk0ZDFhOSJ9" frameborder="0" allowFullScreen="true"></iframe>

### ✅ Acknowledgement
This project is a part [ATS](https://www.atsailab.com/) projects catalog, and has been completed in collaboration with my colleague, Abdur Rehman.