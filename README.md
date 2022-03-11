# Module-3-Election_Analysis-

## Overview of the Project

### Project Background:

The purpose of this analysis is to help a Colorado Elections Board employee complete the election audit of a recent local congressional election. The initial analysis required computation of the following:

- Calculate the total number of votes cast
- Create a complete list of candidates who received votes
- Calculate the number of votes each candidate received 
- Calculate the percentage of votes each candidate won
- Determine the winner of the election based on popular vote

### Purpose
The election commission has requested some additional data to complete the audit:

- Calculate the voter turnout for each county
- Calculate the percentage of votes from each county out of the total count
- Determine the county with the highest turnout


## Resources
- Data Source: [election_results.csv](Resources/election_results.csv)
- Software: Python 3.10, Visual Studio code, 1.65.2


## Election Audit Analysis and Results

For this analysis, a Python code [PyPoll_Challenge.py](/PyPoll_Challenge.py) was updated using For loops and conditional statements to find all the requested results. A for loop was used to get the list of counties from the dataset.  Then a decision statement was used to check if a county exists in the county list. If county did not exist in the list, then the code began tracking the county votes. Another conditional statement was used to determine the winning county. 

The election results were printed on the Python terminal:
   
 https://github.com/Diana7e/Module-3-Election_Analysis-/blob/1100214a128008790da26cbe1f288ba0c099e8dd/Resources/Screenshot%20run%20in%20terminal.png
 
The election results were also sent to an output file called [election_analysis.txt](analysis/election_analysis.txt):

 https://github.com/Diana7e/Module-3-Election_Analysis-/blob/1100214a128008790da26cbe1f288ba0c099e8dd/Resources/election%20analysis%20txt.png

The analysis of the election shows that:

- Total of 369,711 votes were cast.
- There are 3 counties in the precinct:
	- Jefferson County
	- Denver county
	- arapahoe County
- Breakdown of votes by 3 counties in the precinct are as follows:
	- Jefferson County received 10.5% of the vote and 38,855 number of votes  
	- Denver County received 82.8% of the vote and 306,055 number of votes
	- Arapahoe County received 6.7% of the vote and 24,801 number of votes 
- Denver county had the largest number of votes (306,055) casted

- There were three candidates running in this election: 
	- Charles Casper Stockham 
	- Diana DeGette 
	- Raymon Anthony Doane
- Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes
- Diana DeGette received 73.8% of the vote and 272,892 number of votes
- Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes

- Diana DeGette was declared as the winner of the election who received 73.8% of the vote and 272,892 total number of votes

## Election Audit Summary

Given that the file analyzed contained all the election results for a local congressional election in Colorado, the audit was performed with a python code in under 3 seconds.  The code shows the election results by candidate and by County, giving the number of votes as well the percentage of votes for each case, resulting in determining the winner.  With this kind of audit, larger public elections can be audited within seconds of having the results file to be analyzed, even for state or federal elections.

The following are modifications that could be implemented in other type of elections:
- Include data for different types of positions being elected: Governor, Lieutenant Governor, Secretary of State, and Attorney General, State Supreme Court Justices, Comptroller, Treasurer, State Senators, and State Legislators.
- Information about voters could be include to categorize by age, gender, zip codes, etcetera.
