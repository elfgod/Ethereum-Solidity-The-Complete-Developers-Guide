# Ethereum and Solidity: The Complete Developer's Guide

Use Ethereum, Solidity, and Smart Contracts to build production-ready apps based on the blockchain  
Instructor: **Stephen Grider**  
Course Repository:

## Course content

- What is Ethereum?
- Smart Contracts with Solidity
- Advanced Smart Contracts
- Building Interactive Front-Ends
- Real Projects with Ethereum
- Ethereum Project Infrastructure
- Advanced Multi-Page Front-Ends
- Appendix: Basic React
- Extras

## Section 1: What is Ethereum?

### Folder 01:

### 1. Introduction

An Ethereum Network:  
A network of interconnected nodes  
node <--> node <--> node <--> node <-->

- Ethereum networks are used to transfer money and store data
- There are many different Ethereum networks
- Networks are formed by one or more nodes
- Each node is a machine running an ethereum client
- Anyone can run a node
- Each node can contain a full copy of the blockchain
- The 'blockchain' is database that stores a record of every transaction that has ever taken place

For Developers: web3.js  
For Consumers: Metamask, Mist Browser

### 2. A Short History Lesson

Original White paper of Bitcoin and Ethereum  
Bitcoin: A Peer-to-Peer Electronic Cash System (https://bitcoin.org/bitcoin.pdf)  
Ethereum: The Ultimate Smart Contract and Decentralized Application Platform (http://web.archive.org/web/20131228111141/http://vbuterin.com/ethereum.html)

### 3. Metamask Setup

1. Search for the Metamask extension in Chrome or Firefox and install it
2. Follow and then select Create wallet
3. Follow the instructions
4. Click Ethereum Mainnet and select Show/Hide test networks
5. Toggle the Show test networks button to ON (You can now change between networks now)

### 4. Ethereum Accounts

Metamask:

- account address is like the e-mail name
  Account Address: 123456789101112131415
- public key and private key are use to authorize the sending of funds from your accc to other acc's
  Public Key: 123456789101112131415
- private key is the true access to the funds to the account
  Private Key: 123456789101112131415

- Private and Public Keys are hexadecimal numbers

What is hexadecimal?  
Hexadecimal is a numbering system with base 16. It can be used to represent large numbers with fewer digits.

In this system there are 16 symbols or possible digit values from 0 to 9, followed by six alphabetic characters -- A, B, C, D, E and F. These characters are used to represent decimal values from 10 to 15 in single bits.  
https://www.techtarget.com/whatis/definition/hexadecimal

### 5. Getting Test Ether to Use in the Course

1. Visit https://faucets.chain.link

2. Make sure you are signed into Metamask in your browser, and the Goerli Test Network is selected:

3. Temporarily disable any other wallet extensions you may have running in the browser (such as the Coinbase wallet). These wallets will cause a conflict with Metamask when trying to obtain funds.

4. Click the Connect wallet button in the top right corner of the page:

5. Click the Login via Twitter button to authenticate with your Twitter account.

6. Check the I am human box and solve the Captchas.

7. Click Send request (Important - You'll probably want to make three requests to get at least 0.3 Ether to use in the course. You can always come back for more on another day if you need)

8. After a few seconds or minutes, you should see a notification that the transaction was successful.

9. You should then be able to see your Metamask balance increase:
