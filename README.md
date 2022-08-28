# Election Audit with Python

## Overview of Election Audit
The goal of this audit is to provide a vote-count report to certify a U.S. Congressional race using Python. 

This audit will report:

* The total number of votes cast
* The total number of votes for each candidate
* The percentage of votes for each candidate
* A complete list of candidates who received votes
* The total number of votes for each county
* The percentage of votes for each county
* The county with the highest turnout 
* The winner of the election based on the popular vote 


### Election Audit Results

**The Total Number of Votes Cast 
<br /> Code and Image**

<img width="450" alt="total_votes" src="https://user-images.githubusercontent.com/91927712/187050026-9496ff76-0dbb-467f-a7fb-d02e73fd9d61.png">

**The Total Number of Votes and Percentages for Each Candidate 
<br /> Code and Image**

<img width="450" alt="votes_each_candidate" src="https://user-images.githubusercontent.com/91927712/187050722-eb52484b-223b-4c1d-9040-c269479faf50.png">

**The Total Number of Votes and Percentages for Each County
<br /> Code and Image**

<img width="450" alt="total_county_votes" src="https://user-images.githubusercontent.com/91927712/187088619-1e47271c-d2e8-45e5-b6cb-b229904eb8cc.png">


**County with the Highest Turnout
<br /> Code and Image**

<img width="450" alt="largest_county_turnout" src="https://user-images.githubusercontent.com/91927712/187089214-7219fc0e-0b45-480b-89b0-44458bf706c9.png">

**The winner of the election based on the popular vote 
<br /> Code and Image**

<img width="450" alt="winner_elections" src="https://user-images.githubusercontent.com/91927712/187089520-263848b7-a8c7-49c2-92b4-4c98ccc768cb.png">


### Election Audit Summary
This Python script can be used to help automate the process of auditing future congressional and senatorial elections. As long as the tabulated results are in the same three column CSV file format (Ballot ID, County, Candidate), then the only modifications needed would be to change the file_to_load and file_to_save variables because different files will be used.

If more insights are needed, then the script can be updated to meet those needs.
