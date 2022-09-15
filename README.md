# An Analysis of Election Data Using Python
## Overview

The purpose of this analysis was to calculate election results from an excel spreadsheet that contains raw election data for a precinct with information for each ballot cast, including the county where each ballot was cast and the candidate each ballot was cast for.

A python script was made which calculated the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, and the winner of the election based on the popular vote.

The number of votes cast from each county, the percentage of votes from each county and a calcuation of the largest county turnout was also reported.

This was in turn printed out to a text file with a readout of results.

## Election-Audit Results

The following are the results of the audit:

- There were 369,711 total votes cast in the election:

![total_votes](Resources/total_votes.png)

- The following shows the number of votes cast in each county and the percentage of total votes for each county:

![county_votes](Resources/county_votes.png)

- The results show that Denver County was the county with the largest number of votes:

![county_largest_number](Resources/county_largest_number.png)

- The following shows a breakdown of the number of votes and the percentage of the total votes each candidate recieved:

![candidates_votes](Resources/candidates_votes.png)

- Finally, the below shows that Diana DeGette won the election with the corresponding vote count and winning percentage:

![candidate_winner](Resources/candidate_winner.png)

## Election-Audit Summary

This script could potentially be used for future elections as well.

Especially if the same type of information is wanting to be counted (county and candidate information listed directly from the individual ballots), the information could be inputted in the same format on any excel sheet and then ran using the code. If the excel sheet used was saved under a different name, the code would only have to make sure and reflect the correct name of the spreadsheet in the file_to_load line. 

Otherwise, given the same type of information inputted in the columns, the code would work the same.

The code could also be modified to provide additional information to help plan future elections. For example, if the polling sites are also included for each vote cast in the same spreadsheet, the county variables and calculations could be copied and then replaced with variables to record and calculate the number of votes cast and calculate percentages for each polling place. This could help make sure that election workers are properly dispursed.
