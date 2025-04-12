# 🚗 Tesla Geopolitical Market Simulator (2025–2035)

A Shiny app simulating the impact of geopolitical scenarios on Tesla's production and market presence worldwide — especially in relation to China.

## 📦 Features

- Dynamic map of Tesla production cities
- Market share and economic impact projections
- Scenario selector (Baseline, Shanghai Exit, Trade War, New India Factory)
- Competitor analysis (Tesla vs BYD vs NIO)
- Add-your-own factory interface
- Interactive data table & narrative generator

## 📸 Screenshot

*Coming soon*

## 🚀 How to Run

1. Install [R](https://cran.r-project.org/) and [RStudio](https://posit.co/download/rstudio-desktop/)
2. Install the required packages:

```r
install.packages(c("shiny", "leaflet", "dplyr", "plotly", "DT", "bslib"))
```

3. Save the code below in a file called `app.R` and run it with `shiny::runApp()`

---

## 📄 Full Code (`app.R`)

<details>
<summary>Click to expand</summary>

```r
# Load libraries
library(shiny)
library(leaflet)
library(dplyr)
library(plotly)
library(DT)
library(bslib)

# Data for Tesla production cities
teslaData <- data.frame(
  city = c("Fremont", "Sparks", "Austin", "Berlin", "Shanghai"),
  lat = c(37.4848, 39.5349, 30.2672, 52.52, 31.2304),
  lon = c(-121.946, -119.7527, -97.7431, 13.405, 121.4737),
  capacity = c(600000, 50000, 250000, 500000, 750000),
  jobs = c(12000, 7000, 10000, 12000, 20000),
  costImpact = c(85, 60, 89, 76, 20),
  revenue = c(24000, 2000, 10000, 20000, 30000),  # $M/year
  isActive = c(TRUE, TRUE, TRUE, TRUE, TRUE)
)

# UI and server definitions here...
# 👇👇👇 paste the entire UI and server code you provided 👇👇👇
```

</details>

---

## ✍️ Author

**Your Name Here**  
*Emerging developer using low-code, AI, and geopolitical forecasting.*

---

## 📌 Notes

- This project is part of a broader simulation exploring China's influence on global EV markets.
- Built with [TailwindCSS](https://tailwindcss.com/) and R Shiny for a sleek hybrid of frontend + modeling.

---

Would you like me to generate the full `.md` file for download or copy-paste?
