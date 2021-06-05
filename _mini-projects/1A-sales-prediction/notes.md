
## Forecasting Problem
* forecasting horizon
* granularity of the y

Tesla: Forecasting the Sales
* `x` = time, price, color, ..., advertisement
* `y` = no. of cars sold per model

> history is a perfect guide to the future

forecasting:
future ~ lag and then really you get all the historical data

$t+1 \sim t + t-1 + t-2 ...$

`x`s =
1. q4: **unit_sales**, price, color, ..., advertisement
2.

| data | n_units_sold |
| -| - |
|2019_q4   | 2020_q2 |
|2019_q3   | 2020_q1 |
|...   |   |

* key pt: lag between x and y

### Another Example
Seasonality:
* su. is a linear combination of all the other weekdays
  - m, t, w, th, fr, sa
    - singular matrix
    - day of the week effect
    - n_categories: n-1
  - dimensionality reduction
    - m, t, w, th, fr, sa
      - w doesn't matter
      - dropping w won't affect su
