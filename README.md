# IBM-Quantum-Lab-Grover
Grover’s algorithm example
------
![grover-circ](https://user-images.githubusercontent.com/13979489/201800648-0866b557-f942-47e9-a99f-6f15959f13f5.png)


Perhaps even stranger than Bell states are their three-qubit generalization, the GHZ states. An example of a GHZ state

GHZ states are named after Greenberger, Horne, and Zeilinger, who were the first to study them in 1989. GHZ states are also known as “Schrödinger cat states” or just “cat states.”

## W states vs. GHZ states

How else can three qubits be entangled? W states are another way to entangle three qubits, with an important difference from GHZ states: W states are more robustly entangled when a qubit is lost. Let’s look at what that means.

The residual entanglement is useful. For example, we can use it to successfully teleport a qubit two-thirds of the time. Consider the following circuit:

![w-measure2](https://user-images.githubusercontent.com/13979489/201800794-5602792f-600a-4f53-86af-d23420324919.png)
