# `                         Blockchain LAB::Notes::My Journey!`

![](./lab.svg)



## What is Blockchain?

![blockchain-introduction](G:\1.Code\===open source===\blockchain\blockchain-introduction.png)

> A blockchain is a constantly growing ledger which keeps a permanent record of all the transactions that have taken place in a secure, chronological, and immutable way.

Let's breakdown the definition,

- **Ledger:** It is a file that is constantly growing.
- **Permanent:** It means once the transaction goes inside a blockchain, you can put up it permanently in the ledger.
- **Secure:** Blockchain placed information in a secure way. It uses very advanced cryptography to make sure that the information is locked inside the blockchain.
- **Chronological:** Chronological means every transaction happens after the previous one.
- **Immutable:** It means as you build all the transaction onto the blockchain, this ledger can never be changed.

## Why Blockchain is Popular?

Blockchain technology has become popular because of the following.

- **Time reduction:** In the financial industry, blockchain can allow the quicker settlement of trades. It does not take a lengthy process for verification, settlement, and clearance. It is because of a single version of agreed-upon data available between all stakeholders.
- **Unchangeable transactions:** Blockchain register transactions in a chronological order which certifies the unalterability of all operations, means when a new block is added to the chain of ledgers, it cannot be removed or modified.
- **Reliability:** Blockchain certifies and verifies the identities of each interested parties. This removes double records, reducing rates and accelerates transactions.
- **Security:** Blockchain uses very advanced cryptography to make sure that the information is locked inside the blockchain. It uses Distributed Ledger Technology where each party holds a copy of the original chain, so the system remains operative, even the large number of other nodes fall.
- **Collaboration:** It allows each party to transact directly with each other without requiring a third-party intermediary.
- **Decentralized:** It is decentralized because there is no central authority supervising anything. There are standards rules on how every node exchanges the blockchain information. This method ensures that all transactions are validated, and all valid transactions are added one by one.

## History-Short

In **2008**, **Satoshi Nakamoto** conceptualized the theory of **distributed blockchains**. He improves the design in a unique way to add blocks to the initial chain without requiring them to be signed by trusted parties. The modified trees would contain a secure history of data exchanges. It utilizes a peer-to-peer network for timestamping and verifying each exchange. It could be managed autonomously without requiring a central authority. These improvements were so beneficial that makes blockchains as the backbone of cryptocurrencies. Today, the design serves as the public ledger for all transactions in the cryptocurrency space.

The evolution of blockchains has been steady and promising. The words block and chain were used separately in Satoshi Nakamoto's original paper but were eventually popularized as a single word, the Blockchain, by **2016**. In recent time, the file size of cryptocurrency blockchain containing records of all transactions occurred on the network has grown from **20 GB** to **100 GB**.

## What is Bitcoin?

> A bitcoin is a type of digital assets which can be bought, sold, and transfer between the two parties securely over the internet. Bitcoin can be used to store values much like fine gold, silver, and some other type of investments. We can also use bitcoin to buy products and services as well as make payments and exchange values electronically.

 It is commonly called **decentralized digital currency**.

## How Bitcoin Works?

**For example**, Suppose you click on a photo that you want to send it to another person, so you can simply attach that photo to an email, type the receiver email address and send it. The other person will receive the photo, and you think it would end, but it is not. Now, we have two copies of photo, one is a simple email, and another is an original file which is still on my computer. Here, we send the copy of the file of the photo, not the original file. This issue is commonly known as the **double-spend** problem.

![](G:\1.Code\===open source===\blockchain\how-bitcoin-works.png)

The double-spend problem provides a challenge to determine whether a transaction is real or not. How you can send a bitcoin to someone over the internet without needing a bank or some other institution to certify the transfer took place. The answer arises in a global network of thousands of computers called a Bitcoin Network and a special type of decentralized laser technology called **blockchain**.

In Bitcoin, all the information related to the transaction is captured securely by using maths, protected cryptographically, and the data is stored and verified across the entire network of computers. In other words, instead of having a centralized database of the third-party such as banks to certify the transaction took place.

## Blockchain Version

![](G:\1.Code\===open source===\blockchain\blockchain-version.png)

**Blockchain 1.0: Currency**

Bitcoin is the most prominent example in this segment. It is being used as **cash for the Internet** and seen as the enabler of an **Internet of Money**.

** Blockchain 2.0: Smart Contracts**

The main issues that came with Bitcoin are wasteful mining and lack of network scalability. To overcome these issues, this version extends the concept of Bitcoin beyond currency. The new key concepts are Smart Contracts. It is small computer programs that **"live"** in the blockchain. They are free computer programs which executed automatically and checked conditions which are defined earlier like facilitation, verification or enforcement. The big advantage of this technology that blockchain offers, making it impossible to tamper or hack Smart Contracts. A most prominent example is the Ethereum Blockchain, which provides a platform where the developer community can build distributed applications for the Blockchain network.

Quickly, the blockchain 2.0 version is successfully processing a high number of daily transactions on a public network, where millions were raised through **ICO** (Initial Coin Offerings), and the market cap increased rapidly.

**Blockchain 3.0: DApps**

DApps is also known as a decentralized application. It uses decentralized storage and communication. Its backend code is running on a decentralized peer-to-peer network. A DApp can have **frontend code** hosted on decentralized storages such as Ethereum Swarm and **user interfaces** written in any language that can make a call to its backend like a traditional Apps.

## How is the Bitcoin Blockchain built?

The role of a minor is to build the blockchain of records that forms the bitcoin ledger. These ledgers are called blocks, and each block contains all the different transactions that have taken place. A new block is added in **every 10 minutes** as a new Bitcoin Transaction takes place.  ![role-of-bitcoin-miners](G:\1.Code\===open source===\blockchain\role-of-bitcoin-miners.png)
So, as the minors process these different transactions, they build the block, and when a block is confirmed, it gets added to the blockchain. The bitcoin blockchain provides a permanent record of all bitcoin transactions to the beginning.

## Blockchain Hash Function

A hash function takes an input string (numbers, alphabets, media files) of any length and transforms it into a fixed length. The fixed bit length can vary (like 32-bit or 64-bit or 128-bit or 256-bit) depending on the hash function which is being used. The fixed-length output is called a hash. This hash is also the cryptographic byproduct of a hash algorithm. We can understand it from the following diagram.

![blockchain-hash-function](G:\1.Code\===open source===\blockchain\blockchain-hash-function.png)

**The hash algorithm has certain unique properties:**

1. It produces a unique output (or hash).

2. It is a one-way function



## How does the hashing process works?

**SHA-256**::A Bitcoin's blockchain uses SHA-256 (Secure Hash Algorithm) hashing algorithm. In 2001, SHA-256 Hashing algorithm was developed by the National Security Agency (NSA) in the USA.

Online Playground: http://onlinemd5.com/

## ::Block Chain 4 React Developer::

**Blockchain** is about building decentralized apps. Apps and data which are controlled by a community rather than a single organization.

**Ethereum** is a protocol for Blockchain technology. It is a suite of programs and utilities to manage the Blockchain. Get helps to run a node which can mine transactions. Mist is a wallet program which interacts with a Get node to manage accounts.

For React developers, Web3 is a JS package to interact with Blockchain. TestRPC runs a node without the mining component. With Web3 and TestRPC, we can set our development environment for React apps to interact with the blockchain.

Contracts control the transfer of ether between accounts in a blockchain. Contracts are developed using Solidity language in Remix or Ethereum Studio. To manage contracts and test them, we use Truffle package from NPM.

## How Block Hashes Work in Blockchain

A blockchain is a concept of storing data digitally. This data comes in blocks. These blocks are chained together and make the data **immutable**. When a block of data is chained with the other blocks, its data can never be changed again. 

## Basic Components of BitcoinIn 

This section, we are going to learn about the four basic components of bitcoin. These four elements will help us to understand the bitcoin blockchain in a more clear way. We can see the basic components of bitcoin in the following :

1. Software

2. Cryptography

3. Hardware

4. Miners(Gaming Theory)

    

   ![components-of-bitcoin](G:\1.Code\===open source===\blockchain\components-of-bitcoin.png)

**First Component: Software**

Bitcoin is basically a software at the core that defines what a bitcoin is, as well as how a bitcoin gets transferred. It identifies what the rules of a valid bitcoin, who can be inside bitcoin, who cannot be inside bitcoin, **what is valid, what is not,** etc. Everything is based on software, which is the bitcoin software. The bitcoin software is always operated in 24*7.

**Second component: Cryptography**
The software, at its core, uses cryptography and bitcoin as a cryptocurrency. Bitcoin uses cryptography to regulate the transfer of bitcoin between parties, as well as the creation of new units of bitcoin. Without cryptography, Bitcoin would simply not be possible. So, we've got that this software uses **cryptography to control the secure  transfer of bitcoin over the internet.**

Cryptography is a mathematical approach which is solvable by computers and not by humans. So all the stuff that protects your data is served by the cryptography.

**Third Component: Hardware**
To run and solve cryptography, it needs HARDWARE. This hardware is composed of those thousands of miners around the world running their computers. So there are thousands of computers around the world that are basically running the Bitcoin software or the Bitcoin client. **This hardware is specially designed for finding Nonce to validate block and hash. It requires a lot of CPU power to complete a simple task on the bitcoin blockchain.**

If you try to mine bitcoin right now with your smartphone or home computer, then you will End up losing your computer along with a hefty electric bill.

**Fourth Component: Mining(Gaming Theory)**
Miners are users who involved in a gaming theory because bitcoin is truly a game which is run by these miners around the world. In the above, we have seen that the first component is software for bitcoin that issues a cryptography challenge in every 10 minutes. The cryptography challenge involves in trying to find a Nonce which will make the hash for a specific block valid. All the hashes and validations are done by these miners. After successful creation of the block, the new block is added to the blockchain.

Let's see how gaming theory works!

**1.** Bitcoin software creates a challenge. Now, there is a game begins, and there is a race that goes off. The race involves all these miners competing against each other to solve the challenges.

**2.** This task or challenge will take approximately 10 minutes to be completed.

**3.** Every single miner starts trying to find the solution to that one Nonce that will satisfy the hash for the block.

**4.** At some specific point, one of those miners in the global community with higher speed and great hardware specs will solve the cryptography challenge and be the winner of that race.

**5. **Now, the rest of the community will start verifying that block which is mined by the winner. This makes Bitcoin so strong, because in one stage of this cycle, the miners are competing against each other, and in the next stage of the cycle, the rest of the community rallies together to ensure that that solution is correct.

**6.** If the Nonce is correct, it will end up with the new block which will be added to the blockchain.
For this task or challenge, the winner will earn a reward. That reward is currently 12.5 bitcoins.

## Blockchain Proof of work

Proof of Work(PoW) is the **original consensus algorithm** in a blockchain network. The algorithm is used to confirm the transaction and creates a new block to the chain. 

In this algorithm, **minors** (a group of people) compete against each other to complete the transaction on the network. The process of competing against each other is called **mining**. As soon as miners successfully created a valid block, he gets **rewarded**. The most famous application of Proof of Work(PoW) is Bitcoin.

## Coinbase Transaction

![coinbase-transaction](G:\1.Code\===open source===\blockchain\coinbase-transaction.png)

A coinbase transaction is the **first** transaction in a block. It is a **unique** type of bitcoin transaction that can be created by a miner. The miners use it to collect the block reward for their work and any other transaction fees collected by the miner are also sent in this transaction.

The miners are always responsible for creating a block. When a block is successfully created, he will be rewarded from bitcoin for their work.

## Explanation

Each transaction executed on the [bitcoin](https://www.javatpoint.com/bitcoin) network are combined together to form a block. When a block is formed, immediately, it will be added in the blockchain. Now, these blocks are immutable and tamper-proof for all transactions that are made on the bitcoin network. Each block must contain one or more transactions, and the first transaction in the block is called the **coinbase transaction**.



## Key Concepts of Bitcoin

There are four key concepts that you need to aware in Bitcoin. These are:

- Disintermediated
- Distributed
- Decentralized
- Trustless

**1. Disintermediated**

When you send money to someone over the Internet, you need a third party like banks which manages all your transactions. But in you are doing transactions directly to another party over the Internet. This transaction takes place in the Bitcoin network. This network takes care of confirming and verifying that there was a true transfer of value between the two parties. This concept is called Disintermediated.

The Disintermediated is the act of:
**a) Removing the middleman.
b) No 3rd Party like bank
c) No verification** 

**2. Distributed**

The entire bitcoin network runs on a network of thousands of distributed computers which shares the work. So, instead of having one centralized computer which handles the workload, you are distributing it across multiple computers. The distributed network is more reliable because there is no single point of failure. Here, **the work is shared across thousands of computers which are all running and sharing the workload.**

**3. Decentralized**

Bitcoin is decentralized. It means that there is **no central control,** no central repository of data and **no management in the middle** that overseeing what Bitcoin does. As a result, there is no central point of failure.

**4. Trustless**

Bitcoin is Trustless because there is no need to have a third-party, such as a bank to certify and bring trust to the entire process of transactions. Instead, the blockchain and how Bitcoin process the transactions enable the trust is done by Distributed Trustless Consensus in which all the nodes agree that a transaction took place.

## Blockchain Cryptocurrency

Cryptocurrency is a type of **digital asset** which is used to exchange value between parties. It uses strong **cryptography** to secure financial transactions and control the creation of new units of that currency and verify the transfer of assets. Cryptocurrency does not exist physically.

**1.Bitcoin**

Bitcoin is generally known as the first decentralized cryptocurrencies. It is created by the network of thousands of specific nodes called **miners**. The miners can process the bitcoin transactions in the blockchain network. Since the release of bitcoin, more than **4000** alternative variants of bitcoin are available now.

**2.Litecoin**

Litecoin cryptocurrency worked very similar to Bitcoin. We know that bitcoin wait **ten minutes** for a transaction block to be processed, but Litecoin can do this in maximum **two and a half minutes**. Litecoin doesn't have a big market cap. The price of Litecoin is lower than Bitcoin, but it's a very effective process and also has some variations from Bitcoin.

**3.Z-Cash**

Z-Cash is a **privacy-protecting** digital currency which is built-on strong science in cryptography. It provides enhanced privacy for its users as compared to other cryptocurrencies such as bitcoin. Here, transaction data is kept confidential, which is made possible through **zero-knowledge proofs**. It allows transactions to be verified without any information about the sender, receiver, and the amount transacted.

Z-Cash features known as **viewing keys** and **payment disclosure** makes it possible to disclose some of the user's transaction data. It makes the transactions on Z-Cash auditable and regulation-compliant.

**4.Monero**

Monero is an open-source cryptocurrency which focuses on **untraceable**, **privacy** and **decentralization**. It is fast, private, and secure digital cash, which is operated by a network of users. We can use it to buy and sell things and can exchange for other coins or tokens.

It uses a special kind of cryptography which ensures that the transactions remain 100% untraceable. It focuses on anonymity, which is harder to track, whereas Bitcoin is pseudonymous, which transactions are still traceable.

**5.Dash**

Dash is a short form of **Digital Cash**. It is an open-source cryptocurrency and is a form of a decentralized autonomous organization which is run by a subset of users, called master nodes. It is one of the most promising alternative coins to bitcoin. It permits very fast transactions, which are untraceable.