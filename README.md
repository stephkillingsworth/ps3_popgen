## ps3_popgen
Problem Set 3: Group popgen

## Problem Set 3:
This should be turned in as a public github repository (for this each person will create their own repository rather than using GitHub Classrooms) with your code either in Python scripts or Jupyter Notebooks.

 

You may work on this in groups or on your own. If you work as a group, you should create the group in Canvas so that you are not assigned to review another submission from your group.

 

Even if you work in groups, each person must submit the assignment in Canvas for the peer review process to work.

 

Note: This assignment will have peer review. It is important to be able to look at someone else's code and figure out what they are doing. It's also important to write code with the idea that someone else will look at it and needs to understand it. While I will take both the peer reviewer's comments on your code and your comments on the peer reviewed code into account when assigning grades, I will be assigning the grade, not the reviewer.

Data:
The data file for this problem set is at: 

  /bsc4452/share/Class_Files/data/CO-OPS_8727520_wl.csv

The file is also in the Class_Files git repo here.Links to an external site.

Metadata:
The file CO-OPS_8727520_wl.csvLinks to an external site. is the water level observations at Cedar Key, FL, from 9/26/2024 to 9/27/2024 during the landfall of Hurricane Helene.

The data were downloaded on 9/29/204 from: https://tidesandcurrents.noaa.gov/Links to an external site.

The columns are fairly self-explanatory:

Date
Time (GMT)
Predicted (ft): Predicted tide level
Preliminary (ft): Observed tide level, preliminary data
Verified (ft): No verified data when downloaded
 

## Problem 1 (5 pts):
Write a script (or Jupyter Notebook code block) that opens the file, uses a for loop to read through the file line by line and, after finishing reading through the file, reports the highest water level and the date and time that was observed.

 

## Problem 2 (5 pts):
Either in a new script or modifying the above script, calculate the lowest, highest and average water level observed during the time period. As above, print the date and time for the lowest and highest readings. 

 

## Problem 3 (5 pts):
Write a script (or Jupyter Notebook) that calculates the fastest rise in water level per 6-minute period between measurements (for this assignment, assume that each line of the dataset is a 6-minute interval) and reports the date and time that was observed and the change in water level from the previous recording.

 

## Problem 4 (5 pts):
Imagine that the file is providing live readings of the water level. Write a script (or Jupyter Notebook) to print a line of text with a warning if any of these events occur:

The water level increases more than 0.25 since the previous recording.
The water level is over 5.0.
No reading is received at a time point.
 

## Peer Review:
Each person will review one other person's answers and leave comments. 

If the code works for the reviewer and produces the desired result, they will say so.

If it doesn't work they will try to figure out why and suggest a fix.

If the reviewer can understand the code, its logic and what you are doing they will say so.

If the reviewer can't understand what you were doing, they will suggest where things are confusing and how to improve.
