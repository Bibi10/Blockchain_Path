# Blockchain_Path

## TECHNOLOGY

I - Blockchain Technology review

- Distributed Ledger
![alt text](https://github.com/Bibi10/Blockchain_Path/blob/master/DLedger.png 'Ledger')


A Distributed Ledger is a storage tool that is shared and synchonised across multiple party.It make an information available for any node of the network .

- Consensus Mechanism
  Its a fault taulerant mechanism that is used in blockchain system to achieve necessary agreement on a state of the network among distributed process.

- Mining
  Mining process involve solving complex mathematical problem using intrinsec hash fonctions linked to the block containing transaction data.Miners compete with each other to be the first to solve the mathematical puzzle.

- Public & Private blockchain
  There are different types of Blockchain :
![alt text](https://github.com/Bibi10/Blockchain_Path/blob/master/BTypes.png 'Blockchains')


- DL Platforms : 

II - Blockchain Primitives

- Crypographic Hash Functions

https://ethereum.stackexchange.com/questions/550/which-cryptographic-hash-function-does-ethereum-use

![alt text](https://github.com/Bibi10/Blockchain_Path/blob/master/CFunc.png 'Crypto')

Its a hash function use in cryptography which take an input and returns a fixed-size string of bytes.
The string is called the 'hash value', 'message digest', 'digital fingerprint', 'digest' or 'checksum'.

- Public Key Cryptography
  Public-Key Cryptography or asymetric cryptography, is a cryptographic system that uses pairs of keys(public and private) algorithm to secure data communication.

![alt text](https://github.com/Bibi10/Blockchain_Path/blob/master/PKey.png 'Pkey')

- Merkle Trees

![alt text](https://github.com/Bibi10/Blockchain_Path/blob/master/Mtree.png 'Tree')

Also called hash tree, is a tree in which every leaf node is labelled with the hash of a data block.

- Block
  ![alt text](https://github.com/Bibi10/Blockchain_Path/blob/master/Block.png 'Block')
  A block contains the set of valid unicode and hash transactions according to the laws of the blockchain.

- Blockchain Structure

![alt text](https://github.com/Bibi10/Blockchain_Path/blob/master/BStruct.png 'BStruct')

- Building Blockchain

- Smart Contracts
  A smart contract is a self-executing contract with the terms of the agreement between two parties being directly written into lines of code.

- Nodes
  The nodes are the administrative body of the blockchain and verify the legitimacy of the transactions in each block.



- Blockchain Forks
  ![alt text](https://github.com/Bibi10/Blockchain_Path/blob/master/Fork.png 'Fork')

A fork is defined variously as: "what happens when a blockchain diverges into two potential paths forward" "a change in protocol" or a situation that "occurs when two or more blocks have the same block height" .

III - Ethereum Basics

- What is Ethereum 
Launched in 2015, Ethereum is the world open source blockchain platform that enables developper to build Decentralized Applications.
While providing high availability, auditability, transparency, and neutrality, it also reduces or eliminates censorship and reduces certain counterparty risks.
Like other blockchains, Ethereum has a native cryptocurrency called Ether (ETH). ETH is digital money. If you’ve heard of Bitcoin, ETH has many of the same features. It is purely digital, and can be sent to anyone anywhere in the world instantly. The supply of ETH isn’t controlled by any government or company - it is decentralized, and it is scarce. People all over the world use ETH to make payments, as a store of value, or as collateral.

The Ethereum system is comprised of :

- Accounts
Ethereum is comprised of objects with 20 byte address that interact with one another,its called an account.
There are two types of account :
Externally  Owned Account and Contract account
Extrenal account are controlled by private keys with no code associated to.
Contract accounts are controlled by their contract code and have code associated with them.

- Transactions
Every interractions in ethereum are transactions between  accounts.

- Gas 
In solidity users have to pay everytime they execute a function on Dapp.
How gas is a required to execute a function depends on how complex that function's logic is .
Gas is the amount of ETH used to pay for a transaction in the network and its measured in WEI, where 1ETH is 1⁰¹⁸ Wei.

- Tokens 
Tokens are used to incentivize interrraction with a protocol.
There are many type of token standar due to people creating their own.
Exemple : ER223, 777, 827, 721..


IV - Traditional and Distributed App

- Distributed App (dApp)
A dApp is an app where the server side is unique and run by all ethereum node.
Dapp are way of building app for internet, it lets us run app with backend hosted on blockchain instead of normal server.
There are many platform of coding decntralized application : 
Since computing is one most important aspects of building dapps.

- Dev Tools
Truflle, Embark 
- Network State 
Ropsten, Mainnet, Kovan, Testnet, Rinkberry 

V - DEV Tools
There are large and growing tools to help developers build test and deploy their applications.
- Truffle : Its a development environment, testing framework.
- IDEs : Ethereum Studion, Vscode , remix Ethereum
- Frontend : Web3Js Ethereum Javascript API, Ethers.js, light.js
- Backend : Infura Ethereum API as service,Cloudfare, Alchemy,Chainstack..
- Storage : IPFS is a decentralized storage and file referencing system for Ethereum, Swarm, OrbitDB..
- Security Tools: Slither Solidity static analysis framework written in py3, MythX, Myrthril, Securify, ERC20 Verifier..
- Testing Tools: Solidity-Coverage Alternative solidity code coverage tool, hevm, whiteblock Genesis..
- Block Explorers : Etherscan, Blockscout, Etherchain
- Testnet : Testnet are network used by developer to test their applications under different conditions before deploying on Ethereum mainnet, Ropsten, Rinkberry, Goerli.
- Metamask : Is a bridge that allows you to visit distributed web in your browser.
- Dev Workflow Ganache
- Structure of Truffle Project
- Ethereum PM
- Ganache GUI

VI - SOLIDITY
Solidity is a statically typed language, witch means that type of variable needs to be specificed.
https://reference.auditless.com/cheatsheet/
- Data Types :
Booleans => bool : true and false 
Integers => int/uint 
- variables :
Global variables are special variables which exist in global workspace and provide information about blockchain and transaction properties.
Ex: Msg.sender
Local variables are only available within a function where it defined.
State Variables − Variables whose values are permanently stored in a contract storage.
- Mapping  
Mappings are other way of storing data in solidity.
Mapping is a essential key value store for storing data.

- Functions
Its a group of reusable cod e which can be called anywhere in your program.
function name(parameter) scope returns () {
}
- Storage & Memory
    storage: variables defined at the top level inside of the contract. (ex: items)
    memory: Structs ( Refer to http://solidity.readthedocs.io/en/v0.4.21/types.html if you do not know what a struct is)
    Storage is a key-value store where keys and values are both 32 bytes. Memory: Memory is a byte-array, which hold the data in it until the execution of the function.
Storage refers to variables stored permanently on the blockchain. 
Memory variables are temporary, and are erased between external function calls to your contract. Think of it like your computer's hard disk vs RAM.

VII - SMART CONTRACTS
  
- Intro
Smart Contract 
Smart Contract are written in solidity language and allow developers to interact with the ethereum blockchain.

- Immutability of Contracts 
After you deploy a contract to Ethereum, its immutable, which means that it can never be modified or updated again.
The smart contract code is law and no one can later change that function and give you unexpected results. 

- Contract Structure
Contract are similar to class in object-oriented languages.
- Creating smart Contract
- Smart Conracts ABI
- Events & Logs
- Factory Contracts
- Inter Contract Exec
- Inheritnce
- Libraries & EPM
- SC system Design

VIII - Writing a smart Contract (Proof of Existance)

- Multi Sig Wallet Excercise
- Debugging Truffle Tests
- Practice Writing SC


IX - ETHEREUM ANd END Users

- Introduction to web3
- Web3 Js Library
- Web3 to a Contract
- Building Truffle for the Web
- Update to Metamask
- Integrating with React
- Rimble UI

X - SMART CONTRACT PITFALLS,TESTING AND DEBUGGING

- Writing Tests
- Catching solidity erros in truffle Tests
- SC Pest Practices
- Exploit and Dangers
- Optimizing Gas
- Safety Checklist
- Security Analysis Tools
- txOrigin Attack Demo
- DDOS Attack Exemple
- Reetrancy Attack Example
- Integer Over/Underflow Example

XI - ADVANCE topics
- Immutability of Contracts
- SC Design Patterns
- Ethereum Name Service
- IPFS
- Upgradable Contracts
- Oracles with Rhombus
- Rhombus Network
- Formal Verification
- ZKP

XII - ADD TOPICS

- LLL
- Intro Vyper
- Writing SC in Vyper
- EIPs

## CRYPTOCURRENCY

## TRADING
