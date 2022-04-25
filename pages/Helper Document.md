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

## **How-To (Get Cookin')**
*Instructions: There are some descriptions below which detail the usage of visual guidance metrics available in the form of "cookbook-like" instructions for how to consume this document:*

|  Gauges  |     Description    | Visualization |
| -------- | :-----------: |  :----------:  |
|Difficulty| 1-10 (Ticks/Pips) |  [&#124;&#124;&#124;&#124;&#124;&#124;&#124;&#124;&#124;&#124;]  | 
|Time      | In Minutes | X Minutes |
|Resources | Article/Video Links w/ Visual Content | Conceptual & Pictoral "Ingredients List" of Links|

See below 'Recipe' and modify accordingly to above in Figma.

	![[Pasted image 20220415164934.png]]
---
## **Operating Definitions:**

Prep (*Difficulty*) is defined as the ease of which the concepts can be generally understood. (Future: Make into more fun visual or something more enjoyable than a difficulty bar.)

Cook Time (*Scope*) is in reference to the size of information necessary to learn to gain a decent level of comprehension.

Ingredients (*Resources*) is for links relevant to helping people understand the concepts. Number references and use superscript notation to reference mentions in terminology Recipes descriptions.

	Future Work: Adjust difficulty/time ratings, cook time respec. based on feedback from everyone at DXB.

---

## Necessary Terminology by Layer

---
### The Six (6) Technology Layers of Logos as a Blockchain
- Terminology Template (Recipe): [[here]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients: [pictures, videos, article links, research papers, etc.]
#### Consensus
- [[BBA]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://arxiv.org/pdf/2001.07867.pdf
- [[Leaderless ]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://ieeexplore.ieee.org/document/9546485
- [[DAGs]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://en.wikipedia.org/wiki/Directed_acyclic_graph
		2. https://tokens-economy.gitbook.io/consensus/chain-based-dag/direct-acyclic-graph-tangle-dag
- [[CIC]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. See 'Consensus' section within Logos Specifications
- [[P2P Messaging]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://en.wikipedia.org/wiki/Peer-to-peer
- [[Message Passing]] (is a general framework, P2P Messaging is a subset of Message Passing)
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- [[Gossip Protocol]] (is a subset of P2P Messaging)
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://en.wikipedia.org/wiki/Gossip_protocol#:~:text=A%20gossip%20protocol%20or%20epidemic,all%20members%20of%20a%20group.
- [[Permissionless]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://eprint.iacr.org/2021/023.pdf
- [[Scalability]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://eprint.iacr.org/2021/023.pdf
		2. https://medium.com/vechain-foundation/what-does-scalability-really-mean-in-blockchain-b8b13b3181c6
		3. https://101blockchains.com/blockchain-scalability-challenges/
- [[Decentralization]] 
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://en.wikipedia.org/wiki/Decentralization
		2. https://blockworks.co/measuring-decentralization-is-your-crypto-decentralized/
		3. https://jods.mitpress.mit.edu/pub/7vxemtm3/release/2
- [[Security]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://arxiv.org/pdf/1802.06993.pdf
- [[Communication Costs]] (wrt message complexity - see how this extends into hardware)
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.221.883&rep=rep1&type=pdf#:~:text=message%20complexity%20denotes%20the%20maximum,last%20node%20completes%20the%20algorithm.
- [[Stream or Subgraph]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://thegraph.com/docs/en/developer/define-subgraph-hosted/
		2. https://streamingfastio.medium.com/streamingfacts-understanding-the-costs-of-upgrading-a-subgraph-fedf5d61223 (is this related?)
- [[Staking]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://deliverypdf.ssrn.com/delivery.php?ID=112001112005005071028123005115028071053009053038065056030075021066021091100007083094098007039126015013042085120028028079118118027039038017006093067005067006124005093039032030000094104124024001105026027114005123097090090111113068087076002030115100122071&EXT=pdf&INDEX=TRUE
		2. https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3609817
		3. https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4059460
- [[Sybil Resistance]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://en.wikipedia.org/wiki/Sybil_attack
- [[CFT (Crash Fault Tolerant)]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://medium.com/@chamirachid/your-journey-to-consensus-part-1-6a88a6f818f65
		2. https://en.wikipedia.org/wiki/Fault_tolerance5
		3. https://dl.acm.org/doi/pdf/10.1145/102792.102801
- [[BFT (Byzantine Fault Tolerant)]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://en.wikipedia.org/wiki/Byzantine_fault
- [[PBFT (Practical Byzantine Fault Tolerant)]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://www.geeksforgeeks.org/practical-byzantine-fault-tolerancepbft/#:~:text=Practical%20Byzantine%20Fault%20Tolerance%20is,optimized%20for%20low%20overhead%20time.
		2. https://www.usenix.org/legacy/events/nsdi09/tech/full_papers/clement/clement.pdf
- [[Finality]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://medium.com/mechanism-labs/finality-in-blockchain-consensus-d1f83c120a9a5
- [[Social Applications]] (look up context)
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Bootstrapping]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://en.wikipedia.org/wiki/Bootstrapping_node#:~:text=A%20bootstrapping%20node%2C%20also%20known,successfully%20join%20the%20overlay%20network.
- [[Rounds]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Round-less]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Paxos]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[DAG-Based Consensus]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. https://www.sciencedirect.com/science/article/pii/S2352864819301476
- [[Liveness]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Asynchronous (P2P)]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Execution-Layer Decoupling]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Interchangeability]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Liveness]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Extensibility]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Highly-Partitioned Blockchains with Local Views]] 
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Ordering]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Reputation]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Confidence]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Network Congestion]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Topology]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Resilience (Consensus context)]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Verifiability]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Non-Repudiation]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Snowball]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Lachesis]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.
- [[Glacier]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1.

#### Node Reputation
- [[Ikingut (Reputation Algorithm)]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		 1. 
	- [[Important Conceptual Goals]]
		- Prep: [||||||||||]
		- Cook Time: X min
		- Ingredients:
			1.
			- Simple
			- Lightweight
			- Pluggable
			- Adaptive
			- Dynamic
			- Robust
			- No Transitive Trust
			- Reasonable Bootstrap Time
	- [[Reputation Polling]] (Polling Dynamics)
		- Prep: [||||||||||]
		- Cook Time: X min
		- Ingredients:
			 1. 
		- [[Indirect Request]]
			- Prep: [||||||||||]
			- Cook Time: X min
			- Ingredients:
				1.
		- [[Direct Request]]
			- Prep: [||||||||||]
			- Cook Time: X min
			- Ingredients:
				1. 
			- [[Unirep]] (a pre-existing example)
			- [[Qualities Necessary]] (of Direct Request)
				- [[Verifiability]]
				- [[Non-Repudiation]]
				- [[Privacy Preserving]] (preserve origins of score, emit opinions without a way to trace back the origins - MPC)
		- [[ Local Heuristic]]
	- [[Glacier Algorithm]]
		- Prep: [||||||||||]
			- Cook Time: X min
		- Ingredients:
			- Each Iteration
				1. Voting
				2. Agent Action (Post-Consensus Decision Finality)
			- Min-Multiplicative Reputation Punishment
				- Multiplicative
				- Linear
	- Experimental Research
		- Starting Point
			- [[Trust Wisdom per Node]] (requires further elaboration)
				- Prep: [||||||||||]
				- Cook Time: X min
				- Ingredients:
					1. 
			- [[Adversary Types and Effects]] (requires further elaboration)
				- Prep: [||||||||||]
				- Cook Time: X min
				- Ingredients:
					1. 
		- Current Stage of Testing/Challenges
			- [[Silent-Omniscient Adversaries]]
				- Prep: [||||||||||]
				- Cook Time: X min
				- Ingredients:
					1. 
			- [[Punishment Testing]] (Modulating Punishment/No Punishment Impacts to Conditions)
				- Prep: [||||||||||]
				- Cook Time: X min
				- Ingredients:
					1. 
			- [[Adding Multiplicative-min Punishment]]
				- Prep: [||||||||||]
				- Cook Time: X min
				- Ingredients:
					1. 
			- [[Reputation Attacks]]
				- Prep: [||||||||||]
				- Cook Time: X min
				- Ingredients:
					1. 
				- [[Con-Artist Attack]]
					- Prep: [||||||||||]
					- Cook Time: X min
					- Ingredients:
						1. 
				- [[The On-Off Attack]]
					- Prep: [||||||||||]
					- Cook Time: X min
					- Ingredients:
						1. 
			- [[Punishment Effects on Glacier]]
				- Prep: [||||||||||]
				- Cook Time: X min
				- Ingredients:
					1. 
			- [[Reputation Limitations]]
				- Prep: [||||||||||]
				- Cook Time: X min
				- Ingredients:
					1. 
				- No immediate defense against coordinated attacks
				- Reputation does not add to security
		- Future Work
			- [[Circumstantial Impact of Reputation on Consensus]]
				- Prep: [||||||||||]
				- Cook Time: X min
				- Ingredients:
					1. 
			- [[Long-running Simulation]]
				- Prep: [||||||||||]
				- Cook Time: X min
				- Ingredients:
					1. 
			- [[Sudden changes in Collective Byzantine Behavior]]
				- Prep: [||||||||||]
				- Cook Time: X min
				- Ingredients:
					1. 
			- Pending Questions
				1. Interaction of [[Stake-based]] and [[Reputation-based]] selection
					- Stake simulations are necessary for exploring options
					- Relevant in the incentives discussion?
				2. How much (and if) does reputation really help in a coordinated attack? (Assuming patient con-artist attack)
					- Complex interactions here, this model would particularly benefit having a prototype/PoC
- [[Node Challenges]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
	1. [[Intermittence Flexibility | Maintain Operation in High-Churn Network]]
	2. [[Sudden Changing Behavior]]
	3. [[Bootstrapping Quickly]]
	4. [[Resilience to Dynamic Unpredictable Network Changes (Can Handle Membership Volatility)]]
- [[Design]] 
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
	1. [[Local reputation view]]
	2. [[Adaptive and Dynamic]]
	3. [[Required Bootstrapping]]
		- [[Network View Not Required]]
		- [[Individual Node Reputation Not Required]]
- [[Eigentrust]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
	- [[Transitive Trust]]
	- [[Understanding the Math]]
	- [[Trust Decay]]
		- [[Malicious Clusters]] (describe nuances better, trusted nodes cannot overlap the malicious collective)
	- [[Trust for Consensus]]
	- [[Separation of Reputation]]
	- [[Confidant]]
	- [[XRep]]
	- [[P-Grid]]
	- [[R2Trust]]
- [[Generic Taxonomy]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
	- [[Dimensions]]
		- Single
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
- [[Node Discovery]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- [[Subnetworks]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
	- Design
	- Implementation
	- Ideas
- [[Mempool]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
	- Challenges
	- Approach
	- Mempool Design
	
#### Staking and Multi-DAG
- [[Factory of DAGs]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
	- Concept
	- Algorithm
- [[Sub-DAG]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- [[Cross-DAG]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- [[Bridge (Intermediary) Nodes]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- [[Gravity]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- [[Application-Level User-Driven]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- [[Direct Communication Channel]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- [[Direct Communication VGER]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- Challenges
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
	- [[Probabilistic Finality]] and [[Cross-Network Communication]]
	- [[Network Partitioning]] and [[Forks]]
	- [[Weak Subjectivity]] - Reputation of nodes matters to clients. Nodes are clients of other networks.
	- [[Verifying Weights in Staking]]
	- [[Glacier Algorithm Quiesces]]
- [[Approach]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
	1. [[Deterministic Finality]]
	2. [[Secondary Consensus Protocol]] (form local opinion on external DAG)
	3. [[Intermediary DAG]] (Intersection of nodes participating mutually in common structures)
- [[Vertex Sealing]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- [[XSub]] (Cross-sub-DAG communication)
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- [[XDAG]] (Cross-DAG communication)
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- [[XDAG Fees]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- [[Communication Patterns]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
	- Direct
	- User-Coordinated Channel
	- Sub-DAG-Coordinated Channel
- [[Stake Sub-DAG]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
	- [[Totally-Ordered Chain]]
	- [[Global Knowledge]]
	- [[Alternative Designs]]
		- [[2P-Set]]
		- [[Per-Node Branch]]
		
#### Data Model and Concurrency
- Reference Work
	- [[eUTXO]] (Direct extension of the basic UTXO model)
		- Prep: [||||||||||]
		- Cook Time: X min
		- Ingredients:
			1. 
		- References (Cardano foundational paper)
		- [[Validator]]
		- [[Datum]]
		- [[Redeemer]]
		- [[Ledger Description]]
	- [[CKB]]
		- Prep: [||||||||||]
		- Cook Time: X min
		- Ingredients:
			1. 
		- Key feature: [[state space ownership]]
		- [[Cell description]]
		- [[Transaction description]]
	- [[Zexe]]
		- Prep: [||||||||||]
		- Cook Time: X min
		- Ingredients:
			1. 
		- Key Feature: Privacy
		- Transaction Description
		- Record Description
- Approach
- [[Data Model Design]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
		- Challenges
		- Concept
		- Data Structures and Constraints
- [[Concurrent Execution (Threads)]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
			1. 
- [[Execution Patterns]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
	- Useful patterns
		- Example of [[EVM execution]] on this model
		- Explore and describe
	- [[Anti-patterns]]
		- High Contention
		- Low Affinity
		
#### Tokenomics
- [[Fees]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- [[Rewards]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- [[Slashing]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
- [[MEV]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients:
		1. 
