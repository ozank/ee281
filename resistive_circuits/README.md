# Nodes, Branches and Loops

**Node** is the point of connection between elements. Elements connected to the same nodes have the same voltage.

**Branch: ** is the connection between two nodes. The elements in the same branch carry the same current.

**Loop** is the closed loops in the circuit diagram.

A network with **b** branches, **n** nodes, and **l** independent loops will satisfy the fundamental theorem of network topology:

$$b = l + n − 1$$

**Series Connection:** Two or more elements are in series if they are connected sequentially and consequently carry the same current.

**Parallel Connection:** Two or more elements are in parallel if they are connected to the same two nodes and consequently have the same voltage across them.

# Kirchhoff's Current Law

**Algebraic sum of currents entering a closed loop (or a node) is zero.**
$$\sum I_n =0$$

![](http://www.electronics-tutorials.ws/dccircuits/dcp6.gif)

Don't forget to use plus sign for current entering into node and negative sign for currents leaving the node if just the magnitudes are given.

$$I_1+I_2+I_3-I_4-I_5 = 0$$

# Kirchhoff's Voltage Law

**Algebraic sum of all voltages around a closed path (or loop) is zero.**

$$\sum V_n =0$$

![](http://www.csupomona.edu/~elab/projects/project_02/images/kirchhoff3.gif)

If you meet with negative terminal of an element first, write that voltage as negative to the equation.

$$-12 V  + V_1 +V_2 -6 +V_3+V_4 =0 $$
