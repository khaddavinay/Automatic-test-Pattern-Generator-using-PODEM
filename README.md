# Automatic-test-Pattern-Generator-using-PODEM

ATPG is an Automatic Test Pattern Generator whose primary goal is to generate the test vectors that help detect and diagnose faults in the circuit.
The three major steps in the generation of test patterns or stuck at fault are:\\
Fault sensitization/Activation: generate a distinguishable value at the fault site by applying value to PI.\\
Line Justification(LJ): Apply primary inputs to sensitize the fault.\\
Fault Propagation: Once the fault is activated, we will propagate it to one of the primary outputs\\

• Implemented PODEM-based heuristic algorithm in Python to generate the stuck-at-fault test vectors 
• Executed backtracking algorithm and stack decision table to store the used values of primary inputs 
• Used D-frontier approach for fault propagation and path tracing for assigning value to the primary inputs
