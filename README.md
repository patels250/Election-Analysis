# Election-Analysis

## Project Overview

A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election. 

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Determine the voter turnout for each county.
7. Determine the percentage of votes from each county out of the total count.
8. Determine the county with the highest turnout.

## Resources

- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code 1.57.1

## Results

The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- Candidates:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- Voter Turnout:
  - Jefferson County had 10.5% of the total votes (38,855 votes).
  - Denver County had 82.8% of the total votes (306,055 votes).
  - Arapahoe County had 6.7% of the total votes (24,801 votes).
- Largest County Turnout:
  - Denver County who had 82.8% of the total votes (306,055 votes).
- Candidate Results:
  - Charles Casper Stockham received 23.0% of the vote (85,213 votes).
  - Diana DeGette received 73.8% of the vote (272,892 votes).
  - Raymon Anthony Doane received 3.1% of the vote (11,606 votes).
- Winner of the Election: 
  - Diana DeGette who received 73.8% of the vote (272,892 votes).

## Summary

This is a versatile script that can be used to calculate the results of any election where data is stored in a CSV file. To make this script run analysis for any election, a few simple modifications need to be made. The correct file name and path needs to be coded into Line 9 of the script. The script can also be expanded to show the county with the lowest voter turnout. This could be useful if running analysis on elections with dozens of counties involved.
