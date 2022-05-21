# Set of Implementations

## Waku v2 builds on `libp2p`,  
a modular peer-to-peer network stack.

```
Note:  
Often when people encounter Waku v2 for the first time, the relationship with `libp2p` is not immediately clear.  
Waku v2 protocols build on the p2p network stack provided by `libp2p` and adds some functionality to it.  
Waku v1 and Whisper were built on `devp2p`.  
`libp2p` is basically “devp2p done right”.  
For example, there are some [fundamental issues with encryption](https://github.com/ethereum/devp2p/blob/master/rlpx.md#known-issues-in-the-current-version) in `devp2p` and, although things like ETH1 is currently running on it, no one else is really building on `devp2p`.  
`libp2p` was developed for IPFS but now many projects use it, Ethereum 2 included. It is therefore quite mature, with many implementations and a large part of the crypto/p2p community behind it. While it’s not perfect, it’s very modular and easy to extend with new transports, user-defined protocols, etc.
```

## **How-To (Get Cookin')**
*Instructions: There are some descriptions below which detail the usage of visual guidance metrics available in the form of "cookbook-like" instructions for how to consume this document:*

|  Gauges  |     Description    | Visualization |
| -------- | :-----------: |  :----------:  |
|Difficulty| 1-10 (Ticks/Pips) |  [&#124;&#124;&#124;&#124;&#124;&#124;&#124;&#124;&#124;&#124;]  | 
|Time      | In Minutes | X Minutes |
|Resources | Article/Video Links w/ Visual Content | Conceptual & Pictoral "Ingredients List" of Links|

### **Gauge Definitions:**

Prep (*Difficulty*) is defined as the ease of which the concepts can be generally understood. (Future: Make into more fun visual or something more enjoyable than a difficulty bar.)

Cook Time (*Scope*) is in reference to the size of information necessary to learn to gain a decent level of comprehension.

Ingredients (*Resources*) is for links relevant to helping people understand the concepts. Number references and use superscript notation to reference mentions in terminology Recipes descriptions.


	![[Pasted image 20220415164934.png]]

- Recipe: [[nim-waku]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients: 
		1. [Insert pictures, videos, article links, research papers, etc.]
- Recipe: [[js-waku]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients: 
		1. [Insert pictures, videos, article links, research papers, etc.]
- Recipe: [[go-waku]]
	- Prep: [||||||||||]
	- Cook Time: X min
	- Ingredients: 
		1. [Insert pictures, videos, article links, research papers, etc.]