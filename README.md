# all-pairs-shortest-paths
CUDA implementation of the Floyd-Warshall algorithm


ECL-APSP is an all-pairs-shortest-paths CUDA implementation of the Floyd-Warshall algorithm. As far as we know, it is faster than the fastest such codes from the literature. It operates on graphs stored in binary CSR format.

The CUDA code can be compiled as follows:
'''
nvcc -O3 -arch=sm_35 ECL-APSP_10.cu -o ecl-apsp
'''

To compute the APSP of the file graph.egr, enter:
'''
./ecl-apsp graph.egr
'''
This work has been supported in part by the National Science Foundation under Grant No. 1955367 as well as by equipment donations from NVIDIA Corporation.
