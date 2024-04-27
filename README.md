# VQNE
VQNE: Variational Quantum Network Embedding with Application to Network Alignment

This notebook implements the two algorithms of the VQNE paradigm.
To run the notebook (on Linux, not Windows, as at least one supporting package for the TorchQuantum library is not available on Windows),
1. clone the repository to your local directory;
2. change the path of the _gistfile1.txt_ to the _path_to_gistfile1.txt_ in your local directory;
3. change the path of the code directory to the _path_to_Code_ in your local directory;
4. for the d2w dataset, use
    - `data = 'd2w'`
    - `source_edge_file = 'wb-net.txt'`
    - `target_edge_file = 'db-net.txt'`
    - `percentage = 10, 20, 30, 40 or 50`
5. for the f2b dataset, use
    - `data = 'f2b'`
    - `source_edge_file = 'fb-net.txt'`
    - `target_edge_file = 'tt-net.txt'`
    - `percentage = 10, 20, 30, 40 or 50`
6. run all the cells except the first one;
7. if you run the notebook on Google Colab, you may optionally mount your Google Drive by running the first cell to access the gistfile1.txt and the datasets, as well as saving the output to Google Drive.

# References
- [VQNE: Variational Quantum Network Embedding with Application to Network Alignment](https://dl.acm.org/doi/10.1145/3580305.3599542)
- [ASNets: A Benchmark Dataset of Aligned Social Networks for Cross-Platform User Modeling](https://dl.acm.org/doi/10.1145/2983323.2983864)
- [RED: Learning the role embedding in networks via Discrete-timequantum walk](https://link.springer.com/article/10.1007/s10489-021-02342-1)

# Acknowledgments
- We reference the code from https://github.com/Dywangxin/RED_experiments for discrete-time quantum walk.
