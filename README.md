# Slope Shift

**You are the line of best fit.** An IB Mathematics: Applications & Interpretation SL review game for linear regression and correlation (Topic 4: Statistics).

**Play:** https://ostromaj.github.io/slope-shift/

Count Scatter, a villain made of scattered dots, is flinging outliers to wreck everyone's data. Students steer a living regression line to hug the trend, pop outlier meteors, charge a fit blast, and answer Count Scatter's challenges by using the line itself.

## How a level works

1. **Ride the trend (about 36 s):** data points land one at a time. Students shift and tilt the line to fit them. Residual "tethers" show the vertical gap to each point (green = close, red = far). Outlier meteors that land **pull the line toward them** (each frame is a small gradient-descent step), so students pop them in the air or clean them up after.
2. **Reveal:** the regression line of y on x (what the GDC gives) appears next to theirs, with Pearson's r and the mean point (x̄, ȳ) marked. Fit bonus for getting close.
3. **Three challenges,** answered in-game:
   - **Drag the probe** to a prediction using the regression equation
   - **Shape yourself into a given line** with the readout turned off (reading gradient and y-intercept from the grid)
   - **Draw a line of best fit by eye** through the mean point (x̄, ȳ)
   - **Click the point** that fits the trend worst (possible outlier)
   - **Sort tags** onto the axes: independent variable (x) vs dependent variable (y)
   - **Shoot the right card:** gradient and y-intercept meaning in context, matching Pearson's r to a scatter plot, describing r in words (strength and direction), the mean point, extrapolation vs interpolation, correlation vs causation, when not to trust a weak r, using the y-on-x line correctly, and why r ≈ 0 doesn't mean "no relationship"

Everything stays inside the SL syllabus: no R² or residual calculations (those are AHL).

## Levels

| # | Data | Twist |
|---|---|---|
| 1 | Hours studied vs test score | Meteors start |
| 2 | Temperature vs hot cocoa sold (negative) | Landed outliers pull the line |
| 3 | Screen time vs sleep | Faster meteors |
| 4 | Users online vs server response time | Count Scatter shoves the line |
| 5 | Ads shown vs app downloads | Boss level |

Data is randomly generated each game (with realistic noise), and every answer is computed from that data, so replays differ.

15 challenges per game, ending with a score and a 1 to 7 grade. Answering all 15 correctly is always enough to defeat Count Scatter. Fit blasts make up for mistakes. Personal best is saved in the student's browser.

## Controls

- **↑ ↓ / W S** shift the line, **← → / A D** tilt it, or **drag** either end (mouse or touch)
- **Click** meteors, **Space** fires the fit blast, **1 to 4** pick a card, **Enter** continues
- **M** or the Sound button toggles sound (all sounds are synthesized, no files)

No flashing effects. Respects the reduced-motion setting.
