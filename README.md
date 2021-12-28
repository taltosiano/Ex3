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

## our Graph screenshot:


### How to load & run the gui
We load the graph with the "load" button. There are a variety of actions we can perform on the graph, each button performs another action. for example: if we click on the "addNode" button, a vertex will be added to the graph. If we click on the "theShortestDist" buttoמ we will see on the screen the answer to the shortest way from node to another.

## Performance analysis of our algorithms:

|   |  1000 | 10000  | 100000  |
| ------------ | ------------ | ------------ | ------------ |
|  isConnected |  72 ms |  265 |  3 sec 745 ms |
|  shortestpath |  99 ms |  287 ms |  5 sec 443 ms |
| load |   94 ms |  289 ms | 5 sec 538 ms  |
| save |   27 ms |  34 ms | 43 ms  |
| tsp |   100 ms |  285 ms | 5 sec 426 ms  |

## comparing to our code in Ex2

## our uml diagram:

![UML_Ex2](https://user-images.githubusercontent.com/94299489/146005679-d56cd273-0a1a-46e8-bc21-796432eee292.jpeg)
