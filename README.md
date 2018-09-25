# AssureAttendance
Solidity smart-contracts to create events, hold deposit from attenders for registration and return deposit for attending.
Contract Addresss: 0x16905c9dcbe171a72f6cacfbab4925d27602992a

State Variables:
owner - contract creator
balance - keeps track of which address deposited how much

Functions:
deposit() - deposits ETH into the contract
giveBack() - gets back ETH that was deposited into the contract
selfDestruct() - destroys the contract (restricted to the owner)
