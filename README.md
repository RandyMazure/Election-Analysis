# Election-Analysis

## Project Overview
A Colorado Board of Elections committee requested an audit on a recent local congressional election.  This audit was to include:

1. Calculate the total number of votes cast. 
2. Get a complete list of candidates who received votes. 
3. Calculate the toal number of votes each candidate received.  
4. Calculate the percentage of votes each candidate won. 
5. Determine the winner of the election based upon popular vote.

## Resources 
- Data Source: election_results.csv
- Software: Python 3.10, Visual Studio Code, 1.66.0

## Results 
The analysis of the election has shown:
-There were 369,711 total votes cast
-There were three total candidates receiving votes:
  - Charles Casper Stockham 
  - Diana DeGette
  - Raymon Anthony Doane
-The results:
  - Diana DeGette received 272,892 of the total votes (73.8%).
  - Charles Casper Stockham received 85,213 of the total votes (23.0%).
  - Raymon Anothony Doane received 11,606 of the total votes (3.1%).
The winner of the election was:
  - Diana DeGette

## Summary
The supplied code can be used for future analyses given that the .csv files follow the same 3-column format (Ballot ID, County, Candidate).  Simply replace the .csv file name in line 6.  
![Untitled](https://user-images.githubusercontent.com/100173822/162179315-e91301d9-509b-4684-bd60-21c7718eeb17.png)
If the file does not follow the (Ballot ID, County, Candidate) 3-column  structure, changes can be made to the row index in lines 46-50:
![Untitled2](https://user-images.githubusercontent.com/100173822/162180923-aec01a66-39f3-43dc-9006-468bc80dbb5d.png)
