# General-Artificial-Intelligence
This provides a way to GAI

In order to achieve general intelligence, a new neural network architecture must be studied. I appreciate  Geoffrey Hinton's vision of the Capsule Network and the routing mechanism of the Capsule Network. Also I know about Yann LeCun's effort to develop Self-Supervised Learning. But I think that those structures are not closed to achieve the goal of human-level general intelligence.

A network that enables general intelligence must be:

1. Composed of basic units. Automatically enable different units for different tasks. You can smoothly add or remove units only by a small amount of local training.
1. There is no global loss function for optimizition, and the loss functions are distributed and localized around per unit.
1. There is no pre-set direction to pass information, unlike existing networks such as Cnn, Rnn, and Transformer in which the information flows from input nodes to output nodes with pre-fixed steps. The output should be transported outside in a General Interaction Channel(GIC), rather than from some specific nodes after pre-fixed steps of running.
1. The supervision of target output relies on reinforcement learning rather than optimization. It is reinforcement, rather than optimizition, that is global.
1. Have short-term and long-term memories, also have declarative memory. Memory should be stored to and extracted from where it is created, rather than collected in a particular place.
1. There are units' activities and interactions that are independent of the outside world. No matter whether there are inputs or not at that time, information generation, processing and refinement will be generated internally and continuously. 
2. Elements of the external real environment form representations within the system. These representations are spontaneously formed, as indicated by the formation of representations in a hidden layer of a deep network in supervised learning. An analog dynamic model of the external environment is formed inside the system. In the internal model, the representations are reasonably motivated to run each other as if the system were perceiving a real external environment.
1. Have a free will, which means having reasonable explanations before and after actions and those explanations should be complex enough to make them impossible to be derived from a fixed set of rules.

Therefore, I designed a new capsule unit structure and designed an example network system based on it, which matches all the needs listed above. The capsule unit structure is described in [consistent-distinguishable learning], and the network system is described in [micro-prediction capsule system].
