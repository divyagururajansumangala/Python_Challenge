# Python_Challenge
 
# Python Homework - Py Me Up, Charlie

## Background

Well... I've made it!

It's time to put away the Excel sheet and join the big leagues. Welcome to the world of programming with Python. In this homework assignment, I'll be using the concepts I've learned to complete the **two** Python Challenges, PyBank and PyPoll.

Both of these challenges encompasses a real-world situation where the newfound Python scripting skills can come in handy. These challenges are far from easy so expect some hard work ahead!

### Before  Beginning

* Create a new repository for this project called `python-challenge`. **Do not add this homework to an existing repository**.

* Clone the new repository to my computer.

* Inside the local git repository, create a directory for both of the  Python Challenges. Use folder names corresponding to the challenges: **PyBank** and  **PyPoll**.

* Inside of each folder that I just created, add the following:

  * A new file called `main.py`. This will be the main script to run for each analysis.
  * A "Resources" folder that contains the CSV files  used. Make sure the script has the correct path to the CSV file.
  * An "analysis" folder that contains the text file that has the results from the analysis.

* Push the above changes to GitHub or GitLab.

## PyBank

![Revenue](Images/revenue-per-lead.png)

* In this challenge, I am tasked with creating a Python script for analyzing the financial records of your company. I will give a set of financial data called [budget_data.csv](PyBank/Resources/budget_data.csv). The dataset is composed of two columns: `Date` and `Profit/Losses`. (Thankfully, the company has rather lax standards for accounting so the records are simple.)

* My task is to create a Python script that analyzes the records to calculate each of the following:

  * The total number of months included in the dataset

  * The net total amount of "Profit/Losses" over the entire period

  * The average of the changes in "Profit/Losses" over the entire period

  * The greatest increase in profits (date and amount) over the entire period

  * The greatest decrease in losses (date and amount) over the entire period

* As an example, your analysis should look similar to the one below:

  ```text
  Financial Analysis
  ----------------------------
  Total Months: 86
  Total: $38382578
  Average  Change: $-2315.12
  Greatest Increase in Profits: Feb-2012 ($1926159)
  Greatest Decrease in Profits: Sep-2013 ($-2196167)
  ```

* In addition, the final script should both print the analysis to the terminal and export a text file with the results.

## PyPoll

![Vote Counting](Images/Vote_counting.png)

* In this challenge, I am tasked with helping a small, rural town modernize its vote counting process.

* I will be give a set of poll data called [election_data.csv](PyPoll/Resources/election_data.csv). The dataset is composed of three columns: `Voter ID`, `County`, and `Candidate`. The task is to create a Python script that analyzes the votes and calculates each of the following:

  * The total number of votes cast

  * A complete list of candidates who received votes

  * The percentage of votes each candidate won

  * The total number of votes each candidate won

  * The winner of the election based on popular vote.

* As an example, your analysis should look similar to the one below:

  ```text
  Election Results
  -------------------------
  Total Votes: 3521001
  -------------------------
  Khan: 63.000% (2218231)
  Correy: 20.000% (704200)
  Li: 14.000% (492940)
  O'Tooley: 3.000% (105630)
  -------------------------
  Winner: Khan
  -------------------------
  ```

* In addition, the final script should both print the analysis to the terminal and export a text file with the results.

## Hints and Considerations

* Consider what we've learned so far. To date, we've learned how to import modules like `csv`; to read and write files in various formats; to store contents in variables, lists, and dictionaries; to iterate through basic data structures; and to debug along the way. Using what we've learned, try to break down the tasks into discrete mini-objectives. This will be a _much_ better course of action than spending all the time looking for a solution on Stack Overflow.

* As I will discover, for some of these challenges, the datasets are quite large. This was done purposefully, as it showcases one of the limits of Excel-based analysis. While our first instinct, as data analysts, is often to head straight into Excel, creating scripts in Python can provide us with more robust options for handling "big data".

* Write one script for each dataset provided. Run the script separately to make sure that the code works for its respective dataset.

* Feel encouraged to work in groups, but don't shortchange  by copying someone else's work. I get what is put in, and the art of programming is extremely unforgiving to moochers. Dig the heels in, burn the night oil, and learn this while I can! These are skills that will pay dividends in your future career.


  * **Commit often**.

## Copyright

Trilogy Education Services © 2019. All Rights Reserved.
