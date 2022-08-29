# Election Results with Python: Compiling Data Utilizing Python

## Overview of Project

### Background

The dataset is for a population of voters who had voted in a congressional election located in a congressional district in and around the Denver area. The data elements included are ballot ID, county where the ballot deposited, and candidate that was voted for on the ballot. There is a total of 369,712 distinct ballots; 3 counties of which are Arapahoe, Denver, Jefferson; and 3 candidates of whom are Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane.

### Purpose

The purpose of this analysis is to determine the relevant metrics of the election including: the total number of votes, the number of votes per county and the percentage of overall votes in each county, the largest county by votes, the number of votes per candidate and the percentage of overall votes for each candidate, and the winning candidate by votes.

## Election-Audit Results

### Election Outcomes

![Election_Results.png](resources/Election_Results.png)

The following bulleted list notes the pertinent election outcomes also visualized above in the terminal output from the code:
 
* The total number of votes casted in the congressional election was 369,711.

* The breakdown of the number of votes in each county and the percentage of total votes in each county was:
    * Arapahoe: 24,801 (6.7%)
    * Denver: 306,055 (82.8%)
    * Jefferson: 38,855 (10.5%)

* The county with the largest number of votes was Denver at 306,055 votes or 82.8% of the total number of votes.

* The breakdown of the number of votes for each candidate and the percentage of total votes for each candidate was:
    * Diana DeGette: 272,892 (73.8%)
    * Raymon Anthony Doane: 11,606 (3.1%)
    * Charles Casper Stockham: 85,213 (23.0%)

* The candidate with the largest number of votes, and therefore the winner of the election, was Diana DeGette at 272,892 votes or 73.8% of the total number of votes.

## Election-Audit Summary

### Business Proposal for Script

![Election_Script_1.png](resources/Election_Script_1.png)
![Election_Script_2.png](resources/Election_Script_2.png)
![Election_Script_3.png](resources/Election_Script_3.png)
![Election_Script_4.png](resources/Election_Script_4.png)
![Election_Script_5.png](resources/Election_Script_5.png)

Above is the script for compiling the election results.

This Python script can be utilized for any election. For other congressional elections, there requires little to no modifications. For lower-level elections for local governments such as county councils or city councils, there may need to be modifications where, rather than determining votes by county and largest county by votes, we would modify the variables for townships in the county or districts in the city and to modify the printed string output as such. The same can be the case for elections for other national offices such as the presidency where we can still determine votes by county and largest county if that level of granularity is required without any modifications or modify the variables for states and the printed script output as such if that would be preferable. We can therefore further modify the script to determine and print the winners of each state for the presidential election with for loops and then to sum the electoral college votes assigned to each state to determine the winner of the presidential election.

In this election, we can also edit the script to produce more granular analysis on votes for each candidate by county or votes in each county by candidate using a for loop. This can be useful for future elections if the candidates can know where their geographic source of support is.

If we have further demographic datapoints on the identities of each voter who had submitted each ballot then we can also edit the script to compile further aggregate data and visualize it in tabular format for voters by party affiliation, race, religion, gender, age range, or most pertinent issue of concern. If we can identify the most notable demographic groups in an election or which demographic group is the source of support for each candidate, then we can design campaign promises to cater to those demographic groups in designing future campaign platforms.
