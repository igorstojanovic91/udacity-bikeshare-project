# udacity-bikeshare-project

# Udacity Data Analyst Term 1 Bikeshare Data

This Python script is written for Project 2 (Term 1) of Udacity's Data Analyst Nanodegree (DAND) and is used to explore data related to bike share systems in the United States. It imports data from csv files and computes descriptive statistics from the data. It also takes in users' raw input to create an interactive experience in the terminal to present these statistics.


# How to run the script
You can run the script using a Python integrated development environment (IDE). This script is written in Python 3, so you will need the Python 3.x version of the installer. To read the file, the following software requirements apply:

- You should have Python 3, NumPy, and pandas installed using Anaconda
- A text editor, like Sublime or Atom.
- A terminal application (Terminal on Mac and Linux or Cygwin on Windows).

# Datasets
The datasets used for this script contain bike share data for the first six months of 2017. Some data wrangling has been performed by Udacity's staff before being provided to the students of DAND. After downloading the datasets, place them in the same folder with this Python script.

The data is provided by Motivate, which is a bike share system provider for many cities in the United States. The data files for all three cities contain the same six columns:

- Start Time (e.g., 2017-01-01 00:07:57)
- End Time (e.g., 2017-01-01 00:20:53)
- Trip Duration (in seconds - e.g., 776)
- Start Station (e.g., Broadway & Barry Ave)
- End Station (e.g., Sedgwick St & North Ave)
- User Type (Subscriber or Customer)

The Chicago and New York City files also have the following two columns:

- Gender
- Birth Year

# Files

- chicago.csv
- new_york_city.csv
- washington.csv
- bikeshare.py

# Questions explored

The script answers the following questions about the bike share data:

What is the most popular month for start time?
What is the most popular day of week (Monday, Tuesday, etc.) for start time?
What is the most popular hour of day for start time?
What is the total trip duration and average trip duration?
What is the most popular start station and most popular end station?
What is the most popular trip?
What are the counts of each user type?
What are the counts of gender?
What are the earliest (i.e. oldest person), most recent (i.e. youngest person), and most popular birth years?
