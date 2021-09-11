# Election_Analysis
##

## Project Overview
A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.60.0

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
  - Charles Casper
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper recieved 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette recieved 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane recieved 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
  - Diana DeGette, who 73.8% of the vote and 272,892 number of votes.

## Challenge Overview
For this challenge I was asked to further analyze the election data to include the voter turnout by county.

1. Calculate the voter turnout for each county.
2. Calculate the percentage of votes from each county out of the total.
3. Determine the county with the highest turnout.

![Results](https://github.com/PSWil/Election_Analysis/blob/main/analysis/results_txt_output.png)

As you can see in the image above
The voter turnout for each county was:

- Jefferson produced 10.5% of voters, for a total of 38,855 voters.
- Denver produced 82.8% of voters, for a total of 306,055 voters.
- Arapahoe produced 6.7% of voters, for a total of 24,801 voters.
- The county with the largest voter turnout was: 
  - Denver which lead the counties with 82.8% of the total votes.

## Challenge Summary 
Now that we have a working script to analyze county election data we can adjust the script with ease to use for different elections.
This is one of the greatest benifits that analyzing the data with a script so that in the future we can imput the data and gather information much more quickly. With a little tinkering we can adjust the script to analyze the data further and use it in future elections for fast analysis.

We can modify this script further for deeper analysis. If we knew the currentl amount of registered voters in each county, not just the total votes cast, we could get the voter turnout percentage for the county to see how engaged and active the voters are in each county with an if statement. We could then use that information to plan for the next election.

We can also easily adapt this script so that we may apply it to different elections. For instance, in a local election for ie. County Sheriff, City Council we could modify the counties variable to show voters by neighboorhood. We can also scale this up to national elections by categorizing by state.

If you have any questions or concers feel free to reach out to me so that I can be of some assistance, thank you.
