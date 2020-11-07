# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular votes.

## Resources
- Data Source: election_result.csv
- Software: Python 3.7.1. Visual Studio Code, 1.38.1

## Summary
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The candidates were
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were
  - Charles Casper Stockham received 23.0% of votes and 85,213 number of votes.
  - Diana DeGette received 73.8% of votes and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of votes and 11,606 number of votes.
- The winner of the election was
  - Diana DeGette, who received 73.8% of the votes and 272,892 number of votes.
 
## Overview of Election Audit
This project is to provide the below results:
- The total number of votes in this congressional election
- The Breakdown of votes for each county
- The county with the largest number of votes
- The breakdown of votes for each candidate
- The winner of the election

## Election Audit Result
Upon analyzing the votes, the election shows that:
- There are total of 389,711 votes in this congressional election
- Breakdown of votes for each county:
  - Jefferson received 10.5% of votes and 38,855 number of votes;
  - Denver received 82.8% of votes and 306,055 number of votes;
  - Arapahoe received 6.7% of votes and 24,801 number of votes;
- Denver had the largest number of votes;
- Breakdown of votes for each candidate:
  - Charles Casper Stockham received 23.0% of votes and 85,213 number of votes.
  - Diana DeGette received 73.8% of votes and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of votes and 11,606 number of votes.
- Diana DeGatte was the winner of the election. She has 272,892 votes with winning percentage at 73.8%.

![](sreenshot/Election_Results_on_cmd.png)

## Election Audit Summary
This script can be modified for other elections through the examples below:

First, we can add more information on the votes percentage in terms of total population to see the voting participation rate. We can add total population on all counties/ regions and calculate the participation rate by adding code “participating_rate = votes/ population”.

Second, we can show the voting percentage on each candidate in each county. For example, we can show how many people voted for Diana in Denver. We can create an IF statement in the For loop. 
