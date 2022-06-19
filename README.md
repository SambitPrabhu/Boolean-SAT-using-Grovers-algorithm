# Boolean-SAT-using-Grovers-algorithm
Boolean 5-SAT problem of 'Grover's dinner party' solved using Grover's algorithm in Qiskit.
Project associated with Quantum Computing Group, IIT Roorkee.

MOTIVATION:
Grover’s algorithm, also known as the quantum search algorithm, is a quantum algorithm designed by Los Grover in 1996 to search for an element in an unsorted array quadratically faster than the classical linear search for large datasets. In this project we will solve a particular boolean satisfiability problem using Grover's algorithm.

Boolean variables can take the values 'true' or 'false'. Given the constraints on the boolean variables, we can form a boolean output function, and if for some assigned values of the variables the function turns out to be true, then we say that the function is satisfiable. By solving a Boolean SAT problem, we want to determine all the input combinations into a boolean function such that the output is true. Since we will be searching through the combinations, this can be solved using Grover's algorithm.

PROBLEM STATEMENT:
Frank wants to throw a dinner party to celebrate Alice and Bob’s engagement. He is also considering inviting their mutual friends Charles, Dave and Eve. However, he is aware that Charles will come to the party only if Dave comes without Eve. Frank wants to know what possible combinations of invitations he can write for his friends Alice, Bob, Charles, Dave and Eve.
Help Frank calculate all the possible combinations using Grover’s algorithm.
