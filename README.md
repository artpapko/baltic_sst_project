# Baltic Sea SST Analysis

## 📖 Overview
Sea Surface Temperature (SST) Trends: Use the BSH satellite SST dataset (monthly means of Baltic Sea sea surface temperature, 1990–present)gdk.gdi-de.org.

Download the CSV file (e.g. from BSH) and load it into Pandas. Compute the annual mean SST for each year and plot a time series (line chart) of yearly mean SST to reveal long-term trends. Compute the linear temperature trend (°C/decade) via regression. Also analyze seasonality: create a boxplot or line chart showing the distribution of SST by month.

---

## 🗂 Dataset
[Baltic Sea Sea Surface Temperature (SST)](https://gdk.gdi-de.org/geonetwork/srv/api/records/0891ff1f-b3d9-4b18-bcc9-1449455cc5c7#:~:text=Monthly%20spatial%20mean%20sea%20surface,M14%20department%20of%20the%20BSH)

---

## 🎯 Project Goals
- Line chart of annual mean SST vs. year, with trend line.

- Boxplot (or violin plot) of monthly SST to show seasonal cycle.

- Optionally, annotate anomalies (e.g. highlight 2022). 

Calculations: annual averages, trend slope (e.g. using numpy.polyfit or scipy.stats.linregress), seasonal statistics.

