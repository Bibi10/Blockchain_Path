# Blockchain_Path

## TECHNOLOGY

I - Blockchain Technology review

- Distributed Ledger

![alt text](https://github.com/Bibi10/Blockchain_Path/blob/master/DLedger.png 'Ledger')

A Distributed Ledger is a storage tool that is shared and synchonised across multiple party.It make an information available for any node of the network .

- Consensus Mechanism
It's a fault taulerant mechanism that is used in blockchain system to achieve necessary agreement on a state of the network among distributed process.

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
  Externally Owned Account and Contract account
  Extrenal account are controlled by private keys with no code associated to.
  Contract accounts are controlled by their contract code and have code associated with them.

- Transactions
  Every interractions in ethereum are transactions between accounts.

- Gas
  In solidity users have to pay everytime they execute a function on Dapp.
  How gas is a required to execute a function depends on how complex that function's logic is .
  Gas is the amount of ETH used to pay for a transaction in the network and its measured in WEI, where 1ETH is 1⁰¹⁸ Wei.
  Fee for transaction = Total gas used \* gas price;

* Tokens
  Tokens are used to incentivize interrraction with a protocol.
  There are many type of token standar due to people creating their own.
  Exemple : ER223, 777, 827, 721..

IV - Traditional and Distributed App

- Distributed App (dApp)
  A dApp is an app where the server side is unique and run by all ethereum node.
  Dapp are way of building app for internet, it lets us run app with backend hosted on blockchain instead of normal server.
  There are many platform of coding decntralized application :
  Since computing is one most important aspects of building dapps, it make sense to get further with interracting wih smart contracts and then proceding further.

V - DEV Tools
Many blockchain development tools have been introduced to help develop blockchain.

. [Remix IDE](https://remix.ethereum.org/) : is an online web based development platform that help create, test and deploying smart contract.
. Truflle Framework((https://www.trufflesuite.com/): Is a framework for Ethereum that is install on computer and help develop and automate contract testing using chai and Mocha.

. [Geth](https://geth.ethereum.org/downloads/):
Geth is an ethereum client used for running ethereum nodes and can be used for mining ether tokens, create smart contracts, transfer tokens and explore the block history.

. [Ganache](https://www.trufflesuite.com/ganache):
Ganache is a tool from Truffle Suite that allows developers to create their own private Ethereum blockchain to test dApps. Deploying a dApp directly on Ethereum can cost you a lot of gas to verify transactions.

. [Metamask](https://metamask.io/)

Metamask is a wallet that acts as a bridge between Ethereum blockchain and Chrome or Firefox by working as a browser extension. It can be used for saving keys for ERC20 tokens and Ether.

. [Ethereum Studio](https://studio.ethereum.org/)

. [Vscode](https://code.visualstudio.com/)

- Network State
  While writing Ethereum Virtual Machine programs, you have to pay for the gas usage and launch of the app. Also, an untested program can lead to high costs as Ethereum blockchain is immutable and transactions added to it cannot be undone.
  Therefore, it is required to test a dApp before deploying it on the main network(mainnet).
- Block Explorers : Etherscan, Blockscout, Etherchain
- Testnet : Testnet are network used by developer to test their applications under different conditions before deploying on Ethereum mainnet, Ropsten, Rinkberry, Goerli.
- Metamask : Is a bridge that allows you to visit distributed web in your browser.
- Frontend : Web3Js Ethereum Javascript API, Ethers.js, light.js
- Backend : Infura Ethereum API as service,Cloudfare, Alchemy,Chainstack..
- Storage : IPFS is a decentralized storage and file referencing system for Ethereum, Swarm, OrbitDB..
- Security Tools: Slither Solidity static analysis framework written in py3, MythX, Myrthril, Securify, ERC20 Verifier..
- Testing Tools: Solidity-Coverage Alternative solidity code coverage tool, hevm, whiteblock Genesis.

VI - SOLIDITY
Solidity is a statically typed language, witch means that type of variable needs to be specificed.

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
- [Cheat Code](https://reference.auditless.com/cheatsheet/)

VII - SMART CONTRACTS

- Intro
  Smart Contract are written in solidity language and allow developers to interact with blockchain.

. Interestingly enough, the invention of smart contracts dates back to 1996. Computer scientist Nick Szabo drew up the term “smart contracts,” and explains them as follows:
“I call these new contracts “smart”, because they are far more functional than their inanimate paper-based ancestors. No use of artificial intelligence is implied. A smart contract is a set of promises, specified in digital form, including protocols within which the parties perform on these promises”
— Nick Szabo, 1996
His work later went on to inspire many other researchers and scientists, including Vitalik, who created Ethereum.

- Immutability of Contracts
  After you deploy a contract to Ethereum, its immutable, which means that it can never be modified or updated again, so its important to architect it well before develop it.
  The smart contract code is law and no one can later change that function and give you unexpected results.

- Contract Structure
  Contract are similar to class in object-oriented languages and contain declaration of State Variables, Functions, Function Modifiers, Events, Struct Types and Enum Types.

  ![alt text](https://github.com/Bibi10/Blockchain_Path/blob/master/CStruct.png'CStruct')

- Contract Design Patterns
  Best practices for solving problem exist in software engineering as in blockchain engeenering.

[List of Patterns](https://medium.com/@i6mi6/solidty-smart-contracts-design-patterns-ecfa3b1e9784) :
https://eprints.cs.univie.ac.at/5665/1/bare_conf.pdf

- Lifecycle : Contract Self Destruction
  Used to terminate or destroy a contract when its served it purpose.

contract SelfDesctructionContract {
public address owner;
public string someValue;
modifier ownerRestricted {
require(owner == msg.sender);
\_;
}
// constructor
function SelfDesctructionContract() {
owner = msg.sender;
}
// a simple setter function
function setSomeValue(string value){
someValue = value;
}
// you can call it anything you want
function destroyContract() ownerRestricted {
suicide(owner);
}
}

- Factory Pattern
  Is used to create and deploy child contract(referred to as "assets") addresses so the can be safe and used later.

contract CarShop {
address[] carAssets;
function createChildContract(string brand, string model) public payable {
// insert check if the sent ether is enough to cover the car asset ...
address newCarAsset = new CarAsset(brand, model, msg.sender);  
 carAssets.push(newCarAsset);  
 }
function getDeployedChildContracts() public view returns (address[]) {
return carAssets;
}
}
contract CarAsset {
string public brand;
string public model;
address public owner;
function CarAsset(string \_brand, string \_model, address \_owner) public {
brand = \_brand;
model = \_model;
owner = \_owner;
}
}

Widrawal : Withdrawal pattern
Maintenance : Data segregation
Security : Balance Limit
Authorisation : Ownership, Access Restriction

- Name Registry :
  This pattern allows you to only keep the address of one contract, instead of tens, hundreds or even thousands, as your DApp grows in scale. It works by storing a mapping contract name => contract address so each address can be looked up from within the DApp by callinggetAddress("ClothesFactory").

- Mapping Iterator :
  Many times we need to iterate a mapping, but since mappings in Solidity cannot be iterated and they only store values, the Mapping Iterator pattern turns out to be extremely useful. Some things to keep in mind are that as elements count goes up the complexity of iteration will increase, as well as the storage cost, so avoid iterating when possible.

- [Security](https://www.reddit.com/r/ethereum/comments/4omdlf/to_kickstart_the_building_safer_smart_contracts/)

The most popular blockchain development platform is Ethereum.

VIII - ETHEREUM Javascript API : Web3JS

- Introduction to web3JS
  Web3.js is a collection of librairies which allow you to interact with a local or remote ethereum node, using http or ipc connection.

- Web3 Js Library
  FIrst you need to get web3.js into your project by the following methods :
  . npm: npm install web3
  . meteor: meteor add ethereum:web3
  . pure js: link the dist/web3.min.js

The web3-eth is for the Ethereum blockchain and smart contracts
The web3-shh is for the whisper protocol to communicate p2p and broadcast
The web3-utils contains useful helper functions for DApp developers.

- Web3 Parameters
  . provider - string|object: A URL or one of the Web3 provider classes.
  . net - net.Socket (optional): The net NodeJS package.
  . options - object (optional) The Web3 options

Example :
import Web3 from 'web3';
// "Web3.givenProvider" will be set in a Ethereum supported browser.
const web3 = new Web3(Web3.givenProvider || 'ws://some.local-or-remote.node:8546', net, options);

> web3.eth
> web3.shh
> web3.utils
> web3.version

IX - SMART CONTRACT PITFALLS,TESTING AND DEBUGGING
We will create a diploma certificate on blockchain
Putting your diploma on blockchain makes it immutable and you won't rely on any governments or institutions to keep your records.
1- Environment setup

- [Download Metamask](https://studio.ethereum.org/):
  Lets go on the link and install the online wallet handler; don't worry about buying ethers we can have some testnets ones.
- Lets go on [remix](http://remix.ethereum.org/)

2- Dapp Architecture
Le'ts start designing our application by using the factory pattern.

X - ADVANCE topics

- Immutability of Contracts
- SC Design Patterns
- Ethereum Name Service
- IPFS
- Upgradable Contracts
- Oracles with Rhombus
- Rhombus Network
- Formal Verification
- ZKP

XI - ADD TOPICS

- LLL
- Intro Vyper
- Writing SC in Vyper
- EIPs

## CRYPTOCURRENCY

## FUNDRAISING

## TRADING
