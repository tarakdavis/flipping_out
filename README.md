# flipping_out

Chart data about coin flips.

##Objectives
- Understand basic statistics
- Understand the use of different plot types
- Able to use matplotlib
- Able to use Jupyter Notebook
- Able to use the statistics module


##Files included
- A Jupyter notebook: https://github.com/tarakdavis/flipping_out/blob/master/coin-flips.ipynb
- A requirements.txt: use 'pip install -r requirements.txt' to run the files in this repo

##Description

- Create a function to flip a coin. It is up to you to determine what this returns to signify heads or tails.

- Then create a function to run a simulation of flipping a coin n number of times, default 216, recording how many heads and tails it has at different intervals. The intervals are exponential, so record at 20, 21, 22, and so on until you reach n. Record the final number as well.

- Then make a line plot of the difference between heads and tails at each recorded point, and another with the ratio of heads to tails at each recorded point.

- Create these plots again, but as scatter plots with a logarithmic scale for the x-axis.

- Look at the mean and standard deviation of these trials of flipping coins. Flip coins as before, but run 20 trials of 216 each.

- Create a scatter plot of the mean heads/tails ratio at each recorded point, and another scatter plot to plot the standard deviation of the heads/tails ratio at each recorded point, using a logarithmic scale for the x-axis in both.

- Run 100,000 trials of 100 coin flips each. Plot a histogram of the ratio of heads to total flips for each trial. Run 100,000 trials of 1,000 coin flips each and plot that histogram as well.

- Plot a box plot of your results from both the 100 coin flip trials and your results from the 1,000 coin flip trials.
