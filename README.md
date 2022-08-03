# election_analysis

Annette Blackburn

# Colorado Congressional Election Audit Purpose, Results, and Summary 

## Overview and Purpose of Colorado Congressional Election Audit
The purpose of this election audit is to confirm and analyze the congressional election results for the Colorado Board of Elections. 

## Election-Audit Results
- 369,711 votes were cast in this congressional election 
- County Votes:
- In Jefferson County, 38,855 votes were cast, which is 10.5% of the total votes
- In Denver County, 306,055 votes were cast, which is 82.8% of the total votes
 - In Arapahoe County, 24,801 votes were cast, which is 6.7% of total votes 

- Denver County had the largest number of votes (82.8% of total votes)

- Candidate Votes:
- Diana DeGette received 73.8% of all votes (272,892)
 - Charles Casper Stockham received 23.0% of all votes (85,213)
 - Raymon Anthony Done received 3.1% of votes (11,606)
- Diana DeGette won the Colorado congressional election with 272,892 votes, which was 73.8% of all votes.

## Election-Audit Summary 
This script is general and can be used for any election data that is formatted the same. The print output is general: it does not use language specific to Colorado or congressional elections. This script should not need to be modified to be used in other elections, unless the election data was in a non-standard file format or if the election results were formatted differently (i.e., election results in different column).

For example, this block of code determines the winning county and its vote count and can be used anywhere.
~~~~
 if (current_county_votes > largest_county_turnout_vote_count):
            largest_county_turnout_vote_count = current_county_votes
            largest_county_turnout = county_name
~~~~
