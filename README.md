This paper combines Partial Grover’s search algorithm and Bi-directional
Search to create a fast Grover’s quantum search algorithm,
referred to as Bi-Directional Grover Search (BDGS). We in-
corporated a Bi-directional search tactic with Partial Grover
Search starting from an initial state and a single marked state
in parallel. Our novel approach requires π/(4√2)*(√N − √N/(b^r/2 ))
iterations and archives an O(√N/2) average complexity over
regular Grover Search and partial Grover Search, which take
O(√N) (here, N = 2r elements and b is the branching factor of
partial search). The proposed BDGS algorithm is benchmarked
against the state-of-the-art Depth-First Grover’s Search (DFGS)
and generic Grover’s Search (GS) implementations for 2 to 20
qubits and provides an optimal solution. The Qiskit Python
implementation of the proposed BDGS algorithm is available
here in this repository.
