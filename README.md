# Extra-Credit

https://github.com/neil-uwb/Extra-Credit/blob/master/Extra%20Credit.ipynb

Neil Skilton

Dr. Abadi

B ME 450

3/18/2020

# Description

For this project, I tried multiple different approaches, but in the end none worked out for me. The best shot I had at the project was from ingesting the netCDF file and converting it into a .csv file manually. Following this, I was able to isolate time, loaction, and velocity for the wind. Using these values, I plotted the quivers in matplotlib. The plan was to project this plot onto the map from Geoviews. Unfortunately, every attempt made to get this to work failed, and as a result there is no good view on the map. The plot generated has all the quivers on it, but there are too many to see at once, and as a result the plot just looks like a map of the world. I don't know if there is partial credit for this project, but I thought I would submit what I have anyways since I am now out of time.

Note: this code takes a long time to run as it has to read and write large files.
