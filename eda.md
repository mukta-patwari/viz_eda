EDA
================
2025-10-02

Import weather data

``` r
data("weather_df")

weather_df =
  weather_df %>% 
  mutate(month = floor_date(date, unit = "month"))
```
