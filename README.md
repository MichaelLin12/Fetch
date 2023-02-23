# Fetch Coding Excercise


This repository contains the necessary files requested by the company Fetch for application to their internship program.

The fetch.py file is a python file that serves to use up the specified amount of rewards given all the possible rewards the user has attained. It should be noted that the program will use up the rewards that have negative points first before using up the oldest rewards by time. I do not believe the ordering to which how these rewards should be given out was actually specified clearly. Therefore, I have made the decision that this is how the system would run. If the amount of rewards is negative, then it is assumed that amount is 0 because it is impossible to spend a negative amount of rewards.


To run the fetch.py file, simply download the file and make sure python is installed on your computer

The command to run the file is

python fetch.py <amount> <csv file>

If your on windows or if your on Linux or Mac, it is

python3 fetch.py <amount> <csv file>
