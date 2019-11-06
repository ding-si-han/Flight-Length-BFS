# Flight Path BFS Algorithm
Measuring the time taken for BFS Algorithm for:
1. Different number of cities in graphs (Vertices)
2. Different number of non-stop flights (Edges)

## Motivation
Plotting the shortest path for an airline to enable a passenger to fly from city A (Singapore) to city B (Florida).

## Usage
1. Finding how the number of cities in the network affect the time taken for BFS Algorithm: 
<pre><code> $ python numCities.py</code></pre>
2. Finding how the number of non-stop flights affect the time taken for BFS Algorithm
<pre><code> $ python numDirectFlights.py</code></pre>

## How it works
_graph.py_ contains Graph Class which has the stores the flights between cities in the dictionary _graph_dict_ and has the following methods:
 1. addEdge(self,node,neighbour)
 2. showEdges(self)
 3. BFS(self,start, destination)
 4. printParent(self, parentDictionary, start, destination)
 5. generateGraph(self, max, percentageCities)

 The Graph Class is instantiated as individual objects in _numCities.py_ and _numDirectFlights.py_