# HW3 - AirPassengers Dataset 

## 1. Data File
The dataset file `HW3-AirPassengers.csv` has been prepared. It contains monthly international airline passenger counts (in thousands) from January 1949 to December 1960. The dataset is in CSV format with two columns: Date and Passengers.

---

## 2. Data Dictionary

| Variable Name | Readable Variable Name | Measurement Units       | Allowed Values   | Definition                                              | Synonyms                | Description |
|---------------|------------------------|------------------------|------------------|----------------------------------------------------------|-------------------------|-------------|
| Date          | Observation Month      | YYYY-MM format         | 1949-01 to 1960-12 | Calendar month of observation                           | Time                    | Represents the month and year of the observation |
| Passengers    | Monthly Air Passengers | Thousands of passengers | >= 0             | Number of international airline passengers in a given month | Air Travel, Flight Demand | Recorded monthly passenger counts from 1949–1960 |

---

## 3. Data Collection Methodology
The AirPassengers dataset was originally compiled by the **International Air Transport Association (IATA)**.  
It includes aggregated passenger counts from international airlines, collected on a monthly basis.  
The data was later used by statisticians **Box and Jenkins** as a classic example for time series forecasting, and is now included in the R statistical software as a built-in dataset.

---

## 4. Why This Dataset Intrigues Me
I chose the **AirPassengers dataset** because it is a classic benchmark for time series forecasting.  
The dataset clearly demonstrates both **trend** (increasing passenger counts over time) and **seasonality** (higher travel volumes during certain months, especially summer).  
These characteristics make it ideal for practicing forecasting models such as **ARIMA, exponential smoothing, and seasonal decomposition**.  

