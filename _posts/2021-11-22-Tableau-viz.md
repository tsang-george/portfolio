---
layout: post
author: George Tsang
---
### Using chart types to emphasize different aspects of data
Dataset: The Bank of Canada Commodity Price Index ("BCPI")

First, let's have an overview with a simple line chart.
![BCPI from 1972 to 2021 and forecast](/portfolio-assignment/assets/tableau-viz/line.png)
The energy BCPI is the dominant influence on the overall BCPI, as the overall BCPI trend mirrors closer to the energy BCPI than the index with energy excluded.

Let's say I'm interested to see how the energy BCPI rises and falls over the years. A bar chart showing the differences between years will do the job. The index line chart is overlaid to give context to the differences.
![Differences of Energy BCPI between years](/portfolio-assignment/assets/tableau-viz/difference.png)
We can see that it plunged dramatically twice, in 2009 and 2015. Analysts can use this information for further research. The chart also shows the index can drop more dramatically than it can rise.

While a waterfall chart would be better at highlighting the cumulative effect of changes over the years.
![Energy BCPI from 1972 to 2021](/portfolio-assignment/assets/tableau-viz/waterfall.png)
