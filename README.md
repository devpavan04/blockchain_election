# Blockchain Voting DAPP
This is a Voting DAPP powered by ethereum smart contract.

> This DAPP introduces to the very basic understanding of how Smart Contracts work, how they can be deployed on a local blockchain.

## What is a Blockchain?
A blockchain, is a growing list of records, called blocks, that are linked using cryptography. Each block contains a cryptographic hash of the previous block, a timestamp, and transaction data. By design, a blockchain is resistant to modification of the data. 

## What is a Smart Contract?
A smart contract is a computer protocol intended to digitally facilitate, verify, or enforce the negotiation or performance of a contract. Smart contracts allow the performance of credible transactions without third parties. These transactions are trackable and irreversible. 

## What does this DAPP do?
1. There are two candidates who are participating for the election.
2. Voter can vote any one of the candidate through his/her digital wallet i.e [Metamask](https://metamask.io).
3. This application runs on a local blockchain i.e [Ganache](https://www.trufflesuite.com/ganache).
4. Ganache comes bundled with 10 dummy accounts with each having a 100 fake ethers in it already.
5. Ganache is connected to the metamask wallet using **web3.js** library.
6. Voter casts the vote using any one of his 10 accounts from the ganache using the private key(which is not recommended to be used on the real network) of that particular account.
7. Every time a transaction is made i.e voting in this case, a new block is added to the blockchain which contains all the details of the transactions happened from the begining.

> This DAPP is not deployed on the real network.

> This DAPP runs on the local blockchain on our computer.

# Screenshots

### Open Ganache
![open ganache](https://github.com/devpavan04/blockchain_election/blob/master/images/Screenshot%20from%202019-09-29%2003-29-36.png?raw=true )

### Metamask Sign in
![meta mask sign in](https://github.com/devpavan04/blockchain_election/blob/master/images/Screenshot%20from%202019-09-29%2003-31-03.png?raw=true)

### Copy account's private key to import new account
![copy account's private key to import new account](https://github.com/devpavan04/blockchain_election/blob/master/images/Screenshot%20from%202019-09-29%2003-31-50.png?raw=true)

### Import new account
![import new account](https://github.com/devpavan04/blockchain_election/blob/master/images/Screenshot%20from%202019-09-29%2003-32-10.png?raw=true)

### Welcome to the voting page
![welcome to voting page](https://github.com/devpavan04/blockchain_election/blob/master/images/Screenshot%20from%202019-09-29%2003-33-08.png?raw=true)

### Confirm transaction to cast the vote
![confirm transaction to cast the vote](https://github.com/devpavan04/blockchain_election/blob/master/images/Screenshot%20from%202019-09-29%2003-33-29.png?raw=true)

### Transaction confirmed, vote is updated!
![transaction confirmed, vote is updated!](https://github.com/devpavan04/blockchain_election/blob/master/images/Screenshot%20from%202019-09-29%2003-33-37.png?raw=true)