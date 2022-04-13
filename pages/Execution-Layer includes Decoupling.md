Phrase: Execution Layer Decoupling

Related:

Operating Definition: Concept of a Layer-0 or agreements layer, a network of nodes that come to agreement on arbitrary data and nothing else. From there you can bolt on different execution methods. 
When you think of Nakamoto Consensus, the process of coming to agreement (PoW) is tied inexorably to the type of data you are coming into agreement upon. You have to put together that block with all of the transactions and hash that header with nonces so you are tied to the data you are coming into agreement upon which will give you a fundamental bottleneck on how much data you can process at any given time. This is why you have a block time in PoW.

We would like to separate these two things so any two nodes can come into agreement upon any piece of data which gives us a lot of freedom wrt what type of data we are coming into agreement upon and how much data we can process at any given time.

Current Implementation:

The Idea(l):

Logos Implementation: 

IMPORTANT Differentiators:

Trash Heap: