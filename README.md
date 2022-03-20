# VBA Challenge
## Project Goal
The goal of our analysis was to look at stocks in the green energy sector and attempt to discern any patterns based upon price and volume. Our initial cod worked well for the twelve stocks we initially analyzed. However, we needed to refactor the code in order to analyze thousands of stocks as oppose to twelve.

## Results
In order to decrease the run time of our code, we simplified the process by looping through the data once to determine the volume and starting price in it's own loop. We then wrote a loop to find ending prices which also ran a single time. The run time for data from 2017 improved to 0.0742 versus 0.2773 in the original script and can be seen in the image below.

![VBA_Challenge_2017](https://user-images.githubusercontent.com/101157423/159179460-229dc961-b9a1-4920-b2b7-1320993fa220.png)

The run time for data from 2018 improved to 0.0703 versus 0.2812 in the original script and can be seen in the image below.

![VBA_Challenge_2018](https://user-images.githubusercontent.com/101157423/159179581-3f76a078-0dfb-4984-b625-8b02a58054b1.png)

## Summary
Refactoring our code in order to take fewer steps and use less memory would make it possible to analyze a much larger data set than that of our original twelve stocks. The improvement in run time and memory usage would make analyzing the entire market of stocks possible.
