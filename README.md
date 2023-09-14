# openflights-airport-network-analysis

Airport network analysis made with Python, Pandas and igraph

Dataset provided by: https://networks.skewed.de/net/openflights

The main scope of this analysis is to study the ‘openflights’ dataset properties using a graph-oriented approach. Specifically, the analysis aims to:
•	Find airport network properties and characteristics;
•	Find the presence of major hub airports using centrality measures such as betweenness, node degrees and page rank; 
•	Study the network efficiency using previous results;
•	Study the assortativity of the network.

The dataset is available in csv format, it contains both nodes and edges data, respectively representing airports and flights data. The distance column has been used as weight for each edge, since it is a relevant information useful in this context. 
The analysis has been conducted in Python language with the help of igraph library, since many useful methods are already implemented, but few personalized methods have been developed as well. 
