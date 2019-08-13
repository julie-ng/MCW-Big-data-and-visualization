# Goal

- web app
- get flight info from users
- send this info to ML model for scoring
- batch score historical and new data

## Value to Customer

Predictive analysis of likelihood of delay to optimize time traveled, e.g. avoid delays to spend with family.

Most users book within 7 days of departure.

# Data Sources

## 1 - United States Department of Transportation (USDOT) Historical Data
30 years of historical flight data provided to them by the 

- `Year`
- `Month`
- `DayOfMonth`
- `Airline`
- `TailNum`
- `FlightNum`
- `OriginAirport`
- `DestinationAirport`
- `ScheduledDepartureTime`
- `ActualDepartureTime`
- `ScheduledArrivalTime`
- `DepartureDelay`
- `AirTime`
- `Distance`
- `Cancelled`
- `CancellationCode`

Additional Fields since 2003

- `CarrierDelay`
- `WeatherDelay`
- `NationalAirSystemDelay`
- `SecurityDelay`
- `LateAircraftDelay`

## 2 - Margie's Travel Data (CSV)

- own customer flight data
- a history of the historical weather condition for each flight as CSV files

## 3- Third party weather data (JSON)

- Weather forecasts around any airport, and provides forecasts up to 10 days. 

## Amount of Data

- currently MT total: 2TB
- each month: additional 1GB

