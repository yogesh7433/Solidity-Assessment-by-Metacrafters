MyToken Smart Contract

Overview
MyToken is a simple ERC-20-like token implemented in Solidity. The token is named "YogeshRajput" with the abbreviation "YR". This smart contract allows for minting and burning tokens, effectively managing the total supply and balances of the token holders.

Contract Details

State Variables
tokenName: The name of the token, "YogeshRajput".
tokenAbbrv: The abbreviation of the token, "YR".
totalSupply: The total supply of the tokens in circulation.
balances: A mapping that holds the balance of each address.

Functions
The mint function allows for the creation of new tokens. It increases the totalSupply by _value and adds the _value to the balance of _address.
The burn function allows for the destruction of existing tokens. It decreases the totalSupply by _value and deducts the _value from the balance of _address, provided that _address has enough tokens to burn.

Usage
To deploy and interact with this smart contract, you need to have a development environment like Remix or a local Ethereum testnet setup. Below are the steps to deploy and use the contract:

License
This project is licensed under the MIT License. See the LICENSE file for details.

Author
Yogesh Rajput
