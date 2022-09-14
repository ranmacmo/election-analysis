# Election Audit 

## Overview 
 
 1. Calculate the total number of votes 
 2. Get a unique listing of the candidates who received votes 
 3. Get a unique listing of counties who received votes 
 4. Calculate number of votes for each unique candidate 
 5. Calculate number of votes for each county 
 4. Calculate the percentage of the votes for each candidate 
 5. Calculate the percentage of votes for each county 
 5. Determine the winner of the election based on most votes 
 6. Determine the county with the most votes 

## Resources 
- Data Source: Resources/election_results.csv
- Source code: PyPoll_Challenge.py 
- Output File: analysis/election_results.txt 
- Software: Python 3.9.12, Visual Studio Code,  1.71.0 (Universal)

## Results
The analysis of the election shows that: 

- There were 369,711 votes cast 
- The candidates were: 
	- Charles Casper 
	- Diana DeGette
	- Raymon Anthony
- The candidate results were 
	- Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes 
	- Diana DeGette received 73.8% of the vote and 272,892 number of votes 
	- Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes 
- The winner of the election was 
	- Diana DeGette, who received 73.8% of the vote and 272,892 number of votes 
- The countries were 
	- Jefferson 
	- Denver 
	- Arapahoe 
- The county results were 
	- Jefferson received 10.5% of the vote and 38,855 number of votes 
	- Denver received 82.8% of the vote and 306,055 number of votes 
	- Arapahoe received 6.7% of the vote and 24,801 number of votes 
- The largest county turnout was Denver 

## Summary 
- Provided the input data structure is the same for future elections this script could be used to produce similar results. The only modification would be pointing the script to the proper files for input and output (file_to_load and file_to_save variables) 
- If the data structure where slightly different some modifications would be needed to map the columns in the input to a common format prior to running pointing the variables to the proper input and output files. 
