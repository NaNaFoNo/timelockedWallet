# Timelocked-Wallet

A Codeacademy Clarity Camp practice project. 

The block height can be used to perform actions over time. 
If you know the average block time, then you can calculate 
roughly how many blocks will be mined in a specific time frame. 
This project uses this concept to create a wallet contract that unlocks 
at a specific block height.

## Features

- A user can deploy the time-locked wallet contract.
- Then, the user specifies a block height at which the wallet unlocks and a beneficiary.
- Anyone, not just the contract deployer, can send tokens to the contract.
- The beneficiary can claim the tokens once the specified block height is reached.
- Additionally, the beneficiary can transfer the right to claim the wallet to a different principal. (For whatever reason.)