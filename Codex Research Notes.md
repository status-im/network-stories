# Codex
Tags: #storage #data #durability #erasure-coding #incentivization #marketplace #DHT #discovery #network #libp2p #devp2p #peers #records #Messaging #zero-knowledge #privacy 

What
 - P2P decentralized data storage with incentivized durabiliity and bandwidth

Why
- Web3 is about decentralization
- It needs a practical decentralized storage layer
- Centralized solutions:
	- Censorship
	- Monopolozation
- Current solutions don't address all the challenges

How
- Automated remote auditing of data possession
- Durability through strong redundancy
	- thru Erasure-coding
	- not replication
		- replication is full copy

Discovery
 - uses Discovery v5
	 - uses DevP2P

Durability
 - what is the ratio of replication of information to parity information and quantity of replicated information to figure out how "durable" data is. 

Erasure Coding
- Relationship between tokenomics incentivizing growth of data nodes such that dispersion keeps growing to accomodate increasing durability (cheaper storage over time which grows to increase redundancy seems related to price of Codex token)
- if small error restoration is expensive, can you purposefully destroy larger sectors to "cheapen" restoration process? (this can be done by a user?)
- how does BitTorrent work on mobile (light nodes) in order to provide parity space or even full data replication?

Proofs of Storage
- Necessary to prove data is still there (availability)
	- Data Integrity
	- Data Availability
	- Data Possession (Most important)
	- Retrievability
	- Replication


The Complex World of Storage Proofs
- How much smaller is data size are these proofs compared to the actual data requested/storage/etc.? Ratio?

To Learn
- Learn how Erasure Coding works (want a better understanding of how much data replication exists)
- Polynomial committments
- homomorphic encryption
- compact proof
	- compress from two-dimensions:
		- challenge
		- signature