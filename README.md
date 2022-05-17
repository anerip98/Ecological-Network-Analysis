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


## Observations
The order of the network is 128. This measures the species richness of the community.

Water POC’ (node 122) has the highest betweenness centrality out of all the nodes. The second highest betweenness centrality is that of ’Benthic POC’ (node123). Both of these nodes belongs to the group ’Detritus’. Detrivores consume detritus and almost every organism gets converted into detritus. Therefore, due to highout-degree of these nodes their betweenness centrality ishigh.

Species with extreme values of eigenvector centrality can therefore be viewed as strong contributors to the stability or instability of a food web.
As ’Respiration’ is connected to all the living organisms,the out-degree is high and will be connected to importantnodes which leads to the highest eigenvector centrality.The second highest eigenvector centrality is that of ’WaterPOC’ (node 122). This measure shows a similarity withthe results of the betweenness centrality in this case. The 3rd highest value is that of the raptor species, followed by Avifauna as the 4th.

Similarly, ’Respiration’ has the highest closeness centrality of all the nodes. Therefore, respiration is the node which will influence the whole network the most rapidly. Almost every living organisms gets carbon through respiration so it has the highest closeness centrality.The second highest closeness centrality is that of ’WaterPOC’ (node 122). This measure shows a similarity withthe results of the betweenness and eigenvector centralities in this case.
The 3rd highest value is that of the Benthic node while the 4th highest closeness centrality is that of a living species and not a source of energy - the dolphin.

Interestingly, we don’t get a clear distinction between each group through community detection. Many groups are evenly distributed in all the communities. This phenomenon presumably indicates that the roles of these species in the carbon exchange cannot be derived fromthe traditional divisions in a trivial manner. For example,though both are mammals, the manatee and the dolphin have very diverse diets. The manatee feeds on submergent aquatic vegetation, and the dolphin feeds on small fishesand shrimps. Consequently, one would expect that themanatee and the dolphin play different roles in the carbon exchange.

## Contributors:
[Aneri Patel](https://github.com/anerip98)

[Sulay Shah](https://github.com/sulays)
