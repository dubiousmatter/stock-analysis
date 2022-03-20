# VBA Challenge
## Project Goal
The goal of our analysis was to look at stocks in the green energy sector and attempt to discern any patterns based upon price and volume. Our initial cod worked well for the twelve stocks we initially analyzed. However, we needed to refactor the code in order to analyze thousands of stocks as oppose to twelve.

## Results
In order to decrease the run time of our code, we simplified the process by looping through the data once to determine the volume and starting price in it's own loop. We then wrote a loop to find ending prices which also ran a single time. the run time for data from 2017 improved to 0.0742 versus 0.2773 in the original script.

