# EVM-basics
This is a Solidity contract called "MyToken" which represents a basic implementation of a token contract. Tokens are digital assets that can represent ownership, value, or rights, and they are commonly used in blockchain-based systems.

# Features
The contract includes public variables for storing token information, such as token name, token abbreviation, and total supply.
It utilizes a mapping variable to keep track of token balances for different addresses.
The contract has a "mint" function that allows for creating new tokens by increasing the total supply and updating the balance of the target address.
It also has a "burn" function that allows for burning tokens by decreasing the total supply and updating the balance of the target address.

# Usage
To use this contract, you can deploy it on the Ethereum blockchain using a Solidity compiler and an Ethereum development framework such as Remix, Truffle, or Hardhat. Once deployed, you can interact with the contract by calling its functions using a compatible Ethereum wallet or a smart contract interaction tool like MyEtherWallet, MetaMask, or ethers.js.

The following are the main functions available in the contract:

# mint(address _address, uint value)
This function allows for creating new tokens by minting them to the specified address. It takes two parameters:

_address: The target address to mint tokens to.
value: The amount of tokens to mint.

# burn(address _address, uint value)
This function allows for burning tokens by reducing the total supply and updating the balance of the specified address. It takes two parameters:

_address: The target address to burn tokens from.
value: The amount of tokens to burn.
Please note that the contract does not include any access control mechanisms, so anyone can call the mint and burn functions. If you plan to use this contract in a production environment, it is recommended to implement appropriate access control measures to ensure secure token management.

# License
This contract is released under the GNU General Public License v3.0, which is a free and open-source software license. You can find the license text in the SPDX-License-Identifier comment at the beginning of the contract.
