# Eth-Begin
This is my assignment for the Ethereum Beginner course offered by Metacrafters.
# Description
This is a simple ERC-20 compatible smart contract written in Solidity. It supports minting and burning of a custom token named PerpHorizon (abbreviation: PPH).
Public Information:

-Name and Abbreviation: Imagine your token is like a brand new currency, and you're naming it "PerpHorizon," with the short form "PPH"—just like how we have USD for U.S. dollars.
-Total Supply: This is like the total amount of money printed in a country. Initially, it’s set to zero because no tokens exist yet.


Balances:

-Mapping Addresses to Balances: Think of each address as a bank account. The contract keeps a record (mapping) of how much each account (address) owns. This is like the bank’s ledger showing who has how much money.


Minting Tokens:

-Mint Function: This function lets you "print" new tokens, just like a central bank printing new money. You decide how many tokens to create and whose account (address) they go into. The total supply goes up, and that person’s balance increases.


Burning Tokens:

-Burn Function: This is like tearing up some of your money, making it disappear. You choose how many tokens to destroy from someone’s balance. The function first checks if the person has enough tokens to burn. If they do, the total supply decreases, and their balance goes down.
# Getting Started
Simply copy this code in remix,compile and deploy.
You can check transactions in Deploy&Run transactions section.
# Author
PerpetualHorizon
# License
This project is licensed under the MIT License. See the LICENSE file for details.

