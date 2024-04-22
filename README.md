Abstract—Grover’s quantum search algorithm is one of the
well-known applications of quantum computing, enabling quan-
tum computers to perform a database search (unsorted array)
and quadratically outperform their classical counterparts in
terms of time. Despite the efficient database search for an Oracle
model (black box), researchers have shown several Grover circuit
implementations across various platforms. Nevertheless, Grover’s
search methods, including various Partial Grover searches, expe-
rience scaling problems as the number of iterations rises, making
implementation more computationally expensive. This paper
combines Partial Grover’s search algorithm and Bi-directional
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
on Github
