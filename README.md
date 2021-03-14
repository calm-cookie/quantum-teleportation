# Quantum Teleporation

_Implementation of Quantum Teleportation using Qiskit._

Quantum Teleporation is a way to communicate the state of an **unknown qubit** using a **classical channel** of communication. Since it uses a classical channel, the communication is **not** faster than light.

Let's say that ```Alice``` wants to send over a qubit to ```Bob```. 
- They must share an **entangled pair of qubits** for it to work. 
- Alice performs some operations on her qubit of the shared entangled pair and the unknown qubit to be teleported. 
- She measures these qubits and sends the **two bits of classical information** to Bob through a classical channel.
- The original qubit with Alice is **destroyed** in this process.
- Depending upon the information received, Bob performs some operations on his qubit of the shared entangled pair.
- **Finally Bob's qubit has the state of the original unknown qubit**.
