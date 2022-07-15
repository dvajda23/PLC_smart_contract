# PLC_smart_contract
Expanding Abilities of PLC by Use of External Software

Programmable logic controllers are pretty limited in terms of their calculating abilities. If we would like to use advanced calculating / decision in our PLC program 
we would need to make a very advanced algorithm in LADDER logic.

This results in high complexity of our programs, which is not user friendly, since PLC programs need to be simple and easy to understand in order to modify them on the fly. A possible solution for this is expanding abilities of PLC by use of external software. In this final thesis I've expanded PLC's abilities with blockchain technology. 

Advanced calculationg algorithm is programmed in a smart contract. Smart contract is deployed on Rinkeby testnet using Raspberry Pi. PLC communicates with RPi using MODBUS TCP connection protocol. Use of this expansion will be demonstrated on a practical example of a smart warehouse unit. Solving this problem would be very complex in ladder logic, but using a smart contract it's fairly simple. 

State of each sensor is sent to RPi, and then an algorithm calculated

