# qrng-hackathon

### Amol Yadav <amolyadav-inft@atharvacoe.ac.in>

### This was pretty easy to implement using qiskit, here are steps of implementation of how i did it

1. imports

modules i imported was qiskit, qiakit_aer and qiskit's visualization for priting quantum circuits

2. initializing the quantum circuit

i used the quantum and classical registers with n numbers for a quantum circuit.

3. simulating the circuit

for doing this quantum random number generator, we have to first use the aer simulator, and then we will apply the hadamard gate on all qubits for superposition which will make randomness accross the circuit. 

after applying this hadamard gate, i have measured the quantum circuit and collapsed its state. then i computed the result using `result()` function. after that i have counted the results for all the possible state from the outcomes. then from all counts, we take any result, in this i have taken 0 th index means the first bitstring state count as for the randomness, which is one of all possible outcomes.

Thats all, thanks for the oppoturnity!
