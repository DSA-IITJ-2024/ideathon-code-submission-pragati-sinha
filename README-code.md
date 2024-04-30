# **COMMUNITY DETECTION USING DIFFERENT ALGORITHMS**

A community is a group of nodes that are densely connected to each other and sparsely connected to the rest of the network. A streaming community  detection algorithm identifies communities from the stream of edges received.
This code uses the ***BITCOIN ALPHA TRUST WEIGHTED SIGNED NETWORK***. The dataset has 3783 nodes and 24186 edges. The code takes 7000 edges at first, and performs community detection on it using three algorithms-GIRVAN-NEWMAN,
LABEL PROPAGATION and MODULARITY method. The NMI score is calculated and the communities are plotted alongside the original graph. Then the number of edgeds taken is reduced by 1000 till we reach 1000 edges. After each reduction,
the same process of community detection is repeated. The time taken by each algorithm in each iteration is plotted.

## **CONTENTS** 
The folder will have the following components:

### The code file: 
The code file consists of the code that is to be run.

### The Report:
Consists of the procedure followed and the output of the code. 

### The ReadMe file:
Pre-requisite information about the assignment and necessary intel to run the provided code.

## **HOW TO RUN THE CODE**
Download the Bitcoin Alpha Trust Weighted Signed Network dataset [here](https://snap.stanford.edu/data/soc-sign-bitcoin-alpha.html).
Update the path in the code, and run all cells.

## **ALGORITHMS USED**
1. Girvan-Newman Algorithm
2. Label Propagation Algorithm
3. Modularity Community detection

## **PYTHON LIBRARIES USED**
1. networkx
2. matplotlib.pyplot
3. numpy
4. sklearn.metrics
5. random
6. csv
7. time

## **AUTHORS**
1. Pragati Sinha (B22MT048)
2. Shubham Kumar (B22CI038)
3. Palak Bhawsar (B22CH018)
