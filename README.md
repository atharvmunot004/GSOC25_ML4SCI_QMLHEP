# Quantum Kolmogorov-Arnold Networks for High Energy Physics Analysis at the LHC

Project Idea Description: [Proposal_QMLHEP10](https://ml4sci.org/gsoc/2025/proposal_QMLHEP10.html)

Test Tasks link: [Test Tasks](https://docs.google.com/document/d/1imoMEyC0r5IESonwgA7BThEQWDfdrOsoyfMfyJgyXmU/edit?usp=sharing)

<hr>
<hr>

# Tasks for QMLHEP10

## Task I: Quantum Computing Part 
### 1. Implement a simple quantum operation with Cirq or Pennylane
<ol> 
    <li> With 5 qubits 
    <li> Apply Hadamard operation on every qubit 
    <li> Apply CNOT operation on (0, 1), (1,2), (2,3), (3,4) 
    <li> SWAP (0, 4) 
    <li> Rotate X with pi/2 on any qubit 
    <li> Plot the circuit 
</ol>
<hr>

### 2. Implement a second circuit with a framework of your choice:
<ol>
    <li> Apply a Hadmard gate to the first qubit
    <li> Rotate the second qubit by pi/3 around X
    <li> Apply Hadamard gate to the third and fourth qubit
    <li> Perform a swap test between the states of the first and second qubit |q1 q2> and the third and fourth qubit |q3 q4>
</ol>
<hr>

## Task II: Classical Graph Neural Network (GNN) 
### For Task II, you will use ParticleNet’s data for Quark/Gluon jet classification available [here](https://zenodo.org/records/3164691#.YigdGt9MHrB) with its corresponding description. 
<ul>
    <li> Choose 2 Graph-based architectures of your choice to classify jets as being quarks or gluons. Provide a description on what considerations you have taken to project this point-cloud dataset to a set of interconnected nodes and edges.
    <li> Discuss the resulting performance of the 2 chosen architectures. 
</ul>
<hr>

## Task III: Open Task 
Please comment on quantum computing or quantum machine learning. You can also comment on one quantum algorithm or one quantum software you are familiar with. You can also suggest methods you think are good and you would like to work on. Please use your own understanding. Comments copied from the internet will not be considered.
<hr>

## Task IX: Kolmogorov-Arnold Network
Implement a classical Kolmogorov-Arnold Network using basis-splines or some other KAN architecture and apply it to MNIST. Show its performance on the test data. Comment on potential ideas to extend this classical KAN architecture to a quantum KAN and sketch out the architecture in detail.
