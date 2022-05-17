# A Quantitative Characterization of Ecosystem Structure and Function of the South Florida Wetlands 

Ecological communities are best represented as networks. Knowledge of simple and complex interactions between species in an ecosystem is an additional layer of information that network measures exploit to quantify biodiversity. In this notebook, a food web network in the wetlands of South Florida has been analysed.
In this project, we 
    * attempt to understand the general structure of the food web network.
    * observe patterns by clustering similar nodes - detecting communities and motifs in the food web.
    * highlight important species in the ecosystem using various centralities.

## Data

Data

In food webs, species are the nodes and feeding interactions are the edges. The edges are directed flows of biomass and energy that occur when one species feeds on another.
The food web graph used for this analytical study is simple, unweighted, unipartite and directed. In this network, nodes are compartments (organisms and species or sources of energy in the foodweb) and edges represent energy flow (A directed edge from i to j means that carbon is transferred from i to j i.e. organism j eats organism i).

In addition, vertices are partitioned into different types as follows:
* Living/producing compartment
* Other compartment
* Input
* Output
* Respiration

Group classification labels (derived from ATLSS) are included with this network data. Example groups include"Zooplankton Microfauna" and "Pelagic Fishes".

## Contributors:
[Aneri Patel](https://github.com/anerip98)

[Sulay Shah](https://github.com/sulays)
