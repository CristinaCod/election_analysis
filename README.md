# Election Audit Analysis
## Overview
### Purpose
The purpose of this analysis is to assist Tom, a Colorado Board of Elections employee, on an election audit of the results of a congressional precinct in Colorado. Based on the data we will be determining the total number of votes, votes and percentages for each candidate and county, the largest county turnout, and the winning candidate. Typically, this process would be done in Excel however, Tom’s boss wants to know if there is a way to automate the process in Python and that’s where we come in. The findings of this analysis can then be utilized not only in other state congressional districts but also on a senatorial level. Our work in this analysis is certifying the results of the data from this congressional race in Colorado. If valid, this could revolutionize election audits.
## Election Results
* **Total Votes:** 369,711

Calculated by initializing the variable to zero then instructing the program to read through the election data and add every vote as it goes through the code “total_votes = total_votes + 1”
* **County Votes:**

  -Jefferson: 10.5% (38,885)
  
  -Denver: 82.8% (306,055)
  
  -Arapahoe: 6.7% (24,801)
  
* **Largest County Turnout:** Denver
* **Candidate Votes:**

  -Chales Casper Stockham: 23.0% (85,213)
  
  -Diana DeGette: 73.8% (272,892)
  
  -Raymon Anthony Doane: 3.1% (11,606)
  
* **Winner:**

  -Diana DeGette
  
  -Winning Vote Count: 272,892
  
  -Winning Percentage: 73.8%
  
An image of the results printed out is displayed below.

![election_results.png](https://github.com/CristinaCod/election_analysis/blob/main/analysis/Election_Results.png)
## Election Summary
To the Election Commission,

The benefits and future implications of this audit know no bounds. This Colorado district is just the beginning. With a few minor changes to the data source this analysis could be applied on any other district at the same level or applied to other levels of elections. The current analysis doesn’t have to end here though. New information could be added or taken away if desired. 

Some modifications that could be implemented include we could add a step in the code where it also examines political party affiliation. We could include this when looking at the counties, specifically the largest turnout, to determine which party has a greater prevalence and outcome. This could also be applied to the results of the winner, displaying their political party affiliation which obviously also infers the majority of voter’s affiliation.

It could also be beneficial to examine population size in relation to each county or state depending on if this code is being applied again to a state congressional precinct or the next step up, a senatorial one. Obviously, a county or state with a larger population should in theory export more votes, effecting the final results. 

Additionally, if we were to one day apply this to a presidential election it would be interesting to include code that formulates popular vote versus the electoral college. 


