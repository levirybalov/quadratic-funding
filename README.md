# quadratic-funding

SBT_v2 is an implementation of the equations at the end of "Adjusting Quadratic Mechanisms for Pre-Existing Cooperation" of the paper "Decentralized Society: Finding Web3’s Soul" by E. Glen Weyl, Puja Ohlhaver, and Vitalik Buterin.

SBT_simulation is a synthetic construction of contributions and affiliations of a set of agents, and a simulation of one of the matching algorithms on this dataset, before and after setting one agent’s voice to copy that of another (total coordination). There is a lot more that can be simulated, this is just a simple example.

SBT_real_data takes the file “hackathon-contributions-dataset_v2.csv” and forms a matrix of ids by projects, with each cell indicating the amount that each id contributed to each project. The idea is to use this real-world data to inform the simulations. 

SBT_connection_oriented_cluster_match implements the connection-oriented cluster match from "Beyond Collusion Resistance: Leveraging Social Information for Plural Funding and Voting" by Joel Miller, E. Glen Weyl, and Leon Erichsen.
