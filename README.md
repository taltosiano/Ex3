# Ex3

## Authors
**Tal tosiano-208846600**  
**Moran shalev-316220938**


## our project 

+ The project contains the Dijkstra's algorithm who uses to find the shortest path in a weighted graph.

### Design and implement two main interfaces:

+ Interface of a weighted directed graph

+ Interface of algorithms on graphs (weighted tuners).
        
## The process of creating the project:
We built a system that builds a weighted graph by the classes:

### Node
represents the set of operations applicable on a  node (vertex) in a (directional)     
 weighted graph.
Every node has data (id-key,location,weight,info,tag) that helps us to representing the graph         in In the most accurate way. 

### Edge
represents the set of operations applicable on a directional  edge(src,dest,weight)  in a (directional) weighted graph.

### DiGraph
represents a Directional Weighted Graph with all his elements(Nodes,Edeges)and   including many functions that updates his elements.

### GraphAlgo
represents a Directed (positive) Weighted Graph Theory Algorithms and including many algorithms.
for the tsp function (Travelling salesman problem) we use the "tarjan" algoritem to solve  this problem.
for the shortestPathDist function we use the dijkstra's algorithm to solve this problem.

## Performance analysis of our algorithms and comparing to our code in Ex2:

# Ex3
|   |  1000 | 10000  | 100000  |
| ------------ | ------------ | ------------ | ------------ |
|  isConnected |  72 ms |  265 |  3 sec 745 ms |
|  shortestpath |  99 ms |  287 ms |  5 sec 443 ms |
| load |   94 ms |  289 ms | 5 sec 538 ms  |
| save |   27 ms |  34 ms | 43 ms  |
| tsp |   100 ms |  285 ms | 5 sec 426 ms  |

# Ex2
|   |  1000 | 10000  | 100000  |
| ------------ | ------------ | ------------ | ------------ |
|  isConnected |  72 ms |  265 |  3 sec 745 ms |
|  shortestpath |  99 ms |  287 ms |  5 sec 443 ms |
| load |   94 ms |  289 ms | 5 sec 538 ms  |
| save |   27 ms |  34 ms | 43 ms  |
| tsp |   100 ms |  285 ms | 5 sec 426 ms  |

## our graph screenshot:

## our uml diagram:
