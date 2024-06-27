# Stopwatch-Shiny-app-in-R-

# I developed this project as part of experiments I conducted using rats. The idea was to create an easy way to start and stop a timer to record the duration a rat experienced a stimulus before reacting with a specific behavioral endpoint.

# This Shiny app is a unique stopwatch for several reasons:

# 1. Tracking Lapsed Time: The application keeps track of the time elapsed since the start of the first trial. This was crucial for my experiments, which were temporally sensitive.

# 2. Ignoring Repeat Keys: I programmed the app to ignore repeat key presses. The idea was to start the timer by pressing down the space bar and to hold it down until the rat initiated the behavioral endpoint. When the rat initiated the endpoint, you would release the space bar. Upon releasing the space bar, the application records a new row with the time taken for each trial. Ignoring repeat key presses prevents the stopwatch from creating new trials while the key is held down, which is not desirable for this experiment.

# 3. Easy Data Download: This stopwatch allows for easy downloading of data into a .csv file, eliminating the need to tediously write down the data manually.
