# KaseiCoin Crowdsale Solidity

---

## Technologies

This application is a smart contract that function as a joint bank account that allows two users to utilize a shared account to deposit, store and withdraw ethereum.

---

## Installation Guide

No libary installation is necessary, simply clone this github repository to Remix IDE.

Then deploy the contract. Once deployed the contract is ready to use.

## Usage

To use the account fund the account. Here I have made three deposits 1 ether, 5 ether and 10 ether.

Set accounts function
<img src=https://github.com/samlawhead/Joint-Savings-Account-Solidity/blob/main/screenshots/Screen%20Shot%202022-10-13%20at%2013.23.40.png>

Deposit function
<img src=https://github.com/samlawhead/Joint-Savings-Account-Solidity/blob/main/screenshots/Screen%20Shot%202022-10-13%20at%2013.31.23.png>

Here we use the contractBalance function to confirm the deposit was successful
<img src=https://github.com/samlawhead/Joint-Savings-Account-Solidity/blob/main/screenshots/Screen%20Shot%202022-10-13%20at%2013.31.35.png>

10 ether deposit is successful
<img src=https://github.com/samlawhead/Joint-Savings-Account-Solidity/blob/main/screenshots/Screen%20Shot%202022-10-13%20at%2013.33.46.png>

5 ether deposit is successful
<img src=https://github.com/samlawhead/Joint-Savings-Account-Solidity/blob/main/screenshots/Screen%20Shot%202022-10-13%20at%2013.34.10.png>

Withdraw function

Withdrawing 5 ether to account 1
<img src=https://github.com/samlawhead/Joint-Savings-Account-Solidity/blob/main/screenshots/Screen%20Shot%202022-10-13%20at%2013.37.35.png>

Withdrawal was successful
<img src=https://github.com/samlawhead/Joint-Savings-Account-Solidity/blob/main/screenshots/Screen%20Shot%202022-10-13%20at%2013.37.55.png>

Withdrawing 10 ether to account 2
<img src=https://github.com/samlawhead/Joint-Savings-Account-Solidity/blob/main/screenshots/Screen%20Shot%202022-10-13%20at%2013.38.17.png>

contractBalance function, lastWithdrawal function and LastToWithdraw functions respectively show the current balance, who was the last to withdraw funds and how much they withdrew
<img src=https://github.com/samlawhead/Joint-Savings-Account-Solidity/blob/main/screenshots/Screen%20Shot%202022-10-13%20at%2014.07.13.png>

---

## Contributors

Brought to you by Sam Lawhead.

---

## License

Copyright 2022

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
