# Module 3 Challenge – Election Analysis 

## Overview of Project

The aim of the current analysis was to audit the results of an election in order to provide a group of Colorado Board of Elections employees greater insight into the results.  The requested information from these employees include:

-	Calculate the total number of votes cast in the election.
-	Calculate the number of votes cast in each county.
-	Calculate the percentage of votes each country contributed to overall election vote total.
-	Determine which county had the highest voter turnout.
-	Calculate the total number of votes from the county that had the highest voter turnout.
-	Calculate the percentage of total votes from the election were from the country with the highest voter turnout.
-	Compile a list of all candidates that received votes in the election.
-	Calculate the total number of votes each candidate received.
-	Calculate the percentage of total votes each candidate received.
-	Determine which candidate won the election.

## Election Audit Results

The Python script used to complete this analysis can be accessed via the link below:
[https://github.com/jbowman86/Election_Analysis/blob/main/PyPoll_Challenge_Revision.py]

The election dataset used for the audit can be obtained via the following:
[https://github.com/jbowman86/Election_Analysis/blob/main/election_results.csv] 

The results of the election audit were:

Terminal output: [https://github.com/jbowman86/Election_Analysis/blob/main/election_results_terminal_output.png]

Text file output: [https://github.com/jbowman86/Election_Analysis/blob/main/election_results.txt]

The election data yielded the following results:

-	There was 367,111 total votes cast in the congressional election.
-	The Colorado counties audited were:
o	Jefferson
o	Denver
o	Arapahoe
-	The county voter turnout was as follows:
o	There were 38,855 votes from Jefferson county contributing 10.5% of the total number of votes. 
o	There were 306,055 votes from Denver county contributing 82.8% of the total number of votes. 
o	There were 34,801 votes from Arapahoe county contributing 6.7% of the total number of votes.
-	The county with the largest number of votes was Denver (306,055 total votes, 82.8% of total votes).
-	The candidates in the audited election were:
o	Charles Casper Stockham
o	Diana DeGette
o	Raymon Anthony Doane
-	The audited results from the election were:
o	Charles Casper Stockham received 85,213 votes and 23.0% of the total votes.
o	Diana DeGette received 272,892 votes and 73.8% of the total votes
o	Raymon Anthony Doane received 11,606 votes and 3.1% of the total votes.
-	The winner of the election was Diana DeGette.  She received 73.8% of the votes comprising of 272,892 votes in total.

## Election Audit Summary

The python script used to audit the Colorado congressional election has demonstrated that it can effectively determine the winning candidate and county turnout.  With minor modifications, the script could be adapted for other elections.  The following are ways that the script can be modified:

-	The analysis discussed only dealt with three counties and three candidates.  In some elections, there may be more counties and/or candidates.  The python script containing loops that can go through lists of counties and candidates that isn’t just limited to this small dataset.  If data were available on other counties or states, the looping strategy can be altered to apply this code to different datasets.
-	Ballot ID numbers can be used to check if there are any duplicate counts by comparing each ballot ID number against the entire list.
-	Determining the winning candidate by each county.  This can be achieved by utilizing nested loops to provide candidate vote totals for each county in the entire list.  This modification would allow for a breakdown of which candidate won each county compared to the candidate who won the overall election. 

