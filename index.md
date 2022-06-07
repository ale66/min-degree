## The Min-Degree Heuristics

Min-Degree (MD) is a Heuristics for computing cover-time-like problems in undirected networks.

The following abstract is from our latest submission.

*We consider information diffusion on Web-like networks and how random walks can simulate it. 
A well-studied problem in this domain is Partial Cover Time, i.e., the calculation of the expected number of steps a random walker needs to visit a given small number of the nodes of the network.
We notice that some of the fastest solutions in fact require that nodes have perfect knowledge of the degree distribution of their neighbours, which in many practical cases is not obtainable, e.g., for privacy reasons.  
We thus introduce a version of the Cover problem that considers such limitations: Partial Cover Time with Budget. 
The budget is a limit on the number of neighbours that can be inspected for their degree; we have adapted optimal random walks strategies from the literature to operate under such budget. 
Our solution is called Min-degree (MD) and, essentially, it biases random walkers towards visiting peripheral areas of the network first. 
Extensive benchmarking on six real datasets proves---perhaps counter-intuitively--- that our MD strategy is in fact highly competitive wrt. well-known  algorithms such as Edge-Process, All-Degrees and Random Walks with Choice.*

## The Min-Degree with budget Heuristics

Min-Degree with budget (MD(B)) is a Heuristics for computing partial-cover-time when access to neighboring nodes is restricted. The *budget* B is the number of neighbors we can access each time.






