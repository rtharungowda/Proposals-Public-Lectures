## The Network Architecture Of Embryo Developmental Regulation

There are two basic forms of animal development: mosaic (characteristic of Nematodes and Tunicates) and regulative (characteristic of Amphibians and Mammals). How do each of these processes contribute to larger-scale developmental and embryogenetic processes? We employ a series of secondary datasets derived from microscopy of the embryo to answer this question. Using a five-dimensional spatial representation (_x,y,z,t,i_), where _t_ is depth in the lineage tree and _i_ is a cell’s unique location in a lineage tree organized by differentiation code (a binary code for differentiation asymmetry in lineage trees), systems-level features of the developmental process are revealed. To establish the relative role of deterministic mosaic mechanisms, we can map the cell division process of a lineage tree to a computational representation of _C. elegans_ embryogenesis from a directed, acyclic graph (DAG) to an undirected complex network. The deterministic influence of mosaic processes are identifiable by observing spatial/modular localization of progenitor and descendent cells. This topological compartmentalization should be consistent with dynamic processes in the developing embryo. Regulative development should demonstrate spatial “smearing”, or deviations from the compartmentalization of the mosaic process. In a complementary manner, stratification of the data by higher-level features such as division time or position in the lineage tree may provide support for precursors of tissue formation and other embryogenetic processes. Uncovering novel and otherwise interesting statistical relationships between cell lineage and physical space allows us to construct a scalable computational model of the cellular interactome in a model organism.

<p align="center">
  <img width="738" height="533" src="https://user-images.githubusercontent.com/19001437/54640397-ae685d80-4a5d-11e9-933b-be65928cbfd2.png"><BR>
  Figure 1: Description of how an embryo network is constructed. A: three-dimensional spatial representation of cell position centroids. B: two-dimensional lineage tree representation. C: spatial segregation in a 6-level lineage tree. D: circular graph for a 5-level lineage tree.
</p>
