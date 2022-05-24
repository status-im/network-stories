---
dateUpdated: 2022-05-24
---

# Node Reputation
A list of [[Recipes]] necessary to develop better intuition and understanding

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
				- Verifiability (see Consensus)
				- Non-Repudiation (see Consensus)
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


