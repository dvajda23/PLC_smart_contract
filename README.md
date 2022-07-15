# Expanding Abilities of PLC by Use of External Software 

### About: David Vajda's final thesis, University of Ljubljana, Faculty of Mechanical Engineering
## Introduction
Programmable logic controllers are pretty limited in terms of their calculating abilities. If we would like to use advanced calculating / decision in our PLC program 
we would need to make a very advanced algorithm in LADDER logic.

## Basic idea
This results in high complexity of our programs, which is not user friendly, since PLC programs need to be simple and easy to understand in order to modify them on the fly. A possible solution for this is expanding abilities of PLC by use of external software. In this final thesis I've expanded PLC's abilities with blockchain technology. 

## How it works
Advanced calculationg algorithm is programmed in a smart contract. Smart contract is deployed on Rinkeby testnet using Raspberry Pi. PLC communicates with RPi using MODBUS TCP connection protocol. Use of this expansion will be demonstrated on a practical example of a smart warehouse unit. Solving this problem would be very complex in ladder logic, but using a smart contract it's fairly simple. 

Smart storage unit consists of 4 column. Each column's maximum height is 4 parcels. Height of each column is calculated using sensor outputs.

  ![senzorji_skladisce](https://user-images.githubusercontent.com/109219325/179218252-c12727f7-a58d-46c1-b53d-b9a0bba022cb.png)

State of each sensor is sent to RPi using MODBUS. Using function inputs defined in the smart contract user defines which parcel they would like to access. Then an algorithm calculates the optimal way to distribute other parcels in order to gain access to the chosen one.

This thesis is a direct results of my own experiments and testing under supervision and mentorship of Prof. Dr. Janez Diaci and Asist. Dr. Marko Corn.

