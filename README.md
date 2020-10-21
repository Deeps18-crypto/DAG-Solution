# DAG-All-Possible-Paths

The following graph assume that all edges point downward

      0      6 .      4
      /  \ .  /
    1     2
    / \ . /
  3 .  5

It should generate the following paths
0->1->3
0->1->5 
0->2->5
6->2->5
4

Node - The node is also called as vertices.A vertex is a point where multiple lines meet

Edge - The edge is also called as links.The conection between two nodes is called as edge.In the given question we have 6 edge

Path - Path represents a sequence of edges between the two vertices

Steps to run the code:

-> To run the sample code, simple run the "DAGServiceTest"

-> To take user input, run "DAGService" and input the following 
      1. Total no. of nodes
      2. Total no. of edges
      3. For each edges, enter parent node and connected child node
      4. Run "DAGService"
