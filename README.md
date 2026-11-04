# Slope Shift

**You are the line of best fit.** An IB Computer Science (2027) review game for linear regression (A4 Machine learning).

**Play:** https://ostromaj.github.io/slope-shift/

Count Scatter, a villain made of scattered dots, is flinging outliers to wreck everyone's data. Students steer a living regression line to hug the trend, pop outlier meteors, charge an R² blast, and answer Count Scatter's challenges by using the line itself.

## How a level works

1. **Ride the trend (about 36 s):** data points land one at a time. Students shift and tilt the line to fit them. Residual "tethers" show the vertical gap to each point (green = close, red = far). Outlier meteors that land **pull the line toward them** (each frame is a small gradient-descent step), so students pop them in the air or clean them up after.
2. **Reveal:** the least-squares line appears next to theirs, with both R² values. Fit bonus for getting close.
3. **Three challenges,** answered in-game:
   - **Drag the probe** to a prediction using the regression equation
   - **Shape yourself into a given line** with the readout turned off (reading slope and intercept from the grid)
   - **Click the point** with the largest residual
   - **Sort tags** onto the axes: feature/independent (x) vs label/dependent (y)
   - **Shoot the right card:** slope and intercept meaning in context, matching r to a scatter plot, R² = r², what R² means, calculating a residual, extrapolation, least squares, test sets, regression vs classification, why it's supervised

## Levels

| # | Data | Twist |
|---|---|---|
| 1 | Hours studied vs test score | Meteors start |
| 2 | Temperature vs hot cocoa sold (negative) | Landed outliers pull the line |
| 3 | Screen time vs sleep | Faster meteors |
| 4 | Users online vs server response time | Count Scatter shoves the line |
| 5 | Ads shown vs app downloads | Boss level |

Data is randomly generated each game (with realistic noise), and every answer is computed from that data, so replays differ.

15 challenges per game, ending with a score and a 1 to 7 grade. Answering all 15 correctly is always enough to defeat Count Scatter. R² blasts make up for mistakes. Personal best is saved in the student's browser.

## Controls

- **↑ ↓ / W S** shift the line, **← → / A D** tilt it, or **drag** either end (mouse or touch)
- **Click** meteors, **Space** fires the R² blast, **1 to 4** pick a card, **Enter** continues
- **M** or the Sound button toggles sound (all sounds are synthesized, no files)

No flashing effects. Respects the reduced-motion setting.
