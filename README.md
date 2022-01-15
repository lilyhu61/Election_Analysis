# Election Analysis Challenge with Python & VS Code
## Overview of Election Audit
A colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Calculate the voter turnout of each county.
3. calculate the percentage of votes from each county out of the total count.
4. Determine the county with the highest turnout.
5. Get a complete list of candidates who received votes.
6. Calculate the total number of votes each candidate received.
7. Calculate the percentage of votes each candidate won.
8. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- software: Python 3.7.6, Visual Studio Code, 1.63.2

## Election Audit Results
The analysis of the election show that:
- **There were "369,711" votes cast in the election.**

- **The voter turnout of each county and percentage of votes from each county out of the total count were:**
    - County Jefferson received "10.5%" of the vote and "38,855" number of votes.
    - County Denver received "82.8%" of the vote and "306,055" number of votes.
    - County Arapahoe received "6.7%" of the vote and "24,801" number of votes.
    
- **The county had the largest number of votes was Denver.**

- **The candidates were:**
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
    
- **The candidate results were:**
    - Candidate Charles Casper Stockham received "23.0%" of the vote and "85,213" number of votes.
    - Candidate Diana DeGette received "73.8%" of the vote and "272,892" number of votes.
    - Candidate Raymon Anthony Doane received "3.1%" of the vote and "11,606" number of votes.
    
- **The winner of the election was:**
    - Candidate Diana DeGette who received "73.8%" of the vote and "272,892"number of votes.
    
***Election Audit Results image provided***

![image](https://user-images.githubusercontent.com/95242493/149599795-04ca44ef-702d-4516-a70e-78ae7e5c6195.png)

## Election-Audit Summary
   This scrip actually can be used with some modifications for any election. Such as U.S. Presidential election or Mayoral Races election.
   For U.S. presidential election, just need to replace all the "county" with "state" in the following scrip.
   For Mayoral Races election, just need to replace all the "county" with "city" in the following scrip.
   ```
   if county_name not in county_options:

            # 4b: Add the existing county to the list of counties.
            county_options.append(county_name)

            # 4c: Begin tracking the county's vote count.
            county_votes[county_name] = 0        

        # 5: Add a vote to that county's vote count.
        county_votes[county_name] += 1   
   ```
