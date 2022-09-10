## Magic Mile ("MM")

Notes
- What it is: time trial to predict race performance
- Use a track for distance & slope consistency

### Pace Calculation

- all times are in minutes
- all temperatures in Fahrenheit; note: `TEMP_C = (9/5) * (TEMP_F - 32)`
- for general planning, assuming an 8-10 minute magic mile pace

```text
PACE_LONG_RUN = PACE_MM - 3.5 - [ 30 * ( TEMP - 60 ) ]

TEMP_F: { 0, 5, 10, ... }

PACE_5K = PACE_MM + (33/60)
```

### Instructions

Steps
1. Warm Up (11-12 min)
  1. 5 minute walk
  1. 1 minute run
  1. 1 minute walk
  1. 1/2 mile easy jog
1. Pre-Run
  1. 4 acceleration gliders
  1. 4 cadence drills
  1. 4 minute walk
1. Run
  1. Start at normal running pace --> in 1/4 lap, increase to fast pace (less than all-out)
  1. Total distance: 1 mile (including above 1/4 lap ramp up)
1. Cool Down (reverse of Warm Up: 11-12 min)
  1. 1/2 mile easy jog
  1. 1 minute walk
  1. 1 minute run
  1. 5 minute walk
