Phrase: Scalability

Related:

Operating Definition: 
With PBFT or Paxos-like consensus-like algorithms as you scale the number of validators the messages that need to be passed scales exponentially and that limits the number of validators close to around 100 or so because that message complexity gets too high. Bandwidth too high which affects how fast you can come to finality. As you increase the # of validators you increase the amount of work each validator has to do. This doesn't work for us, we want to keep the amount of work per individual as low as possible so we don't make it difficult for people to get access to available resources to be able to participate. We want to give more people the ability to participate within a network.

We want individual communties to be able to start with a low node count and eventually grow into a large node count. This may require the transition from a specific type of consensus mechanism into a different one or a combination of the two. A small network can join us and use our consensus infrastructure to start and grow off.

Current Implementation:

The Idea(l):

Logos Implementation: 

IMPORTANT Differentiators:

Trash Heap: