# Election Audit with Python

## Overview of Election Audit
The Colorado Board of Election requested an election audit of the tabulated results for a U.S. Congressional precinct in Colorado. This audit will report the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, and the winner of the election based on the popular vote with the end goal of providing a vote-count report to certify this U.S. Congressional race. In addition, the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout will be reported.

### Election Audit Results
* A total of 369,711 votes were cast in this election.
* Denver County had a total of 306,055 votes casted or 82.8% of total votes. Jefferson County had a total of 38,855 votes casted or 10.5% of total votes. Arapahoe County had 24,801 votes casted or 6.7%.
* Denver County had the largest number of votes.
* Charles Casper Stockham received 23.0% or 85,213 of the total votes. Diana DeGette received 73.8% or 272,892 of the total votes. Raymon Anthony Doane received 3.1% or 11,606 of the total votes.
* Diana DeGette won the election with 272,892 or 73.8% of the total votes. 

#### This image shows the Election Results generated by Python
<img width="413" alt="election-results" src="https://user-images.githubusercontent.com/91927712/141666320-f840f772-3e7c-4059-b290-0f1c09636d46.png">

### Election Audit Summary
This Python script can be used for future election audits to report the outcomes listed in this audit and in the "Overview of Election Audit" section. In the future, if the tabulated results are in the same three column (Ballot ID, County, Candidate) CSV file, then there would be minor modifications needed for the file_to_load and file_to_save variables to yield the same results. If data is delivered with more columns and information, then additional variables will need to be modified, like the candidate_name or county_name variables. If possible, delivering the results in the same three column format (Ballot ID, County, Candidate) will help streamline the process to yield these results. However, if more data is needed, then the script can be edited to yield the desired data outcomes.
