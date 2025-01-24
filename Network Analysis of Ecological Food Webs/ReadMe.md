## Network Analysis of Ecological Food Webs: Insights into Community Structure and Link Prediction ##

### Background: ###

Food webs in ecological networks often show how various complex interactions between species in the ecosystems occur. These networks often showcase interesting hierarchical community structures, where various types of living organisms form nested groups based on their feeding relationships and ecological roles in the system. Traditional methods of analyzing food webs such as special diversity metrics and Shannon diversity index have often focused on metrics such as species diversity, interconnectedness, and trophic levels. However, these approaches often fail to show the special hierarchical organization that emerges from species interactions such as food. This doesn’t account for how the food web impacts the roles of species and interaction between species. Recent advancements in network science, particularly in community detection algorithms and hierarchical clustering methods have provided newer tools to uncover and visualize these nested structures in ecological networks. Understanding these hierarchical patterns is very crucial in understanding and comprehending ecosystem dynamics, predicting responses to future disturbances, and creating new conservation strategies. I believe that we can utilize publicly available resources such as food web datasets from the Ecological Archives by ESA and the Web of Life database to get a better understanding of this. This provides data such as species composition lists, interaction matrices, biomass data, and stable isotope data as well as long term data sets and experimental manipulations that have been done in the past to get a better understanding of the food web and its impact on hierarchical structure in different ecosystems. This can help us get a better understanding of energy flow, nutrient cycling and keystone complexes.

### Methods: ###

### Datasets ###
The dataset that were used for analysis consists of 10 food web datasets. 

### Canadian Freshwater Systems: ###
Aishihik Lake
Cold Lake
Lake of the Woods
McGregor River
Parsnip River
Sbay Lake Huron
Smallwood Reservoir

### New Zealand Streams: ###
AkatoreA
AkatoreB
Venlaw

### Data preprocessing involved: ###
Converting adjacency matrices to edge lists
Removing duplicate edges
Handling missing values
Creating directed graph representations

### Network Analysis Methods ###

### Basic Network Metrics Calculation ###
Node count (species richness)
Edge count (interaction quantity)
Degree distribution
Mean degree
Clustering coefficient
Mean geodesic distance (MGD)

### Community Detection Implementation ###
Applied Louvain algorithm
Calculated modularity scores
Analyzed community size distributions

### Link Prediction Method ###
Implemented Common Neighbors algorithm
Calculated prediction scores
Identified top potential interactions

### Motif Analysis Methodology ###
Sampled network motifs (n=50)
Detected feed-forward loops (FFL)
Identified feedback loops (FBL)
Generated random network ensemble (n=50)
Calculated statistical significance

### Visualization Method ###
Spring Layout for to visualize the structure, communities, and key species for each ecosystem


## Full research data analysis report with data visualization: ##

https://docs.google.com/document/d/1ZAaVfjKG5D9kwNBHhAlbQW24dTXAiLBFOmr7M-6OqWw/edit?usp=sharing
https://docs.google.com/document/d/1OVIZ4DEjmYIK2I2BYOD_8RcJDll0PFD577aQgKuB2G4/edit?usp=sharing


