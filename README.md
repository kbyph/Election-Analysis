# Election_Analysis

## Overview of Election Audit
The Colorado Board of Elections requests the following tasks to complete the election audit of a recent local congressional election to determine the final results. In addition, calculating each county's voter turnout and percentages allows us to expand the Election Audit to include additional data that may be insightful for future elections.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes for each candidate received. 
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Calculate each county's voter turnout.
7. Calculate each county's percentage of votes in relation to the total count.
8. Determine the county with the largest voter turnout.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code 1.38.1

## Election Audit Results
The analysis of the election shows that:
- There were 369,711 votes cast in the election.

- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane

- The candidate results were:
    - Charles Casper Stockham received 23.0% of the total vote (85,213).
    - Diana DeGette received 73.8% of the total vote (272,892).
    - Raymon Anthony Doane received 3.1% of the total vote (11,606).

- The winner of the election was:
    - Diana DeGette, with a winning percentage of 73.8% and a total count of 272,892 votes.

- The county votes were:
    - Jefferson contributed to 10.5% of total votes with 38,855 voters.
    - Denver contributed to 82.8% of total votes with 306,055 voters.
    - Arapahoe contributed to 6.7% of total votes with 11,606 voters.

- The largest county turnout was:
    - Denver, which contributed to 82.8% of total votes with 306,055 voters.

![Election_Results](https://user-images.githubusercontent.com/102638461/165668983-9bac04b1-8fd0-43e9-96cc-ec8b880ca739.png)

## Election-Audit Summary
The PyPoll_Challenge.py script can definitely be used for other elections because it analyzes each individual county and  candidate in the dataset with printed results. Expanding the Election Audit to include the county votes and turnout are also great for extra insight in regards to the targeted demographic area.

Modifications to the original script will provide additional data for us to utilize. For example, we can modify the script  to cover all counties within a state, providing a deeper analysis for each specific county vote. Hence the script is flexible enough to cover all sizes of elections, big or small. The candidates can also be modified to include a larger scale of competition, spreading out the data set to analyze each indivual vote. Therefore I propose the election commission to adopt this script as a solution for statewide election audits. This application is flexible, customizable, and simple to analyze.

