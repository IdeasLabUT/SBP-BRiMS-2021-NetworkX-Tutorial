# Analyzing Network Data in Python using NetworkX and DyNetworkX
SBP-BRiMS 2021 Tutorial
Tanner Hilsabeck, Hung Do, and Kevin S. Xu (University of Toledo)

Tuesday, July 6 3:00-5:30pm Eastern time

## Brief Description

Networks are all around us in many forms, ranging from online social networks to public transportation networks to gene networks in biology. Analyzing network representations of complex systems can reveal many insights about how they are organized. This tutorial introduces methods for analyzing network data using Python. It will be divided into 2 parts.

In part 1, we begin by discussing a variety of measures of network structure, including measures of centrality, transitivity, path lengths, and homophily. We also introduce several common analysis tasks involving networks, including community detection and link prediction. We then demonstrate how to compute these measures and perform these analysis tasks in Python using the well-known NetworkX package . We conclude this part with a case study on real social network data.

In part 2, we transition to dynamic or temporal networks, where the structure of the network changes over time. We first introduce different representations of dynamic networks ranging from the discrete-time snapshot or panel data representation to the continuous-time relational event representation. We then discuss several different approaches to analyzing dynamic network data ranging from applying static network measures snapshot by snapshot to identifying temporal motifs. We demonstrate how to conduct such analyses using functionality built into NetworkX and DyNetworkX . We then conclude with a second case study on a real dynamic social network.

## Tutorial Materials

[Tutorial slides (PDF)](Slides.pdf)

### Demos

There will be four demos in this tutorial:

1. Centrality analysis on Zachary's Karate Club network using NetworkX
2. Link prediction on Zachary's Karate Club network using NetworkX
3. Dynamic betweenness centrality analysis on Enron email network using DyNetworkX
4. Temporal motif analysis on Militarized Interstate Disputes incident network using DyNetworkX

