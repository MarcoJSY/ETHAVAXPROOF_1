# ETHAVAXPROOF_1

This Ethereum smart contract is designed to demonstrate the use of `require()`, `assert()`, and `revert()` statements. The contract allows users to deposit, transfer, and withdraw funds.

## Contract Details

- **Contract Address:** `<Your Deployed Contract Address>`
- **Owner Address:** `<Owner's Ethereum Address>`
- **Initial Value:** `0`

## Functions

### `deposit(uint256 amount)`

Allows users to deposit a specified amount of funds into their account.

#### Parameters

- `amount`: The amount to deposit.

#### Conditions

- Requires the deposited amount to be greater than zero.

### `transfer(address recipient, uint256 amount)`

