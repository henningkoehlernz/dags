# Directed Acyclic Graphs

A collection of sparse directed acyclic graphs.
Numbers of nodes and edges range from 10s of thousands to 10s of millions.

## File Format

Nodes are numbered consecutively in topological order, starting from 0.
The first line lists the number of nodes.
Subsequent lines start with a source node, followed by 1 or more target nodes.

### Example

The following describes a graph with nodes 0, 1, 2, 3, 4 and 5, and edges 0->1, 0->2, 0->4 and 3->4:

    6
    0 1 2 4
    3 4

## Origin

Graphs were collected from the following source:

* https://code.google.com/archive/p/grail/downloads
* https://snap.stanford.edu/data/
* https://bitbucket.org/jensdietrich/gigascale-pointsto-oopsla2015

Strongly connected components of the original graphs were contracted to eliminate cycles.
