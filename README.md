# Automatic-test-Pattern-Generator-using-PODEM

ATPG is an Automatic Test Pattern Generator whose primary goal is to generate the test vectors that help detect and diagnose faults in the circuit.
The three major steps in the generation of test patterns or stuck at fault are:<br />
Fault sensitization/Activation: generate a distinguishable value at the fault site by applying value to PI.<br />
Line Justification(LJ): Apply primary inputs to sensitize the fault.<br />
Fault Propagation: Once the fault is activated, we will propagate it to one of the primary outputs<br />
<br />
• Implemented PODEM-based heuristic algorithm in Python to generate the stuck-at-fault test vectors <br />
• Executed backtracking algorithm and stack decision table to store the used values of primary inputs <br />
• Used D-frontier approach for fault propagation and path tracing for assigning value to the primary inputs
