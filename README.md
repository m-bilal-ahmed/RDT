# Reliable Data Transfer Application
- Implemented RDT (Reliable Data Transfer) application in C++ using fundamental networking concepts such as TCP and UDP for transmitting data
  over a lossy channel with bit errors.
- Designed FSMs (Finite State Machines) for sender and receiver sides, utilizing unicast communication for point-to-point data transmission.
- Developed Network program as an emulator of a network, employing multicast to relay packets and acknowledgments between sender and receiver,
  emulating a lossy channel with random operations (PASS, CORRUPT, DROP) based on probabilities.
- Utilized unicast and multicast communication to support bidirectional data flow, allowing the receiver to send back ACKs to the Network, which are
  then relayed to the Sender for proper handling.
