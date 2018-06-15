***********************************************************************************************************************************************************************
DAA PROJECT:                                   Our project is Longest simple weighted path in a directed acyclic graph
***********************************************************************************************************************************************************************
We Consider a Directed Acyclic Graph,Dag are those graph which has Directed edge's  and have no cycle( mean's there is no directed path from any vertex back to itself).
Initialize the  Source distance as 0 and for other vertex the distance will be Negative infini 
and then We one by one process all vertices in topological order. For every vertex being processed, 
we update distances of its adjacent using distance of current vertex.
Any Directed Acyclic Graph can be topological ordering also known as topological sort,
Topological Sort is a linear ordering of vertices such that,for every directed edge(u,v) ,
vertex u come's before v in the Odering.
We apply topological sort  because Topological Sorting Order depicts that the only vertices that can be visited after reaching that 
given vertex will come after that given vertex in the Topological Sorted Order and this is the requirement to solve this problem.
AFter Apllying topological Sort we will intialize the distance of source to "0" and then update the distance of vertex 
if distance of upcoming vertex is lessthen distance of starting vertex + weight of egde between them,then print the largest distance from source.


Time Complexity is O(V+E).
***********************************************************************************
GROUP MEMBERS:
AASHIR SHAHID  (15B-068-BS)
ARSALAN AKHTER (15B-009-BS)
MOHIB AHMED    (15B-001-BS)
************************************************************************************
                     HOW TO ACHEIVE  MEANING FULL OUTCOME
************************************************************************************ 
STEP 0:Run the given code on C++(gcc compiler). 
STEP 1:Consider a Simple Directed Acyclic Graph.
STEP 2:Enter the number of vertex you have in a DAG (vertex start from 0 so,you enter the verteces+1).
       //0 is A and so on..
STEP 3:Enter how many edge's do you have in DAG,For each edge from source to desitination(VERTEX) 
       enter the source ,destination and their edge weight.
STEP 4:Enter the Source from which you want to find the longest simple weighted path in  a Graph.