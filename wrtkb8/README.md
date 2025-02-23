To adjust for the recent introduction of balls 57-75 and normalize historical averages, we employ a weighted average approach. First, we tally the occurrences of each winning ball number and calculate frequencies based on the number of years each ball has been available. This ensures that newer balls are treated differently than those with a longer history.

In the current program, we can introduce a multiplier to adjust probabilities based on the dataset's earliest and most recent dates, along with a cutoff point (2013 in this case). For balls 1-56, available for the entire period, their multiplier is simply 1. For balls 57-75, introduced in 2013, their probabilities are multiplied by (Years from 2002 to 2023) / (Years from 2013 to 2023), which results in a multiplier of approximately 2.1.

We could continue this approach in the future to furthor optimize the algorithm. By refining these algorithms over time, we can increase our chances in the seemingly impossible game that is the lottery.

![Alt Text](https://github.com/thromwill/lottery/blob/main/wrtkb8/img.jpg)
