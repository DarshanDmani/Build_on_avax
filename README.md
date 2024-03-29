# FruitToken Contract

## Description

This Solidity smart contract, named FruitToken, enables users to interact with a token system where they can mint, burn, transfer tokens, and redeem fruits using those tokens. The contract is implemented with the ERC20 standard for the token functionality and includes the Ownable contract for ownership management.

## Features

- **Token Minting:** The owner of the contract can mint new tokens and assign them to specific addresses.
- **Token Burning:** Users can burn their own tokens, effectively reducing the total supply.
- **Fruit Redemption:** Users can exchange their tokens for different types of fruits: dry fruits, fresh fruits, and ripened fruits.
- **Token Transfer:** Users can transfer their tokens to other addresses.

## Events

- **FruitRedeemed:** Triggered when a user redeems a fruit, indicating the user, the type of fruit redeemed, and the cost in tokens.
- **TokensMinted:** Fired when tokens are minted, specifying the beneficiary and the amount minted.
- **TokensBurned:** Indicates when tokens are burned, mentioning the burner and the amount burned.
- **TokensTransferred:** Signals when tokens are transferred between addresses, providing information on the sender, recipient, and the amount transferred.

## Functions

- **mintTokens:** Allows the contract owner to mint new tokens and assign them to a specific address.
- **burnTokens:** Enables users to burn a certain amount of their own tokens, reducing their balance.
- **redeemFruit:** Allows users to redeem a fruit by spending tokens, updating their selected fruit and deducting the appropriate token amount.
- **transferTokens:** Lets users transfer tokens to another address.

## Enums and Mappings

- **Fruit Enum:** Defines the different types of fruits available for redemption.
- **Mapping (userSelectedFruits):** Maps user addresses to their selected fruit.
- **Mapping (fruitCosts):** Maps each fruit type to its respective token cost.

## Initial Setup

- The contract constructor requires an initial owner address to set up the contract.
- The `initializeFruitCosts` function sets initial costs for each type of fruit.

## How to use?

- Deploy the contract, providing an initial owner address.
- Interact with the contract using the provided functions to mint, burn, transfer tokens, and redeem fruits.

## License

This contract is licensed under the MIT License.

## SPDX-License-Identifier

SPDX-License-Identifier: MIT

## Author 

dharshan98760@gmail.com

darshan 
