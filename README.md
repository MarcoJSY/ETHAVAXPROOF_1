# ETHAVAX1 SMART CONTRACT PROJECT - FUNCTIONS AND ERRORS

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

Allows users to transfer funds to another Ethereum address.

#### Parameters

- `recipient`: The Ethereum address of the recipient.
- `amount`: The amount to transfer.

#### Conditions

- Requires the sender's balance to be sufficient for the transfer.

### `withdraw(uint256 amount)`

Allows users to withdraw a specified amount of funds from their account.

#### Parameters

- `amount`: The amount to withdraw.

#### Conditions

- Checks if the user has a sufficient balance for withdrawal. If not, reverts the transaction.

## Getting Started

1. Copy and Paste the ETHAVAX1.sol source code to Remix (remix.ethereum.org).
2. Use the appropriate compiler (I used version 0.8.18)
3. Click compile ETHAVAX1.sol, then go to deploy & run transactions tab.
4. Choose the name of the project in the dropdown of the Contract, then click deploy.
5. Under the deployed contracts choose name of the deployed project. 
7. Interact with the different functions of the contract (check Functions or Usage).

## Usage

1. Deposit funds using the `deposit` function.
2. Transfer funds to another address using the `transfer` function.
3. Withdraw funds using the `withdraw` function.

## Disclaimer

This smart contract is for educational purposes only. Use it at your own risk. The contract may have security vulnerabilities, and it is not recommended for deployment on the mainnet without proper auditing. This smart contract was designed to only demonstrate the use of `require()`, `assert()`, and `revert()` statements.

## Author

  - Mendizabal, Jed Marco
    - GitHub: @MarcoJSY

## License

This smart contract is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
