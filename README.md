# operating-system
The banker’s algorithm is a resource allocation and deadlock avoidance algorithm that tests for safety by simulating the allocation for predetermined maximum possible amounts of all resources, then makes an “s-state” check to test for possible activities, before deciding whether allocation should be allowed to continue. 
Let ‘n’ be the number of processes in the system and ‘m’ be the number of resources types. 
    Available :  
•	It is a 1-d array of size ‘m’ indicating the number of available resources of each type. 
•	Available[ i ] = k means there are ‘k’ instances of resource type Rj     Max : 
•	It is a 2-d array of size ‘n*m’ that defines the maximum demand of each process in a system. 
•	Max[ i, j ] = k means process Pi may request at most ‘k’ instances of resource type Rj.     Allocation : 
•	It is a 2-d array of size ‘n*m’ that defines the number of resources of each type currently allocated to each process. 
•	Allocation[ i, j ] = k means process Pis is currently allocated ‘k’ instances of resource type Rj     Need : 
