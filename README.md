# Efficient_poll
This file conatins the basic idea behind electoins using azure blockchain.

## Issues
1. Applying for voter ID
2. Living in different location
3. Vote counting
4. EVM hacking

Using the concept of blockchain these issues related to election in India can be easily resolved. 
The basic idea is to create a blockchain for every constituency in India and contest election for that constituency using block.

## Stage 1 - Applying for voter ID (Creation of Block)
The process will be that with every Voter ID created, there will be the addition of a block in the blockchain of the constituency. This block will store the information of Voter ID in it.

## Stage 2 - The creation of the voting Online Portal 
Using reactJS an online voting portal will be created. The portal will have one account for each voter ID. For Login the login ID will be the voter ID and the password will be an alpha-numeric string which will be known to the voter when he/she goes for applying the voter ID. Upon logging in into the voter account the voter will get the candidate's information and the option for voting for them(within the 15 days of voting). 

## Stage 3 - Voting
In every 5 years each block will get one token to share which will expire within 15 days(voting period) of activation. This token is the voting right of the voter and by sharing this token the voter casts his/her vote. The voting buttons ,displayed on the portal in the contestant's information, will be linked to the hash of the contestant in the blockchain.By clicking on the voting button the voter can vote can for a particular contestant. For confirmation of vote an OTP will be sent to the voter either by email or by SMS. Upon confirmation of vote the token will be transfered from the voter's block to the contestant's block. This will complete the voting process

## Stage 4 - Vote Counting
At the end of the 15th day, the block with the highest number of token will be announced winner in the constituency. And the party which has won in the highest number of contituency will be   concerned with forming the government.

## Tools used- 
1. Microsoft Azure (Blockchain)
2. ReactJS (Online Portal)
3. Solidity (Smart Contracts)
