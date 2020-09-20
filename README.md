# Election-Analysis

## Overview of Election Audit
A Colorado Board of Elections employee has gven you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Calculcate the voter turnout for each county.
7. Calculate the percentage of votes from each county out of the total count.
8. Determine the county with the highest voter turnout.

## Resources
-Data Source: election_results.csv

-Software: Python 3.7.8, Visual Studio Code, 1.38.1

## Election-Audit Results

The analysis of the election show that:

-Total number of votes casted in election

  - There were "369,711" votes cast in the election

-Breakdown of votes by county:
  
  - Jefferson 10.5% (38,855)

  - Denver 82.8% (306,055)

  - Arapahoe: 6.7% (24,801)

-County with largest number of votes:

  - Denver
  
  county_name_turnout_summary= (
  
        f"-------------------------\n"
        
        f" Largest County Turnout : {county_name_turnout}\n"
        
        f"-------------------------\n")
        
    print(county_name_turnout_summary)
   
-The candidate results were:
 
  - Charles Casper Stockham received 23.0% of the votes and 85,213 of the votes
  
  - Diana DeGette received 73.8% of the votes and 272,892 of the votes
  
  - Raymon Anthony Doane received 3.1% of the votes and 11,606 of the votes
  
-The winner of the election was:
 
  - Diana DeGette received 272,892 total votes which accounted for 73.8% of the votes casted

![image](https://user-images.githubusercontent.com/70483866/93721419-bb37a700-fb55-11ea-914a-e1edfa08324b.png)

## Election-Audit Summary

Since Diana DeGette won by an overwhelming majority with over 70% of the votes while the overwhelming majority of votes came from Denver with over 80%, I would advice the election commission investigate further into the ties between the winning candidate and Denver county and if there is reason to consider voter fraud being a legitimate possibility. This script can serve as a beneficial tool for future elections because of how straightforward and easy to read it is. It would be best for future elections that are based solely on popular vote because of the breakdowns of county and candidates by percentage and raw counts. For task #7, I would have included the percentage and number of votes in addition to just the name of the largest county turnout, similar to what was done for the winning candidate in the section below it. Additionally, I would suggest the political party that candidate represents be listed next to their name and that there be a header present displaying the specific position and district/area being elected for.
