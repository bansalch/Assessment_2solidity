# Assessment_2solidity
My second metacrafters assessment!!!
# MyToken Smart Contract

This Ethereum smart contract implements a basic ERC-20 token with minting and burning functionalities.

## Contract Details

- *Token Name*: Dogecoin
- *Token Abbreviation*: DOGE
- *Total Supply*: Tracks the total number of tokens.

## Features

- *Public Variables*:
  - tokenName: Name of the token.
  - tokenAbbrv: Abbreviation.
  - totalSupply: Total token count.

- *Balances Mapping*:
  - Maps addresses to balances.

- *Mint Function*:
  - Mints tokens to a specified address.
  - *Parameters*:
    - _add: Address to mint tokens to.
    - _value: Number of tokens to mint.
  - *Effects*:
    - Increases totalSupply and the address balance.

- *Burn Function*:
  - Burns tokens from a specified address.
  - *Parameters*:
    - _add: Address to burn tokens from.
    - _value: Number of tokens to burn.
  - *Effects*:
    - Decreases totalSupply and the address balance.
  - *Requirement*:
    - The address balance must be greater than or equal to _value.

## Requirements

- Solidity version: ^0.8.0
- SPDX-License-Identifier: MIT

## License

This project is licensed under the MIT License.
