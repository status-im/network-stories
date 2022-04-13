# Understanding the Logos Blockchain Whitepaper
>Title: Understanding the Logos Blockchain Whitepaper | A High-Level Conceptual Overview/Review of the Logos Blockchain
>
>Purpose: 
>This document reflects an approach of whitepaper review that combines a rough-draft whitepaper review containing comments/reflections/concerns with a further simplification of concepts to make everything more digestible to more people outside of the internal Status infra team for communication purposes. In addition, this review will provide a gauge of difficulty of understanding involved with various different terms/concepts.
>
Tags: #learning #whitepaper #Logos

---

**"We build everything on top of consensus." **
Dr. Corey Petty

---

**How-To (Get Cookin')**

*There are some descriptions below which detail the usage of visual guidance metrics available in the form of "cookbook-like" instructions for how to consume this document:*

|  Gauges  |     Description    | Visualization |
| -------- | :-----------: |  :----------:  |
|Difficulty| 1-10 (Ticks/Pips) |  [&#124;&#124;&#124;&#124;&#124;&#124;&#124;&#124;&#124;&#124;]  | 
|Time      | In Minutes | X Minutes |
|Resources | Article/Video Links w/ Visual Content | Conceptual & Pictoral "Ingredients List" of Links|

See below 'Recipe' and modify accordingly to above in Figma.

![](../Pasted%20image%2020220411034611.png)

---
**Operating Definitions:**
*Easiness/Difficulty* is defined as the ease of which the concepts can be generally understood.

*Time/Scope* is in reference to the size of information necessary to learn to gain a decent level of comprehension.

*Resources* is for links relevant to helping people understand the concepts.

---

## Necessary Terminology by Layer

---
### The Six (6) Technology Layers of Logos as a Blockchain
- Terminology Template: [[here]]
#### Consensus
- [[BBA]]
- [[Leaderless]]
- [[DAGs]]
- [[CIC]]
- [[Messaging]]
- [[Permissionless]]
- [[Scalability]]
- [[Decentralization]] 
- [[Security]]
- [[Communication Costs]]
- [[Stream or Subgraph]]
- [[Staking]]
- [[Sybil Resistance]]
- [[CFT (Crash Fault Tolerant)]]
- [[BFT (Byzantine Fault Tolerant)]]
- [[Finality]]
- [[Social Applications]]
- [[Bootstrapping]]
- [[Rounds]]
- [[Round-less]]
- [[PBFT]]
- [[DAG-Based Consensus (Avalanche-like)]]
- [[Liveness]]
- [[Asynchronous (P2P)]]
- [[Execution-Layer Decoupling]]
- [[Interchangeability]]
- [[Liveness]]
- [[Extensibility]]
- [[Highly-Partitioned Blockchains with Local Views]] 
- [[Ordering]]
- [[Reputation]]
- [[Confidence]]
- [[Network Congestion]]
- [[Topology]]
- [[Resilience (Consensus context)]]
- [[Verifiability]]
- [[Non-Repudiation]]
- [[Snowball]]
- [[Lachesis]]
- [[Glacier]]

#### Node Reputation
- [[Ikingut (Reputation Algorithm)]]
	- [[Important Conceptual Goals]]
		- Simple
		- Lightweight
		- Pluggable
		- Adaptive
		- Dynamic
		- Robust
		- No Transitive Trust
		- Reasonable Bootstrap Time
	- [[Reputation Polling]] (Polling Dynamics)
		- [[Indirect Request]]
		- [[Direct Request]]
			- [[Unirep]] (an example)
			- [[Qualities Necessary]]
				- [[Requires Verifiability]]
				- [[Requires Non-Repudiation]]
				- [[Privacy Preserving]] (preserve origins of score, emit opinions without a way to trace back the origins - MPC)
		- [[ Local Heuristic]]
	- [[Algorithm]]
		- Each Iteration
			1. Voting
			2. Agent Action (Post-Consensus Decision Finality)
		- Min-Multiplicative Reputation Punishment
			- Multiplicative
			- Linear
	- Experimental Research
		- Starting Point
			- Trust Wisdom per Node (requires further elaboration)
			- Adversary Types and Effects (requires further elaboration)
		- Current Stage of Testing/Challenges
			- Silent-Omniscient Adversaries
			- Modulating Punishment/No Punishment Impacts to Conditions
			- Adding Multiplicative-min Punishment
			- Attacks
				- Con-Artist Attack
				- The On-Off Attack
			- Effects on Glacier Consensus
			- Limitations
				- No immediate defense against coordinated attacks
				- Reputation does not add to security
		- Future Work
			- Circumstantial Impact of Reputation on Consensus
			- Long-running Simulation
			- Sudden changes in Collective Byzantine Behavior
			- Pending Questions
				1. Interaction of Stake-based and Reputation-based selection
					- Stake simulations are necessary for exploring options
					- Relevant in the incentives discussion?
				2. How much (and if) does reputation really help in a coordinated attack? (Assuming patient con-artist attack)
					- Complex interactions here, this model would particularly benefit having a prototype/PoC
- [[Node Challenges]]
	1. [[Intermittence Flexibility | Maintain Operation in High-Churn Network]]
	2. [[Sudden Changing Behavior]]
	3. [[Bootstrapping Quickly]]
	4. [[Resilience to Dynamic Unpredictable Network Changes (Can Handle Membership Volatility)]]
- [[Design]] 
	1. [[Local reputation view]]
	2. [[Adaptive and Dynamic]]
	3. [[Required Bootstrapping]]
		- [[Network View Not Required]]
		- [[Individual Node Reputation Not Required]]
- [[Eigentrust]]
	- [[Transitive Trust]]
	- [[Understanding the Math]]
	- [[Trust Decay]]
		- [[Malicious Clusters]] (describe nuances better | trusted nodes cannot overlap the malicious collective)
	- [[Trust for Consensus]]
	- [[Separation of Reputation]]
	- [[Confidant]]
	- [[XRep]]
	- [[P-Grid]]
	- [[R2Trust]]
- [[Generic Taxonomy]]
	- [[Dimensions]]
		- #Single
		- Multiple
	- [[Time computation]]
	- [[Aggregation]]
		- Deterministic sum of positive and negative ratings
		- Probabilistic
	- [[Logic]]
		- Local vs gathered data
		- Age of data
		- Frequency of data
		- Weight of multiple dimensions
	- [[Value Control]]
		- External
		- Internal
	- [[Data Aging]]
		- None
		- Decay
		- Death of old/selected
	- [[Selection]]
		- Ranking-based
		- Threshold (trusted/untrusted)
		- Probabilistic selection


#### Network Layer and Mempool

#### Staking and Multi-DAG
#### Data Model and Concurrency
#### Tokenomics
