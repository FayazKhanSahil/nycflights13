# NYC Flights 2013 – Delay Analysis in R

This project explores flight delays for all departing flights from New York City airports in 2013, using the `nycflights13` dataset and R.  
The goal is to understand patterns of departure and arrival delays by airline, destination, time of day, and other factors.

## Dataset

- **Name:** nycflights13  
- **Source:** R package `nycflights13` (not included in this repository – it will be installed from CRAN)  
- **Description:** 336,776 flights departing from NYC (JFK, LGA, EWR) in 2013, with variables such as carrier, origin, destination, distance, departure delay, and arrival delay.

## Project Structure

- `nyc-flights-2013-delay-analysis.R` or `.Rmd` / `.ipynb` – main analysis script/notebook  
- `figures/` (optional) – exported plots used in the analysis  
- `README.md` – project overview (this file)

## Analysis Overview

The analysis focuses on:

- Basic exploration of delay distributions (departure and arrival).  
- Delay patterns by carrier and destination.  
- Delay patterns by month, day of week, and time of day.  
- Identification of routes and airlines with higher on‑time performance versus frequent delays.

Example questions answered:

- Which airlines have the highest average departure delay?  
- How do delays vary over the year (seasonality)?  
- Are certain destinations more prone to long delays?

## Methods and Tools

- **Language:** R  
- **Key packages:**  
  - `nycflights13` – flight data  
  - `dplyr` – data manipulation  
  - `ggplot2` – visualisation  
  - (add any others you used, e.g. `lubridate`, `tidyr`)

The analysis is written as a single R script/notebook so it can be run top‑to‑bottom to reproduce the results.

## How to Run

1. Install R (and optionally RStudio).  
2. Install the required packages in R:

   ```r
   install.packages(c("nycflights13", "dplyr", "ggplot2"))
