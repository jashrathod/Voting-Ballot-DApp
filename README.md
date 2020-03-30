# Voting Ballot DApp

A voting ballot application in which there is a chairperson who is authorized to register voters. Voters have the permission to vote only after the registration process.

<small> The smart contract used is based on the example in solidity docs </small>


## Business Logics handled
1. Chairperson registers accounts to vote
2. No other account can register accounts to vote
3. Can't register already registered user
4. Unregistered account can't vote
5. Registered accounts cannot vote twice
6. Can't vote a person who is not there

## Business logic to be included
1. State change rules
2. Save start time as a state variable

## Prerequisite
1. NodeJs
2. Metamask (3.14.1)
3. Truffle (v4.0.4)