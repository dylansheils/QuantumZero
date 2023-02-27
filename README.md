# QuantumZero
Expanding Tensor Network Contraction Heuristics

At the moment, the problem of generating a tensor network associated with a quantum circuit is solved and the problem of designing a model is solved. 
The current plan is to generate a dataset of input tensor network + the CuQuantum and Exact contraction trajectories with the end associated cost. 
The current architecture is a fairly simple recursive Graphformer with residual connections. A maximum of the highest associated probability will be taken 
when generating a contraction sequence.
