### Description

Each folder contains files for one dataset.
* `*_graph.txt` file contains the list of edges, and additional information (e.g., edge time)
* `dblp_t_label.npy` file contains node labels for each time step in a numpy array of the following shape: (# time steps, # nodes, # classes).

### Acknowledgements

These files were collected from the following sources and postprocessed into the current format.
* https://sites.google.com/site/yangdingqi/home/foursquare-dataset
* https://github.com/yh-yao/InterpretableClustering