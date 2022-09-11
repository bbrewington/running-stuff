# Long Run Pace Calculation

- all times are in minutes
- all temperatures in Fahrenheit; note: `TEMP_C = (9/5) * (TEMP_F - 32)`

```text
PACE_LONG_RUN = PACE_MM - 3.5 - [ 30 * ( TEMP - 60 ) ]

TEMP_F: { 0, 5, 10, ... }

PACE_5K = PACE_MM + (33 / 60)
PACE_10K = 1.15 * PACE-MM
```
