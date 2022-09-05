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


## Running Tests

To run tests, run the following command

```
  clarinet test
```

### Unit tests

- Allows the contract owner to lock an amount.
- Does not allow anyone else to lock an amount.
- Cannot be locked more than once.
- Cannot set the unlock height to a value less than the current block height.
- Allows the beneficiary to bestow the right to claim to someone else.
- Does not allow anyone else to bestow the right to claim to someone else. (Not even the contract owner.)
- Allows the beneficiary to claim the balance when the block height is reached.
- Does not allow the beneficiary to claim the balance before the block-height is reached.
- Nobody but the beneficiary can claim the balance once the block height is reached.


## Project Source Code

The full source code of the project can be found here: 

https://github.com/clarity-lang/book/tree/main/projects/timelocked-wallet


