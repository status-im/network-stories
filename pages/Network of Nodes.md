---
dateUpdated: 2022-05-24
---

# Network of Nodes

## The Waku Network  
Typical Network Topology

![Typical Network Topology](https://i.imgur.com/MTcNKTt.png)

```
Note:
Let’s take a look at what a network of Waku nodes might look like.  
It may be too intricate for a clear understanding on first glance, but we’ll look into each feature in detail next.  
For now it’s important to have a high-level understanding of what each element represents:
```
-   the shaded circles represent [[Waku Nodes]] contributing at different levels to the network
-   the shading itself represents that node’s capabilities/resource availability (we’ll look at this concept next)
-   the colored, dotted lines represent different pubsub topics. Remember that a specific contribution always belongs to a specific pubsub topic, hence the separate pubsub topics represent separate sub-networks.
-   the solid arrows represent some request/response protocols, such as `store`, `filter`, or `lightpush`
-   the dotted boxes show what content topics (i.e. applications) a node is interested in. A node that is purely providing a service to the network might not care.
-   there are also dashed lines to “auxiliary networks”. These represents breakouts from the Waku network to auxiliary protocols, such as bridging to Waku v1, DNS used for discovery, etc.


- Recipe: Topic
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients: 
		1. [Insert pictures, videos, article links, research papers, etc.]
