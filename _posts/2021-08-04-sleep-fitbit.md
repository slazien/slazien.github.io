---
layout: post
title: To sleep or not to sleep? That is (not) the question
---

## Fitbit? More like Sleepbit

My amaxzing girlfriend once had a great idea for a Christmas gift - a small Fitbit. She also got one, which helped us stay fit by encouraging each other to beat each other's stats. A great side effect I discovered only later on is that wearing the Fitbit every day for 1.5 years generated *tons* of detailed sleep tracking data.

The next thing was to get all that data. Knowing how companies tend to make their products as limited as possible in terms of access to your own data, I didn't have much hope. However, it turns out that Fitbit allows you to export all of your data in... JSON and CSV formats! What a news was that to me!

## Exploration time!

To uncover what my sleep data tries to tell me, I did an in-depth analysis of 1.5 years' worth of data. [An interactive Jupyter notebook is available here](https://mybinder.org/v2/gh/slazien/fitbit_analysis/4140b6c56bfb1b448364fc58344d23383c86e387?filepath=notebooks%2Fmain_analysis.ipynb).

### Main conclusions

My analysis:

1. Seems to confirm that going to sleep on time improves sleep quality.

2. Confirms my feeling of "not being a dreamer" - I regularly get less REM sleep than I should for my age. This will have to be further diagnosed by a sleep doctor.

3. Confirms that I'm a "light sleeper" quite literally - the vast majority of my sleep stages are light sleep, sometimes to the point of being disproportionately frequent. This partially explains my occasional tiredness during the day.

4. Shows that the duration of a single deep sleep episode as well as the total deep sleep time per night is highly variable, which helps explain days where I feel very refreshed one day and tired the next one.

Overall, this was a great exercise in data wrangling and using using Plotly to make interactive graphs. I hope you enjoy it as much as I did!